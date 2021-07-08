## Legend:

- \* (asterisk) \-> required to complete step
- [**input**] \-> default input field
- [**input-additional**] \-> default input field which is hidden by default with accompanying "+" button; once the "+" button is pressed, the input field shows up. An "X" button shows on the input field which allows for removal of that input field.
- [**label**] \-> default label for elements which come after the label
- [**btn**] \-> default button
- [**photo-select-/w-preview**] \-> input for selecting a photo with a preview
- [**radial-checkbox**] \-> custom input in a shape of a circle graph for selecting multiple items
- [**map-google**] \-> google map
- [**radio-box-/w-icon-&-text**] \-> custom radio in the shape of a box with an icon and text inside of it

##### Registracija kao **trgovac**:
```Route: /registracija```

- STEP 1
    - \*[**input**] Ime
    - \*[**input**] Prezime
    - \*[**input**] E-mail
    - \*[**input**] Šifra
    - \*[**input**] Potvrdi šifru
    - &nbsp; [**btn**] Kreiraj profil
    &nbsp;
- STEP 2
    - \*[**input**] Ulica 
    - \*[**input**] Dodatna adresa
    - \*[**input**] Grad
    - \*[**input**] Poštanski broj
    - &nbsp; [**btn**] Započni trgovinu
    &nbsp;
- STEP 3
    - \*[**input**] Naziv trgovine
    - \*[**input**] Dodatne informacije o trgovini
    - \*[**input**] Kontakt broj #1
    - &nbsp; [**input-additional**] Kontakt broj #2
    - &nbsp; [**radial-checkbox**] Radni dani
    - &nbsp; [**input**] Radno vrijeme
        - &nbsp; [**label**] OD
            - &nbsp; [**dropdown**] HH
            - &nbsp; [**dropdown**] MM
        - &nbsp; [**label**] DO
            - &nbsp; [**dropdown**] HH
            - &nbsp; [**dropdown**] MM
            &nbsp;
    - \*[**label**] Pronađite trgovinu na mapi za bolju vidljivost
        - \*[**input**] Adresa na mapi
        - \*[**map-google**] Lokacija na mapi (dodirnite mapu da odaberete lokaciju)
        &nbsp;
    - \*[**label**] Stajling i izgled e-trgovine
        - &nbsp; [**label**] Izgled trgovine
            - &nbsp; [**radio-box-/w-icon-&-text**] Tenda
            - &nbsp; [**radio-box-/w-icon-&-text**] Moderno
            - &nbsp; [**radio-box-/w-icon-&-text**] Elegantno
            - &nbsp; [**radio-box-/w-icon-&-text**] Prirodno
            - &nbsp; [**radio-box-/w-icon-&-text**] Ruralno
        - &nbsp; [**photo-select-/w-preview**] Logo trgovine
        - &nbsp; [**photo-select-/w-preview**] Naslovna slika trgovine
        &nbsp;
    - &nbsp; [**btn**] Otvori trgovinu!
    &nbsp;