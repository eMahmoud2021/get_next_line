`get_next_line` is a function that reads a line from a file descriptor and returns it as a string. It allows reading text from the file descriptor one line at a time until the end of the file. The function is designed to mimic the behavior of the standard `getline()` function. 
## Features
- Read a line from a file descriptor
- Returns the line as a string
- Supports reading from multiple file descriptors

## Usage
To use the `get_next_line` function in your project, follow these steps:

1. Copy the following files into your project directory:
   - `get_next_line.c`
   - `get_next_line_utils.c`
   - `get_next_line.h`

2. Include the `get_next_line.h` header file in your source code:
   ```c
   #include "get_next_line.h"
   ```

3. Call the `get_next_line` function to read lines from a file descriptor.

## Bonus (Optional)
The bonus part of the project aims to enhance the functionality of `get_next_line`. To complete the bonus part, make sure the mandatory part is perfect and then implement the following:

- Use a single static variable to succeed `get_next_line`.
- Manage multiple file descriptors, allowing reading from different file descriptors without losing the reading thread.

## External Functions
- `read`: Used to read data from the file descriptor.
- `malloc`: Used to allocate memory dynamically.
- `free`: Used to free allocated memory.

## Resources
For more information on `get_next_line` and related concepts, you can refer to the following resources:

- [Wikipedia - Static Variable](https://en.wikipedia.org/wiki/Static_variable)
- `man` pages:
  - `man 3 read`
  - `man 3 malloc`
  - `man 3 free`

**Note:** The `BUFFER_SIZE` macro can be modified to adjust the buffer size used for reading. However, during evaluation, the value will be modified to test different buffer sizes.
