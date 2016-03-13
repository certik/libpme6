# Build

How to build:

    hit load d4
    export PKG_CONFIG_PATH=$HASHSTACK/lib/pkgconfig
    cmake -DCMAKE_PREFIX_PATH=$HASHSTACK .
    make

How to run:

    ./make-box 4 1
    ./run-pme 64 cell.mat positions.mat charges.mat 20 1e-10
