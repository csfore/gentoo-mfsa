# gentoo-mfsa

Simple script to automate the tedious portion of reporting MFSAs to Gentoo

## Usage

[!NOTE]
This assumes the `announce` directory from [Foundation Security Advisories](https://github.com/mozilla/foundation-security-advisories) is in the current directory as of 2024-08-05

Provide numbers after the name of the script for the report, i.e. 30, 31, and 32:

```
$ gentoo-mfsa 30 31 32
```

And it should output a template to copy/paste into the products' respective bugs.

## Todo

- [ ] Add arguments for various options (argparse?)
- [ ] 
