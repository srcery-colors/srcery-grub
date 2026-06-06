<p align="center">
  <img src="https://raw.githubusercontent.com/srcery-colors/srcery-assets/master/src/logo_border.svg">
</p>

<p align="center">
  <a href="https://srcery.sh">
    <img src="https://img.shields.io/static/v1?label=&message=Website&style=flat&color=5B5B5B&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAA7MAAAOzAGxoQZ+AAAAGXRFWHRTb2Z0d2FyZQB3d3cuaW5rc2NhcGUub3Jnm+48GgAAAdJJREFUOI1jDAgIYMAFTp8+EcrIyMRqYmK2DJcaJlwS548fV2RjYJnNxsg87fzx44okGbBhwwaWvyyMSzM4dfgrlGz5/7IwLt2wYQML0QZIS0s2mLFIWIZxqDKkyJowuAirWkpLSzYQZcDZsyfthJnYK2p4TBkYGRgYGBkYGXo0PBjE2XgqT58+7oTXgHPnzgky/GNYXMFlwizEyAEXF2bjYujX9GJiYmBedPr0aWGcBvz793teOIeanBWrJIZT7YQUGFJkTaQZGf4v3LBhAyOGAWdPn8hUZxYIyODUweZVBgYGBoYqZXsGQz5Jb1lpiQycYUAqgBtgbGox/ebfDxtmfL+CU3Hb3YMM5z893/r46YsZWF3AxMSatPLHrUfHfj/H0Hzo3QOGOY/PPP3PwBgfEBDwH6sBRkZG7xmYGGI7vp35++7/D7j421/fGAqvb/v3j+FvnKmp6VusXoB7xdj80Nt/Pztavpxm+M/AwPCf4T9DyY0dDC9/fWk3NbXchzMMkMHTp88bTv15cXzVj9sMcx6fYdjz9vbxp0+fN2BTy4grN54/flyRiYX1PCMTI8PfX78MDS0t72NThzMaDS0t7//5/y/z99+/mbg0MzAwMAAAVbWgDHTwVjUAAAAASUVORK5CYII=">
  </a>
  <a href="https://discord.gg/G6vBMmZ">
    <img src="https://img.shields.io/discord/714101903377694741?color=%232C78BF&label=Discord&logo=discord">
  </a>
  <a href="https://www.npmjs.com/package/@srcery-colors/srcery-palette">
    <img src="https://img.shields.io/npm/v/@srcery-colors/srcery-palette?color=%23FBB829&label=Palette%20version&logo=npm">
  </a>
</p>

<h2 align="center">GNU GRUB</h2>

<p align="center">
Official theme for the <a href="https://www.gnu.org/software/grub/">GNU GRUB</a> multiboot boot loader.
</p>

## Requirements

- [GNU GRUB](https://www.gnu.org/software/grub/)


## Installation

- Copy the `srcery` folder from this reposittory to `/boot/grup2/themes`
- Set `GRUB_THEME` in `/etc/default/grub` to `GRUB_THEME=/boot/grub2/themes/srcery/theme.txt`
- Set `GRUB_TERMINAL_OUTPUT="gfxterm"`
- Run `sudo grub2-mkconfig -o /boot/grub2/grub.cfg`
- Reboot

## Screenshots

## Acknowledgement

- https://github.com/be5invis/Iosevka for fonts.
- https://github.com/voidlhf/StarRailGrubThemes for icons.
