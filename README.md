# IT003.M21.PMCL-Nhom14
> This repository is just big project =)))  

[![Build Status](https://img.shields.io/github/workflow/status/hoanghy0112/IT003.M21.PMCL-Nhom14/Build%20Project?style=for-the-badge)](https://github.com/hoanghy0112/IT003.M21.PMCL-Nhom14/actions)
[![Release Status](https://img.shields.io/github/workflow/status/hoanghy0112/IT003.M21.PMCL-Nhom14/Lastest%20Release?label=RELEASE&style=for-the-badge)](https://github.com/hoanghy0112/IT003.M21.PMCL-Nhom14/actions)
![Languages](https://img.shields.io/github/languages/top/hoanghy0112/IT003.M21.PMCL-Nhom14?style=for-the-badge)
![Repo Size](https://img.shields.io/github/repo-size/hoanghy0112/IT003.M21.PMCL-Nhom14?style=for-the-badge)
![License](https://img.shields.io/github/license/hoanghy0112/IT003.M21.PMCL-Nhom14?style=for-the-badge)
[![Download](https://img.shields.io/github/downloads/hoanghy0112/IT003.M21.PMCL-Nhom14/v1.x.x/total?style=for-the-badge)](https://github.com/hoanghy0112/IT003.M21.PMCL-Nhom14/releases/tag/v1.x.x)

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
