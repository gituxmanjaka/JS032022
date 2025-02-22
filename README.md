# JS032022

## How to contribute

- Forkena ilay repostiory ito
- Clonena avy eo ilay repository anao Ilay fork an'ito
- Ajoutenao ny remote *upstream* `git remote add upstream https://github.com/OpenMG/JS032022.git`
- Mamonona branche `git checkout -b ma_super_branch`
- Copiena ny dossier na fichier misy ny code-nao na mamorona fichier vaovao
- Rehefa vita ny fanovana ataonao dia manao `git add .`
- Avy eo commite-nao ny zavatra nataono `git commit -m "Update function"`
- Maka ny mise a jour farany ianao:
  - avy ao aminao `git pull origin master`
  - avy any aminy topony repository `git pull upstream master`
- Farany, alefanao ao aminao ny modification rehetra nataonao `git push origin ma_super_branch`
- Makany aminy navigateur ianao avy eo manao *Merge request*

## Description

Techzara formations JS Mars 2022.  
Ireo excercice rehetra mandritra ny formations no hitanareo ato.

> Ajouteo eo amin'ny contributors ny anaranao :) 
## Contributors
- [Chrys rakotonimanana](https://github.com/chrys-elrak)
- [Rasolondraibe Tolotra Mandresy](https://github.com/TolotraMandresy)
- [Toky Mahefarison](https://github.com/gituxmanjaka)

## Excercices


1. Manala doublons anaty tableau ana nombre  

```
    > in [23, 0, -23, 1, 5, 0]  
    > out [23, 0, -23, 1, 5]  
```

2. Mandahatra element anaty tableau ana nombre par ordre croissant (raha misy doublons dia igniorena) avy eo decroissant

```
    in [23, 0, -23, 1, 5, 0]  
    out: [-23, 0, 1, 5, 23] (croissant)
    out: [23, 5, 1, 0, -23] (decroissant)
```

3. Total ny nombre negative sy positive anaty tableau ana nombre
```
    in: [12, -3, -4, 0, 1]
    out:
        * negatives: -7
        * positives: 13
```

4. Nombre miverina in-betsaka indrindra anaty tableau (raha misy mitovy dia aseo daholo)

```
    in: [23, 23, 23, 3, 4, 5, 5, 5, 1, 0, 3]
    out: 23, 5
```

5. Combinaison ana nombre lehibe indrindra anaty tableau (positive daholo ny nombre anaty tableau)

```
    in: [2, 2, 0, 5]
    out: 5220
    ****
    in: [1, 3, 6]
    out: 631
```
