# Le Machine Learning, autrement

**Apprendre, Choisir, Construire en 7 jours**

Le repo officiel du livre. Tu y trouveras tous les datasets, notebooks et exemples de code utilisés au fil des chapitres.

---

## C'est quoi ce livre ?

Un livre de Machine Learning écrit par un ingénieur logiciel pour les **curieux ambitieux** : étudiants, professionnels en reconversion, managers, entrepreneurs, développeurs qui n'ont jamais touché au ML.

Pas un cours académique exhaustif. Pas une promesse de devenir expert en une semaine. Juste une autre façon d'expliquer le Machine Learning : avec des analogies, des problèmes concrets, du code qui tourne, et zéro jargon non défini.

> *Après ce livre, tu comprendras de quoi les gens parlent quand ils disent IA, ML, LLM, agent. Tu sauras ce qui existe, quand l'utiliser, et tu auras les bases pour aller plus loin si tu veux.*

---

## À qui ce livre s'adresse

- **Étudiants** (Licence/Master, toutes filières) qui veulent comprendre l'IA en 2026
- **Professionnels en reconversion** vers la data (marketing, finance, RH, etc.)
- **Managers et décideurs** qui veulent piloter des équipes data sans se faire mener en bateau
- **Entrepreneurs** qui veulent savoir si l'IA peut servir leur projet
- **Développeurs juniors** qui n'ont jamais touché au ML

### Prérequis

- Maths de lycée (moyenne, pourcentage, lire un graphique)
- Logique de base (si... alors...)
- Python très basique (ou prêt à apprendre via le Chapitre 0)
- **Aucun** prérequis en stats avancées, algèbre linéaire, ou deep learning frameworks

---

## Statut du livre

Le livre est en cours de rédaction. Version bêta prévue **début 2027**.

### Avancement

| Partie | Chapitre | Statut |
|--------|----------|--------|
| Fondations | 0 - Python en 30 minutes | 🔲 |
| Fondations | 1 - Ce qu'est vraiment le Machine Learning | ✅ |
| Fondations | 2 - Apprivoiser les données | ✅ |
| Fondations | 3 - Évaluer un modèle (sans se mentir) | ✅ |
| Penser par problème | 4 - Prédire un nombre : la régression | ✅ |
| Penser par problème | 5 - Classer des éléments : la classification | ✅ |
| Penser par problème | 6 - Sans labels : clustering & réduction | ✅ |
| Penser par problème | 7 - Détecter ce qui sort de l'ordinaire | ✅ |
| Penser par problème | 8 - Apprendre par renforcement | ✅ |
| Modèles fondamentaux | 9 - Comprendre les LLMs (sans bullshit) | ✅ |
| Modèles fondamentaux | 10 - Prompt Engineering comme compétence | ✅ |
| Modèles fondamentaux | 11 - Fine-tuning : quand et pourquoi | ✅ |
| Modèles fondamentaux | 12 - RAG : connecter un LLM à tes données | ✅ |
| Construire des systèmes | 13 - Les agents IA | 🔲 |
| Construire des systèmes | 14 - ML classique + LLM : le meilleur des deux | 🔲 |
| Construire des systèmes | 15 - Mettre en production (MLOps simplifié) | 🔲 |
| Écosystème | 16 - Qui fait quoi dans la data ? | 🔲 |
| Écosystème | 17 - Choisir ses outils | 🔲 |
| Écosystème | 18 - Éthique et limites | 🔲 |

---

## Structure du repo

```
ml-autrement/
├── data/                    Datasets utilisés dans les chapitres
│   ├── 02/                  Chapitre 2 - Apprivoiser les données
│   │   └── smartphones.csv
│   └── ...
│
├── notebooks/               Notebooks Jupyter exécutables (à venir)
│   └── ...
│
└── README.md
```

Convention de nommage : `XX-mot-cle` où `XX` est le numéro de chapitre. Le notebook 04 correspond au Chapitre 4 du livre.

---

## Comment utiliser ce repo

Les datasets sont accessibles directement via leur URL brute. Par exemple, pour charger le dataset des smartphones (Chapitre 2) :

```python
import pandas as pd
url = "https://raw.githubusercontent.com/denisakp/ml-autrement/main/data/02/smartphones.csv"
df = pd.read_csv(url)
```

Pas besoin de cloner le repo, pas besoin de compte GitHub. Tout est public, libre, accessible.

---

## Reproduire les exemples du livre

Pour reproduire tous les exemples du livre, tu auras besoin de Python 3.10+ et de quelques librairies classiques :

```bash
pip install pandas scikit-learn matplotlib numpy
```

Pour les chapitres sur les LLMs et le RAG (à venir), des librairies supplémentaires seront nécessaires. Elles seront listées au fil des chapitres.

---

## Licence

Le contenu de ce repo (datasets, notebooks, code) est sous licence **Creative Commons CC BY-NC 4.0**.

Tu peux librement :
- ✅ Le partager et l'adapter pour un usage personnel ou éducatif
- ✅ Le citer dans tes propres travaux

Mais tu ne peux pas :
- ❌ L'utiliser pour des fins commerciales sans accord préalable

Pour toute demande d'usage commercial, contacte l'auteur.

---

## L'auteur

**Denis AKPAGNONITE** : ingénieur logiciel spécialisé en architectures et systèmes distribuées. J'enseigne la programation distribuée et répartie, le Cloud, le BigData, et la modélisation SIG.

Ce livre est l'aboutissement de plusieurs années à essayer d'expliquer le Machine Learning autrement que comme on me l'avait appris : avec mes mots, mes analogies, mon vécu.

---

## Contribuer

Le livre est en cours de rédaction. Si tu trouves une erreur, une coquille, un exemple qui ne tourne pas, ou si tu as une suggestion : **ouvre une issue sur ce repo**. Toute remarque constructive est bienvenue.

Si tu veux être informé de la sortie de la version bêta, mets une ⭐ sur le repo. C'est le moyen le plus simple de suivre l'avancement.
