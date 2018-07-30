# Y86-Simulator-macOS

Build Y86 Simulator on macOS

## Download

```shell
git clone git@github.com:lizebang/Y86-Simulator-macOS.git
```

## Installation

I have made the necessary changes. All you have to do is decompress and compile.

```shell
tar -xf sim.tar
cd sim
make clean
make
```

## Run

I just run `sim/y86-code/abs-asum-cmov.yo` for example.

```shell
cd seq
./ssim -g ../y86-code/abs-asum-cmov.yo
```

Warning: You must run in the `sim/seq` directory. If not, an error accours.
