[Español](README.md)

# Guaraní keyboard layout
Guaraní-Spanish-Portuguese keyboard layout

![Keyboard layout](img/gua-spa.png)

The objective of this new proposal for keyboard distribution is to allow accessibility to the necessary signs to type guaraní and spanish.
Starting with the Spanish - ISO distribution and introducing the least amount of modifications possible we’ve introduced:

`y` + `´`

`e` `i` `u` `y` `g` + `~`

`saltillo` ⁄ `pusó`

`Gtilde` / `gtilde` -> They don’t have Unicode, but they can be typed using the combination accent.

`Saltillo` / `saltillo` -> They have Unicode. They’re a letters, so they can be typed directly and they’re inside the orbit of letters. They have lowercase and uppercase.

With this distribution we want to offer a solution for guaraní writing, independently of the font being used (any font that has combining accents and saltillo should work).

The accents are typed before the letter they modify.

It’s important to consider bilingual users because guaraní is a language that shares territory with other languages, mainly spanish and portuguese.

For making changes in the windows version of the keyboard run in command line:

```bash
python mac2winKeyboard.py Guarani.keylayout
```

How to install a new keyboard layout in Windows:

Https://support.microsoft.com/en-us/help/258824/how-to-change-your-keyboard-layout


How to intall a new keyboard layout on Mac:

Double-click the Guarani.dmg file and drop the .keylayout file into the folder named "Drag here to install" (~/Library/Keyboard Layouts)

Open the keyboard preferences.

Add this distribution to the keyboard options from the "Others" section on the left.

More info: http://www.languagegeek.com/keyboard_general/mac_installation1.html


This distribution was created using Ukelele

- http://scripts.sil.org/cms/scripts/page.php?item_id=ukelele
- https://support.microsoft.com/es-ar/help/258824/how-to-change-your-keyboard-layout
- https://glyphsapp.com/tutorials/mark-attachment
- https://es.wikipedia.org/wiki/Distribuci%C3%B3n_del_teclado#Teclado_est.C3.A1ndar_multiidiomas_de_Canad.C3.A1
- https://github.com/adobe-type-tools/keyboard-layouts