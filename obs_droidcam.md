# INSTALACIÓN DE DrindCamClient CON OBS
#### Se puede instalar buscando los comando en la pagina del siguiente link ó usar los camandos siguientes
> https://www.dev47apps.com/
```bash
sudo apt update
sudo apt install flatpak
#### Reinicia sesión o pc para que se apliquen los cambios, luego ejecutar los siguientes comandos
flatpak install flathub com.obsproject.Studio
flatpak install flathub com.obsproject.Studio.Plugin.DroidCam
flatpak override --user --device=all com.obsproject.Studio #(override for v4l2loopback access, see below)
```
