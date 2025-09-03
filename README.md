# Lua libraries that are interesting
- [middleclass](https://github.com/kikito/middleclass), Object oriented support for Lua
- [luasocket](https://github.com/lunarmodules/luasocket), non-block POSIX socket support for Lua
- [cqueues](https://github.com/wahern/cqueues), event driven programming using Lua's coroutines.
- [Penlight](https://github.com/lunarmodules/Penlight), a collection of Lua libs that aims to make the language battery included.
- [copas](https://github.com/lunarmodules/copas), network events dispatcher using Lua' coroutine, can be used with 'luasocket'.
- [luasec](https://github.com/lunarmodules/luasec), SSL support for Lua.
- [busted](https://github.com/lunarmodules/busted), Unit testing Lua code.
- [sol2](https://github.com/ThePhD/sol2), generate C++ binds for Lua code.

# Use multiple versions of Lua together
On my Linux machin, Lua5.1 and `luarocks` are installed by the system package manager.
While Lua5.4 is installed in `$HOME/home_local`, and a seperate `luarocks` for it
is configured by `./configure --lua-version=5.4 --lua-suffix=5.4 --with-lua-bin=/home/johnzli/home_local/bin --versioned-rocks-dir --prefix=/home/johnzli/home_local/`.
