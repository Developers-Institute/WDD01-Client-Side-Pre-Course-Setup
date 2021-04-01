# Setting Windows up for a development environment

Our normal developer's environment (macOS) is based on a UNIX operating system and allows us to build our software or websites from within a similar environment then what it would be serving once deployed(hosted).

Windows has introduced a very deeply integrated way of running a Linux operating system inside of a Windows environment allowing us to have very similar functionality as with macOS.

[What is WSL2](https://youtu.be/48k317kOxqg)

## Requirements

- A motherboard supported with Hyper-V (check your [BIOS](https://www.youtube.com/watch?v=ncUmWthHrU0))
- Windows 10 PRO with Insider Preview
- For x64 systems: Version 1903 or higher, with Build 18362 or higher. Please check the [documentation](https://docs.microsoft.com/en-us/windows/wsl/install-win10#requirements) on the latest recommended version.
  - How to Check what Windows 10 Build you have:
    1. Right-click the start menu and choose Run.
    2. In the Run window, type `winver` and press OK.
    3. The window that opens will display the Windows 10 build that is installed

## WSL2 installation steps

For the most up to date steps, we would recommend following the [windows documentation](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

Note: When deciding on what Linux distribution to use you can use any but we recommend using the [latest LTS version of Ubuntu](https://ubuntu.com/about/release-cycle)

## Docker installation steps

Docker will be a requirement in later papers. The installation steps specific to WSL2 can be found at [Docker Documentation](https://docs.docker.com/docker-for-windows/wsl/)

## Windows Terminal installation

For the best experience developing in a Windows environment, we recommend you use the latest [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab)

## VS Code installation

While inside the WSL2 terminal just type `code .` and VS Code will start the installation process.
