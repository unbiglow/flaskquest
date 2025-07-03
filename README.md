Premièrement il faut crééer la BASE DE données

Donc dans le terminal : 

Ecrire python

Ecrivé c'est ligne de code puis quand le print s'affiche faite exit()

```python
from app import app, db
with app.app_context():
    db.create_all()
    print("Toutes les tables ont été créées avec succès !")
```

Après cetté étape vous pouvez lancée l'application

python app.py
