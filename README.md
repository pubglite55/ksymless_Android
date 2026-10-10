# KallRecon

<p align="center">
  <a href="https://github.com/pubglite55/ksymless_Android/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/pubglite55/ksymless_Android?style=flat-square&label=Stars"></a>
  <a href="https://github.com/pubglite55/ksymless_Android/commits/main"><img alt="Last Commit" src="https://img.shields.io/github/last-commit/pubglite55/ksymless_Android?style=flat-square&label=Last%20Commit"></a>
  <a href="https://github.com/pubglite55/ksymless_Android/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/github/license/pubglite55/ksymless_Android?style=flat-square&label=License"></a>
</p>

discovers and reconstructs the kallsyms symbol table from kernel
image memory on ARM64 GKI. locates kallsyms_lookup_name to provide
symbol resolution from within an LKM. inspired by
[ksymless](https://github.com/rota1001/ksymless) and depends only on
sprint_symbol.

on kallsyms: [xcellerator](https://xcellerator.github.io/posts/linux_rootkits_11/)

## requirements

- ARM64 device with GKI kernel
- sprint_symbol exported

## credits

Thanks to [汐の月](https://www.coolapk.com/u/1550124) for providing
the device for GKI 6.6 testing.

Thanks to [阿尔托莉雅·潘德拉贡](https://www.coolapk.com/u/41654149) for providing
the device for GKI 6.1 testing.

Thanks to [小初](https://www.coolapk.com/u/42372039) for providing
the device for GKI 6.1 testing.

Thanks to [haohao3001](https://github.com/haohao3001) for providing
the device for GKI 6.12/5.15 testing.

Thanks to [mx_wj](https://github.com/mx-wj) for providing
the device for GKI 6.1 testing.

Thanks to [pubglite55](https://github.com/pubglite55) for providing
the device for GKI 5.15 testing.

## license

GPL-2.0
