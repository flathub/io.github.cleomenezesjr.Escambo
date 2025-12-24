# Escambo

___Test and develop APIs___

Escambo is an HTTP-based APIs test application for GNOME.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub io.github.cleomenezesjr.Escambo
flatpak run io.github.cleomenezesjr.Escambo
```

## Building

```
git clone git@github.com:flathub/io.github.cleomenezesjr.Escambo.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install io.github.cleomenezesjr.Escambo.json
```

---

**Technologies**: GNOME, GTK4, Libadwaita, Python
