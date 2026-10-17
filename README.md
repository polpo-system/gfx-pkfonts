# gfx-pkfonts

GfxPKFonts for [polpo](https://github.com/polpo-system/polpo): the packed raster fonts of TeX (.pk)
as fonts of Gfx (the package gfx). `GfxPKFonts.Install` in the section FontFormats of Oberon.Text
makes Gfx look for them.

```
portia.Install gfx-pkfonts
```

## What is here

    src/OLR.GfxPKFonts.Mod     the PK font reader
    test/GfxPKFontsTest.Mod

The source comes from ETH Linux Oberon (OLR, 2017-06-18), converted from an Oberon text to plain
text; the first commit has it unchanged. It compiles unchanged with all five of polpo's compilers
(x86, ARM, ARMv7, RISC-V, MIPS).

## Tests

    GfxPKFontsTest.Run      1 check: the module loaded; it needs the desktop's display

The license is GPL-3 (`LICENSE`); the code comes from ETH Oberon, whose license (`LICENSE.ETH`)
asks to keep its copyright notice and conditions, which `LICENSE.ETH` does.
