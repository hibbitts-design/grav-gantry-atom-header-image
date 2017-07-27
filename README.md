# Gantry 5 'Header Image' Atom for Grav

Atoms are small, modular blocks with preset scripting that enable you to add elements to your Grav Gantry 5 pages.

## Installing the Atom

Before installing and using the Atom, it is suggested you temporarily enable Gantry's [`Development Mode`](http://docs.gantry.org/gantry5/configure/extras)

1. Open the active theme folder in your `user/data/gantry5/themes/` your Gantry installation. For example, if you are using the Hydrogen theme open the folder `user/data/gantry5/themes/g5_hydrogen`.
2. If a `particles` folder already exists within the `custom` folder open it, otherwise create it.
4. Upload `headerimage.html.twig` and `headerimage.yaml` files into the `particles` folder. For example, if you are using the Hydrogen theme copy the two particle files into `user/data/gantry5/themes/g5_hydrogen/particles`.

## Using the Atom
1. Add the Atom to your theme's 'Atoms' area on the 'Page Settings' panel.
2. Create a folder called 'headerimage' at root level of your site or within any page folder
3. Copy the image you want to be displayed for your headerimage
4. Create a file called `default.md` and include the following with that file:

```
---
title: HeaderImage
published: false
routable: false
---
```
