# system_stress
This repo contains the procedure of system level stress for cpu and ddr. 

## Project Structure

```
test_content
├── bin
├── common
│   ├── inc
│   │   └── common.h
│   └── src
│       └── common.c
├── deps
│   ├── Makefile
│   ├── stress-ng.tar.xz
│   └── sysstat.tar.xz
├── doc
│   ├── ddr
│   ├── ufs
│   ├── usb
|   └── cpu_stress
│       └── readme_cpu_stress.md
├── Makefile
├── README.md
├── subsystem
│   ├── benchmark
│   ├── cpu
│   │   ├── cpu_stress
│   │   │   ├── cpu_stress.conf
│   │   │   ├── inc
│   │   │   │   └── cpu_stress.h
│   │   │   ├── Makefile
│   │   │   └── src
│   │   │       └── cpu_stress.c
│   │   └── Makefile
│   ├── ddr
│   ├── ufs
│   ├── usb
│   └── vpu
└── testreport

```

## Project Compilation Procedure

1. Clone the source using below link
    * [system_stress](https://github.com/kumaramit124/system_stress)

2. Change the directory to the system_stress using below command
    * cd system_stress

3. export the ndk toolchain path
    * export PATH=$PATH:~/Android/Sdk/ndk/<ndk version dir name>/toolchains/llvm/prebuilt/linux-x86_64/bin

4. Run the below command to compile.
    * make

