# PronotePY MonLycee

Ceci est une version patchée de PronotePY qui permet de se connecter avec le nouveau site de MonLycee.

Le partial pour l'ile de france a été modifié puisque cet ENT utilise désormais le nouveau site de MonLycee.

**Aucune autre modification n'a été faite sur PronotePy**

## Utilisation simple

Il suffit de télécharger le fichier `pronotepy_monlycee.py`, de le mettre dans le dossier de votre projet et d'importer le code:

```python
import pronotepy
from pronotepy_monlycee import ile_de_france

client = pronotepy.Client("URL DE L'INSTANCE PRONOTE",
                          username="NOM D'UTILISATEUR DE L'ENT",
                          password="MOT DE PASSE DE L'ENT",
                          ent=ile_de_france)
```


## Utilisation avec pip

Il suffit d'installer le package via `pip install -U git+https://github.com/Alg0v/pronotepy_monlycee`

### Île de France
```python
import pronotepy
from pronotepy.ent import ile_de_france

client = pronotepy.Client("URL DE L'INSTANCE PRONOTE",
                          username="NOM D'UTILISATEUR DE L'ENT",
                          password="MOT DE PASSE DE L'ENT",
                          ent=ile_de_france)
```
