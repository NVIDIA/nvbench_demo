# Quick Start

```
git clone --recursive https://github.com/allisonvacanti/nvbench_demo.git

cd nvbench_demo

# Use your actual target architecture(s) or omit the option:
cmake -DCMAKE_CUDA_ARCHITECTURES=70-real .

make

./example_bench
```
