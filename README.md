# Welcome to Dosham

This is a compilation of different Chechen, Chechen-Russian, Russian-Chechen dictionaries. The compilation contains approximately 68k words. 

The following is the list of dictionaries: 

- Matsiev A.G. Nokhchiin-orsiin dosham. **(Chechen-Russian)**
- Karasaev A.T., Matsiev A.G. Orsiin-nokhchiin dosham. **(Russian-Chechen)**
- Umarkhadzhiev S.M., Akhmatukaev A.A. Nokhchiin-orsiin, oirsiin-nokhchiin mathematician terminin dosham. **(Chechen-Russian, Russian-Chechen mathematical terms)**
- Abdurashidov E.D. Nokhchiin-o'rsiin, o'rsiin-nokhchiin yuridicheski terminin dosham. **(Chechen-Russian juridical terms)**
- Bersanov R.U. Nokhchiin-orsiin, oirsiin-nokhchiin adaman anatomin dosham. **(Chechen-Russian, Russian-Chechen anatomical terms)**
- Umarkhadzhiev S.M., Askhabov Kh.I., Badaeva A.S., Vagapov A.D., Izrailova E.S., Sultanov Z.A., Astemirov A.V. O'rsiin-nokhchiin, nokhchiin-o'rsiin computer lexikin dosham. **(Chechen-Russian, Russian-Chechen computer terms)**
- Baysultanov D.B. Nokhchiin-o'rsiin dosham ("A. Matsievn (1961 sh.) "Nokhchiin-o'rsiin dosham" yuk'a tsa yaakhanchu lexemekh hӀottiina yolu nokhchiin mettan discriptivny dosham").
- Ismailov A. Nokhchiin-o'rsiin, o'rsiin-nokhchiin dosham ("Dosh" knigi tӏera). **(Chechen-Russian, Russian-Chechen)**
- Aslakhanov S.A.M. O'rsiin-nokhchiin sportivni terminin a, deshniin tskhyanakkhetariin a dosham. **(Chechen-Russian sports terms)**
- Daukaev A.A. Geologist-mineralogist terminin oirsiin-nokhchiin dosham **(Chechen-Russian geological terms)**

# Structure

There are 2 files: 
- `original.json` - contains unicode encoded characters. Each dictionary separate array
- `unified.json` - contains unicoded translated characters. Single array. 


The JSON structure of a word in `unified.json` is as follows: 

```
 {
    "id": "12205",
    "word": "сибатдо̃цу, сибатдо̃цург",
    "word1": "сибатдоцу, сибатдоцург",
    "translate": "<i>прич. уст.</i> безли́кий.\r\n",
    "parent": "maciev_ce_ru"
  },
```

Where `word` or `word1` contains a word. The corresponding translation is in the `translate` property.

The `parent` property signifies the dictionary to which the word belongs. 

# Caveats

The `translate` field can contain HTML markup code. 