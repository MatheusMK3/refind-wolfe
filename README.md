## Wolfe rEFInd Theme

This is a custom theme I use for [rEFInd](http://www.rodsbooks.com/refind/), an easy to use boot manager for EFI
based systems.

It's currently based in these themes:

- [refind-minimal](https://github.com/EvanPurkhiser/rEFInd-minimal/) for most base stuff, as it was my previous theme in use
- [refind-black](https://github.com/anthon38/refind-black/) for the base icons, which I'm currently adding some shadows and details to

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/rEFInd-wolfe/theme.conf` at the end of
    `refind.conf`.

Entries that are autodetected should show the proper icons, though at first only icons I actually use are featured (so expect stuff to look weird at first).

### Background

The background is something based on my own branding, but feel free to replace and use something you like!