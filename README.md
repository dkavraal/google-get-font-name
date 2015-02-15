# google-get-font-name
Google Fonts ttf otf woff woff2 eot url extractor

eg.


```bash
# python getfont.py Roboto latin 400 ttf
http://fonts.gstatic.com/s/roboto/v15/zN7GBFwfMP4uA6AR0HCoLQ.ttf
```

```bash
# python getfont.py Roboto
http://fonts.gstatic.com/s/roboto/v15/ek4gzZ-GeXAPcSbHtCeQI_esZW2xOQ-xsNqO47m55DA.woff2
http://fonts.gstatic.com/s/roboto/v15/mErvLBYg_cXG3rLvUsKT_fesZW2xOQ-xsNqO47m55DA.woff2
http://fonts.gstatic.com/s/roboto/v15/-2n2p-_Y08sg57CNWQfKNvesZW2xOQ-xsNqO47m55DA.woff2
http://fonts.gstatic.com/s/roboto/v15/u0TOpm082MNkS5K0Q4rhqvesZW2xOQ-xsNqO47m55DA.woff2
http://fonts.gstatic.com/s/roboto/v15/NdF9MtnOpLzo-noMoG0miPesZW2xOQ-xsNqO47m55DA.woff2
http://fonts.gstatic.com/s/roboto/v15/Fcx7Wwv8OzT71A3E1XOAjvesZW2xOQ-xsNqO47m55DA.woff2
http://fonts.gstatic.com/s/roboto/v15/CWB0XYA8bzo0kSThX0UTuA.woff2
```

```bash
# python getfont.py Roboto latin 400 eot
http://fonts.gstatic.com/s/roboto/v15/5YB-ifwqHP20Yn46l_BDhA.eot
```

```bash
# python getfont.py
You should use:
        python getfont.py font-name [subset:latin|latin-ext|cyrillic] [styles:400|100|100italic|...] [file-type:all|woff|woff2|ttf|svg|eot]
e.g.
        python getfont.py Roboto latin 400
        python getfont.py Roboto latin,latin-ext 100,100italic


Possible font names may be, "Pt Sans",Roboto,Ubuntu,...
You can check further names at: https://www.google.com/fonts/
```
