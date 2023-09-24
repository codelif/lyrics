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

