## Meson And Conan Sample Project

This is a sample project that uses Meson Build system and Conan Package Manager.

###

choco install pkgconfiglite

###

### How to build

    $ mkdir build && cd build
    $ conan install ..
    $ conan build ..

### How to debug

    $ mkdir debug && cd debug
    $ conan install .. --settings build_type=Debug
    $ conan build ..
