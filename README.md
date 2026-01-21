#  ML Prediction API – FastAPI Project

## Description
Ce projet est une application **Machine Learning** déployée avec **FastAPI**.  
Il permet de faire des **prédictions** à partir d’un modèle entraîné (RandomForestRegressor) et propose une **interface web** stylisée (HTML + CSS) avec images et couleurs.

L’objectif est de :
- Charger un modèle ML entraîné
- Exposer une API avec FastAPI
- Afficher une interface web conviviale avec Jinja2

---

##  Technologies utilisées

- **Python 3.10+**
- **FastAPI**
- **Uvicorn**
- **Scikit-learn**
- **Jinja2 (templates HTML)**
- **HTML / CSS**

---

## Structure du projet

```
api/
│── main.py
│── model.pkl
│── templates/
│   └── index.html
│── static/
│   ├── car.png
│
│── README.md
```

---

## Lancer le projet

### Installer les dépendances

```bash
pip install fastapi uvicorn jinja2 scikit-learn
```

---

###  Démarrer le serveur

```bash
uvicorn main:app --reload
```

---

###  Accéder à l’application

- 🌐 Interface Web :
```
http://127.0.0.1:8000
```

-  Documentation API (Swagger) :
```
http://127.0.0.1:8000/docs
```

---

##  Interface utilisateur

- Thème **bleu moderne**
- Images intégrées depuis le dossier `static`
- Formulaire de saisie pour les prédictions
- Résultat affiché dynamiquement

---

##  Remarques importantes

- Les warnings `InconsistentVersionWarning` de scikit-learn ne bloquent pas l’exécution
- Assurez-vous que les dossiers `templates` et `static` sont au même niveau que `main.py`

---

##  Améliorations possibles

- Ajout de graphiques (matplotlib / plotly)
- Authentification utilisateur
- Déploiement sur Render / Railway / Docker
- Amélioration du design (Bootstrap / Tailwind)

---


---

## 📄 Licence

Ce projet est à usage éducatif.

"# Car-Price-Prediction" 
"# Car-Price-Prediction" 
