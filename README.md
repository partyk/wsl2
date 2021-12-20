# wsl2
Windows Subsystem for Linux

## wsl command
```wsl --update``` aktualizace WSL kernelu

```wsl --status``` ukáže aktualni distribuci a verzi WSL

```wsl --list``` výpis instalovaných distribucí

```wsl --list --online``` výpis dostupných distribucí

```wsl --install -d DISTRO-NAME``` instalace distribuce

```wsl --unregister``` smazání distribuce

```wsl --set-default``` nastavení výchozí distribuce

## wsl export image

```wsl --export <DistributionName> <PATH/FILENAME.tar>```

example

```wsl --export Ubunut d:\Ubuntu.tar``` image s Ubuntu

```wsl --export docker-desktop-data d:\docker-desktop-data.tar``` image s docker kontejnery

![!](https://winaero.com/blog/wp-content/uploads/2019/02/Windows-10-export-WSL-distro.png "")

## wsl import image

```wsl --import <DistroName> <InstallLocation> <InstallTarFile>```

example

```wsl --import Ubuntu c:\wsl d:\ubuntu.tar```

![!](https://winaero.com/blog/wp-content/uploads/2019/02/Windows-10-import-WSL-distro-624x170.png "")

## nastavení výchozího uživatele

```my-wsl2-distro.exe config --default-user my-user```

example

```Ubuntu config --default-user partyk```

## odkazy

https://github.com/microsoft/WSL/issues/4276

https://www.tenforums.com/tutorials/128152-set-default-user-windows-subsystem-linux-distro-windows-10-a.html

https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/

https://winaero.com/export-import-wsl-linux-distro-windows-10/
