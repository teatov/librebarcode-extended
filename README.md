A fork of [Libre Barcode](https://github.com/graphicore/librebarcode) with extra glyph sets for Code 128.

Intended for decorative purposes only, since there are no actual standards for non-ASCII barcode symbols and no scanner software will be able to work with this.

Glyph sets added:
- Cyrillic.

  The barcode patterns are taken from standard ASCII symbols, using mappings from [KOI-7](https://en.wikipedia.org/wiki/KOI-7). So, for example, letter Г uses the pattern for G, З uses Z, etc. That way the barcode remains kind of usable, the text will just be encoded in KOI-7.

  ![](documentation/librebarcode-extended-dem.png)

The original Libre Barcode uses [Inconsolata](https://levien.com/type/myfonts/inconsolata.html) as the text-below font. This fork uses [Inconsolata LGC](https://github.com/MihailJP/Inconsolata-LGC).

---

Consult the original README [here](https://github.com/graphicore/librebarcode#).
