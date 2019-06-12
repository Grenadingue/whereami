# whereami
Get informations about current execution environment from a unix* shell

## Description

This script tries to detect and display:
* Operating system
* System distribution
* Kernel informations
* Processor architecture
* Unix emulated environment informations (if available)

## Compatibility
### Operating systems
*Note: "P." stands for "Print"*  

| Operating system | Distribution    | Tested       | P. OS  | P. Distrib | P. Kernel | P. Processor |
|------------------|-----------------|--------------|--------|------------|-----------|--------------|
| Linux            | Arch Linux      | Yes          | Yes    | Yes        | Yes       | Yes          |
| Linux            | Debian          | Yes (jessie) | Yes    | Yes        | Yes       | Yes          |
| Linux            | SUSE            | No           | Yes    | Yes        | Yes       | Yes          |
| Linux            | RedHat          | No           | Yes    | Yes        | Yes       | Yes          |
| Linux            | Fedora          | No           | Yes    | Yes        | Yes       | Yes          |
| Linux            | Slackware       | No           | Yes    | Yes        | Yes       | Yes          |
| Linux            | Mandrake        | No           | Yes    | Yes        | Yes       | Yes          |
| Linux            | YellowDog       | No           | Yes    | Yes        | Yes       | Yes          |
| Linux            | Gentoo          | No           | Yes    | Yes        | Yes       | Yes          |
| Linux            | UnitedLinux     | No           | Yes    | Yes        | Yes       | Yes          |
| BSD              | \*BSD\*         | No           | Yes    | Yes        | Yes       | Yes          |
| Darwin           | macOS           | No           | Yes    | Yes        | Yes       | No           |
| SunOS (Solaris)  | Solaris*        | No           | Yes    | No         | No        | Yes          |
| AIX              | AIX*            | No           | Yes    | No         | No        | No           |
| Windows          | 10              | Yes          | Yes    | Yes        | Yes       | Yes          |
| Windows          | 8.1             | No           | Yes    | Yes        | Yes       | Yes          |
| Windows          | 8               | No           | Yes    | Yes        | Yes       | Yes          |
| Windows          | 7               | No           | Yes    | Yes        | Yes       | Yes          |

### Emulated environments
*Note: "P." stands for "Print", "E." for "Emulated"*  

| Operating system | Unix emulator | Tested    | P. Emulator | P.E. Kernel | P.E. Processor |
|------------------|---------------|-----------|-------------|-------------|----------------|
| Windows          | Cygwin        | Yes (10)  | Yes         | Yes         | Yes            |
| Windows          | Msys (MinGW)  | Yes (10)  | Yes         | Yes         | Yes            |
