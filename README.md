# ravi-luaossl
Most comprehensive OpenSSL module in the Lua universe.

This fork of luaossl has following changes:

* Uses a CMake build system
* The names of the C library functions / and the library have been changed (upstream project calls the Lua library `openssl`).
* The Lua code and the C code have been seperated.

## Some build dependencies

* On Ubuntu you will need to install `libssl-dev`.
* On Mac OSX you will need to install openssl via brew.
