# lyrics
lyrics is a simple program for displaying lyrics in the terminal.

## Overview
`lyrics` is straightforward. The user gives it a search term and it outputs the lyrics to `stdout`. If it doesn't find any lyrics, it will return nothing to `stdout` and an exit code of `1`, otherwise `0`.

The above paragraph describes the whole program, it does nothing more nothing less.

## Usage 
- Give a song name as the arguments
```sh
lyrics "Lonely Akon"
```
- The search term is not required to be surrounded by quotes, anything after lyrics will be included as the search term:
```sh
lyrics somewhere only we know
```
- For better navigation, the output can be piped to a terminal pager like `less`
```sh
lyrics perfect ed sheeran | less
```

## Demo
![ezgif com-gif-maker](https://github.com/codelif/lyrics/assets/68972644/a0093182-2459-4d49-b618-b14e4eb04cf1)

## License
    
    This is free and unencumbered software released into the public domain.
    
    Anyone is free to copy, modify, publish, use, compile, sell, or
    distribute this software, either in source code form or as a compiled
    binary, for any purpose, commercial or non-commercial, and by any
    means.
    
    In jurisdictions that recognize copyright laws, the author or authors
    of this software dedicate any and all copyright interest in the
    software to the public domain. We make this dedication for the benefit
    of the public at large and to the detriment of our heirs and
    successors. We intend this dedication to be an overt act of
    relinquishment in perpetuity of all present and future rights to this
    software under copyright law.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
    IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
    OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
    ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
    OTHER DEALINGS IN THE SOFTWARE.
    
    For more information, please refer to <https://unlicense.org>
