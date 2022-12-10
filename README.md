# Disadvantage 68 Keyboard

This keyboard is a fork of [dactyl-cc](https://github.com/adereth/dactyl-keyboard).

Diferences with *dactyl-cc*:

- Fixed switch hole sizes (if you print the current version of dactly-cc, you will have a bad time).
- Fixed screw hole sizes for M3 screws and "brass insert nut" ([AliExpress](https://www.aliexpress.com/item/1005004870993068.htm)).
    ![nut](pictures/screw_insert.png)

CMake is the preferred way to build and leads to the fastest recompilation times.

```bash
cd build
./build.sh
```

If you do not have cmake installed you can run the simple build script which just uses g++.

```bash
cd build
./build_simple.sh
```

You can generate an stl from the command line with the following command:

```bash
cd build
// openscad -o ../things/left.stl left.scad
make_things.sh
```
