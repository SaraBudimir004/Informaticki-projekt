# Predviđanje cijena nekretnina pomoću strojnog učenja

## Opis projekta

Ovaj projekt bavi se predviđanjem cijena nekretnina korištenjem metoda strojnog učenja. 
Cilj je analizirati utjecaj različitih socio-ekonomskih i geografskih čimbenika na cijenu nekretnina te izgraditi modele koji mogu predvidjeti njihovu vrijednost.

Korišten je Boston Housing Dataset koji sadrži podatke o karakteristikama urbanih područja Bostona.

## Cilj projekta

- Analiza podataka i identifikacija ključnih varijabli
- Izrada eksplorativne analize podataka (EDA)
- Izgradnja modela strojnog učenja
- Usporedba performansi modela

## Dataset

Koristi se Boston Housing Dataset s 13 ulaznih varijabli i ciljnom varijablom MEDV (srednja vrijednost nekretnina).

Glavne varijable uključuju:
- CRIM (stopa kriminala)
- RM (broj soba)
- LSTAT (udio stanovništva nižeg socio-ekonomskog statusa)
- PTRATIO (omjer učenika i nastavnika)
- TAX (porezna stopa)

## Evaluacija

Modeli su uspoređeni pomoću metrika:
- MAE
- RMSE
- R²

## Rezultati

Random Forest model ostvaruje bolje rezultate u odnosu na Ridge regresiju, s manjom pogreškom i većim R² koeficijentom.

## Zaključak

Rezultati pokazuju da nelinearni modeli bolje opisuju odnose u podacima i daju točnije predikcije cijena nekretnina.
