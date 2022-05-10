# IT003.M21.PMCL-Nhom14 ![](https://github.com/hoanghy0112/IT003.M21.PMCL-Nhom14/actions/workflows/build.yml/badge.svg) ![](https://github.com/hoanghy0112/IT003.M21.PMCL-Nhom14/actions/workflows/release.yml/badge.svg)

This repository is just big project =)))

## I. Requirements
- Windows OS (just only Windows, not Linux)
- Visual Studio (any version)
- CMake 3.10.2 or above

## II. Install
- Clone repository
```bash
git clone https://github.com/hoanghy0112/IT003.M21.PMCL-Nhom14.git
cd IT003.M21.PMCL-Nhom14/
```

- Clone submodule repository
```bash
git submodule update --init --recursive
```

- Build project form sources
```bash
mkdir build
cd build
cmake .. -DCMAKE_BUILD_TYPE=MinSizeRel -DBUILD_SHARED_LIBS=OFF -G"Visual Studio 17 2022" -Ax64
cmake --build . --config MinSizeRel
```

- Run project
```
Find an application that named IT003.M21.PMCL-Nhom14.exe
Now, run it!!!
```