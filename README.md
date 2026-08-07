# Archivo APT de Nexus AI OS

Canal de actualización de [Nexus AI OS](https://github.com/ndf14685/nexus-ai-os)
(derivada de Debian 13). Bootstrap en un Debian/Nexus instalado:

```sh
wget https://www.nestorfleitas.ar/nexus-apt/nexus-archive-keyring_0.11.0_all.deb
sudo apt install ./nexus-archive-keyring_0.11.0_all.deb
sudo apt update && sudo apt install nexus-os-desktop
```

Después, todo llega con `sudo apt update && sudo apt upgrade`.
Generado por `distro/apt/` del repo principal — no editar a mano.
