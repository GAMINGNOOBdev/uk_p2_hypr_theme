# ULTRAHYPRTHEME
ULTRAKILL Theme files for Hyprland

## Screenshots
> [!NOTE]
> Screenshots were taken in a hurry inside a qemu vm.

### P-2 Theme
![P-2 Theme](/screenshots/p2.png)

### Fraudulence Theme
![Fraud 8-1 Theme](/screenshots/fraud.png)

## Prerequisites
You have to have archlinux. Why? Too lazy to add support to detect the package manager of choice.
You have to have `yay`, `python3` and `git` installed.
The extra packages such as hyprland, waybar, fastfetch, hyprpaper and so on will get installed by the install shell script.

## Installation
First of all, clone this repository by running:
```bash
git clone https://github.com/GAMINGNOOBdev/uk_hypr_theme
```

After that you can change into the cloned repository and run the install script:
```bash

cd uk_hypr_theme
bash install_packages.sh
python3 install.py
cd ..

```
Aaaaaand you're done.
Now...

<s><b> H A V E   F U N </b></s>

## Bug finders

[pradosh-arduino](https://github.com/pradosh-arduino) found out that the `poppler-glib` package is sometimes necesary.

## Credits

The installer automatically downloads the library [simple term menu](https://github.com/IngoMeyer441/simple-term-menu) by IngoMeyer441.
