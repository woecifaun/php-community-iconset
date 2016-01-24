# PHP Community Iconset

A collection of icons for your operating system[<sup>1</sup>](#note1) related to the php community and its user groups.

## :package: [Get the latest release](https://github.com/woecifaun/php-community-iconset/releases)


## Why?

Just for fun 😜

## How to customize your folder/item icon?

### Mac

1. Find the element you want to custom in the Finder
2. Display the element information (Right click > Get Info or Cmd+i)
3. Open the folder containing the icon. Attention, the latter window must not overlap the "Get Info" panel of the target element
4. Drag and drop the wanted icon file onto the current icon in the "Get Info" panel.

Voila!

## Generating the iconset

This repository does not hold the final generated icons. It only contains icon sources and the binary generator. You can find the usable icon set in the release section of this repository.

You can also generate the final icon set, by running the following command in the root folder of the project.
```shell
./iconify
```

Once generated, the .zip for the release can be built by running
```shell
./release
```

Tags are built on the following scheme `v{int}` where `int` just increments the last release. Release should only be created when a new icon is added.

---

> <sup id="note1">1</sup> Currently only available for Mac OS X. Any contribution to port the set to other systems is welcome.
