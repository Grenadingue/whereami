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

| Operating system | Distribution    | Compatibility | P. OS  | P. Distrib | P. Kernel | P. Processor |
|------------------|-----------------|---------------|--------|------------|-----------|--------------|
| Linux            | Arch Linux      | Yes           | Yes    | Yes        | Yes       | Yes          |
| Linux            | Debian          | Yes (jessie)  | Yes    | Yes        | Yes       | Yes          |
| Linux            | SUSE            | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Linux            | RedHat          | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Linux            | Fedora          | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Linux            | Slackware       | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Linux            | Mandrake        | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Linux            | YellowDog       | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Linux            | Gentoo          | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Linux            | UnitedLinux     | Not tested    | Yes    | Yes        | Yes       | Yes          |
| Mac OS X         | OS X*           | Not tested    | Yes    | No         | No        | No           |
| SunOS (Solaris)  | Solaris*        | Not tested    | Yes    | No         | No        | Yes          |
| AIX              | AIX*            | Not tested    | Yes    | No         | No        | No           |
| Windows          | *               | Not tested    | Yes    | No         | No        | No           |

### Emulated environments
*Note: "P." stands for "Print", "E." for "Emulated"*  
| Operating system | Unix emulator | Compatibility | P. Emulator | P.E. Kernel | P.E. Processor |
|------------------|---------------|---------------|-------------|-------------|----------------|
| Windows          | Cygwin        | Yes           | Yes         | Yes         | Yes            |
| Windows          | Msys (MinGW)  | Yes           | Yes         | Yes         | Yes            |
