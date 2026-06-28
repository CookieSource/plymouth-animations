# Yay animations! 

A small collection of fun, silly, and slightly unnecessary Plymouth boot animations.

This repo contains different Plymouth themes I made either because I wanted something custom, or simply because watching Cookie Monster roll across the screen is objectively important Linux work.

## Themes included

At the moment this repo contains:

- `Aerynos-minimal`
- `Aerynos-Full`
- `Aerynos-alternative-minimal`
- `Aerynos-alternative-full`
- `Cookiemonster-cookie-roll`

## Preview 
Coming I swear !!

## Installation

Copy the theme folder you want into your Plymouth themes directory:

```bash
sudo cp -r ThemeName /usr/share/plymouth/themes/
```
On most distros you also need to rebuild the initramfs.

```bash
sudo mkinitcpio -P
```
Testing without rebooting
You can test a theme manually with:
```
sudo plymouthd
```
To stop it again:
```
sudo plymouth quit
```
