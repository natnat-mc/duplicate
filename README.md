# duplicate
A small duplicate tester, using xxhash32 (or falling back to md5sum), written in lua5.3

## Using duplicate
- make sure you have `find` and `xxhash32` (or `xxhash`, or even `md5sum` which is massively slower) in your path
- make sure you have `lua5.3` installed and in your path
- ideally copy `duplicate` in your path
- `duplicate <directory to test>`
