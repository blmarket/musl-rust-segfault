# SSCCE for segfault with rust + musl-g++


    # works
    make cxx

    # works
    make cxx CXX=/path/to/musl-g++

    # works
    make rust

    # segfaults
    make rust-musl
