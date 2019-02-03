# game-of-life
[![GitHub license](https://img.shields.io/github/license/jellycsc/game-of-life.svg)](https://github.com/jellycsc/game-of-life/blob/master/LICENSE)

🔯[Rule 90](https://en.wikipedia.org/wiki/Rule_90), a 1D variant of the [Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life).

## Getting Started

### Prerequisites

* GCC
* Shell (Bash is recommended)

### Download source code and compile
The following instructions are presented using Bash in macOS:
```
# Change to HOME directory
$ cd ~

# Clone this repo and 'cd' into it
$ git clone https://github.com/jellycsc/game-of-life.git
$ cd game-of-life/

# Let's compile.
$ make
gcc -Wall -std=gnu99 -g -c life.c
gcc -Wall -std=gnu99 -g -c life_helpers.c
gcc -Wall -std=gnu99 -g -o life life.o life_helpers.o
```

### Usage
```
USAGE: life initial n
```

## Examples
```
$ ./life ......X.......X.......X...... 10
......X.......X.......X......
.....X.X.....X.X.....X.X.....
....X...X...X...X...X...X....
...X.X.X.X.X.X.X.X.X.X.X.X...
..X.......................X..
.X.X.....................X.X.
....X...................X....
...X.X.................X.X...
..X...X...............X...X..
.X.X.X.X.............X.X.X.X.
```

## Auto test
```
$ make test_life
Compiled and life check passed :)
```

## Author(s)

| Name                    | GitHub                                     | Email
| ----------------------- | ------------------------------------------ | -------------------------
| Chenjie (Jack) Ni       | [jellycsc](https://github.com/jellycsc)    | nichenjie2013@gmail.com

## Thoughts and future improvements

* Since this is a rather simple beginner's project, no further improvements will be made.

## Contributing to this project

1. Fork it [![GitHub forks](https://img.shields.io/github/forks/jellycsc/game-of-life.svg?style=social&label=Fork&maxAge=2592000&)](https://github.com/jellycsc/game-of-life/fork)
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to your feature branch (`git push origin my-new-feature`)
5. Create a new Pull Request

Details are described [here](https://git-scm.com/book/en/v2/GitHub-Contributing-to-a-Project).

## Bug Reporting [![GitHub issues](https://img.shields.io/github/issues/jellycsc/game-of-life.svg?)](https://github.com/jellycsc/game-of-life/issues/)

Please click `issue` button above↑ to report any issues related to this project  
OR you can shoot an email to <nichenjie2013@gmail.com>

## License
This project is released under GNU General Public License v3.0 - see [LICENSE](LICENSE) file for more details.
