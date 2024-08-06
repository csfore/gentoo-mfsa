# gentoo-mfsa

Simple script to automate the tedious portion of reporting MFSAs to Gentoo

## Usage

Provide numbers after the name of the script for the report, i.e. 30, 31, and 32:

```
$ gentoo-mfsa 01 02 03
```

To change the select year, use `-y` or `--year`:

```
$ gentoo-mfsa -y 2023 01 02 03
```

To change the directory the `announce/` directory is contained in, use `-d` or `--dir`:

```
$ gentoo-mfsa -d ../announce 01 02 03
```

And it should output a template to copy/paste into the products' respective bugs.

## Todo

- [x] Add arguments for various options (argparse?)
