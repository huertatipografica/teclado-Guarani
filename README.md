[English](README-en.md)

# Teclado Guaraní
Distribución de teclado Guaraní-Español-Portugués

![Keyboard layout](img/gua-spa.png)

El objetivo de esta nueva propuesta de distribución de teclado es brindar accesibilidad a los signos necesarios para tipear guaraní y español.
Tomando como base la distribución Spanish - ISO y modificándola lo menos posible hemos incorporado:

`y` + `´`

`e` `i` `u` `y` `g` + `~`

`saltillo` ⁄ `pusó`

`Gtilde` / `gtilde` -> no tienen unicode, pero se pueden tipear usando  el acento de combinación.

`Saltillo` / `saltillo` -> tienen unicode. Es una letra, por lo que debería ser de tipeado directo y estar dentro de la órbita de las letras. Tiene low- y uppercap.

Con esta distribución queremos ofrecer una solución a la escritura guaraní independientemente de la fuente tipográfica que se esté utilizando (cualquier fuente que contenga combining accents y saltillo debería funcionar).

Los acentos deben ser tipeados antes de la letra que modifican.

Es importante considerar a un usuario bilingüe porque el guaraní es un idioma que comparte territorio con otros idiomas, principalmente español y portugués.

En caso de hacer cambios, para actualizar la versión de windows correr en la terminal:

```bash
python mac2winKeyboard.py Guarani.keylayout
```

**Instrucciones para instalar una nueva distribución del teclado en Windows:**

https://support.microsoft.com/es-ar/help/258824/how-to-change-your-keyboard-layout



**Instrucciones para instalar una nueva distribución del teclado en Mac:**

Hacer doble click en el archivo Guarani.dmg y arrojar el archivo .keylayout en la carpeta que indica Drag here to install (~Library / Keyboard Layouts)

Abrir el panel de preferencias de teclado

Agregar esta distribución a las opciones de teclado

Más info: http://www.languagegeek.com/keyboard_general/mac_installation1.html



El programa utilizado para generar esta nueva distribución es Ukelele

- http://scripts.sil.org/cms/scripts/page.php?item_id=ukelele
- https://support.microsoft.com/es-ar/help/258824/how-to-change-your-keyboard-layout
- https://glyphsapp.com/tutorials/mark-attachment
- https://es.wikipedia.org/wiki/Distribuci%C3%B3n_del_teclado#Teclado_est.C3.A1ndar_multiidiomas_de_Canad.C3.A1
- https://github.com/adobe-type-tools/keyboard-layouts