# Pràctica Kaggle APC UAB 2021-22
### Nom: Christian Ferré Delgado
### NIU: 1565129
### DATASET: covid_and_healthy_spectra.csv
### URL: https://www.kaggle.com/sfran96/raman-spectroscopy-for-detecting-covid19?select=tube_spectra.csv

## Resum
El dataset utilitza dades del resultat de realitzar una espectroscòpia de Raman a un pacient per diagnosticar si té covid o no.
Tenim 309 dades amb 901 atributs. Tots els atributs són númerics excepte l'atribut 'diagnostic' que és categòric. La base de dades és balancejada.
### Objectius
El meu objectiu és ser capaç de fer un diagnòstic d'un pacient a partir de les dades proporcionades per l'espectroscòpia Raman.

### Preprocessat
Abans de treballar amb la base de dades, hem tractat els nulls, examinat els tipus d'atributs, estandarditzat les dades i estudiat la correlació.
## Model
- Decision Tree amb cerca d'hiperparàmetres
- Random Forest
- Regressor logístic
## Conclusions
El millor model que he aconseguint a és el regressor logístic amb una classificació quasi perfecta.

## Idees per treballar en un futur 
Crec que amb més dades i un model amb una cerca d'hiperparàmetres més extensa pot arribar a ser molt fiable respecte a les prediccions.
Per tant, podem arribar a obtenir un model que en segons pugui donar-te un resultat quasi perfecte i ajudar a diagnosticar molts casos 
de positius en covid.

