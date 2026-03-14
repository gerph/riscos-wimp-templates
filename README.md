# Wimp template loading library

This repository holds a library for loading Template files (definitions of windows)
for use inside the RISC OS WindowManager.
It is intended for use with the RISC OS 64 project (which aims to bring RISC OS
towards a 64-bit system).

The template loading library implements the internal and external calls for the
WindowManager, specifically the `Wimp_OpenTemplate`, `Wimp_LoadTemplaet` and
`Wimp_CloseTemplate` interfaces.
These allow applications and modules to load window definitions from the Template
files in the same way as RISC OS Classic.

The library implements the components described within the RISC OS 64 project. See
[WindowManager (Templates)](https://github.com/gerph/riscos64-status/wiki/Module_WindowManager_Templates) for more details.

