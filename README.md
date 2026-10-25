<h1 align="center">🧮 Smart Calculator</h1>

<p align="center"><em>Une calculatrice en ligne de commande qui retient tes variables et signale les erreurs de syntaxe.</em></p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3" />
  <img src="https://img.shields.io/badge/d%C3%A9pendances-aucune-success?style=for-the-badge" alt="Aucune dépendance" />
  <img src="https://img.shields.io/badge/projet%20d%27apprentissage-ff69b4?style=for-the-badge" alt="Projet d'apprentissage" />
</p>

---

## ✨ Pourquoi tu vas l'adorer

- **Les quatre opérations** `+ - * /`, avec les priorités habituelles de Python.
- **Des variables** : `a = 10`, puis réutilise `a` dans tes calculs.
- **Des messages d'erreur clairs** : identifiant invalide, variable inconnue, expression invalide.
- **Deux commandes** : `/help` et `/exit`.

## 🎮 Utilisation

| Saisie | Résultat |
|---|---|
| `3 + 4 * 2` | `11` |
| `a = 10` | Rien affiché, la valeur est mémorisée |
| `a / 4` | `2.5` |
| `/help` | Rappel du rôle du programme |
| `/exit` | Quitte le programme |

## 🚀 Lancer

```bash
python3 Code_Python_Smart_Calculator
```

## 🕹️ Exemple

Les lignes saisies sont suivies du résultat du programme :

```text
3 + 4 * 2
11
a = 10
a / 4
2.5
/help
The program calculates the sum and subs of numbers
/exit
Bye!
```

## 🧠 Sous le capot

- Une fois nettoyée, l'expression est évaluée avec `eval()`.
- Les variables vivent dans un dictionnaire `num_dict` et sont substituées avant le calcul.
- Les exceptions `SyntaxError` et `NameError` sont interceptées pour afficher un message propre.
- ⚠️ `eval()` exécute n'importe quel code Python : parfait pour apprendre, à bannir d'un vrai projet.

## 🔭 Pistes d'évolution

- Accepter les expressions dans les affectations : `b = a * 2` est pour l'instant mal géré.
- Remplacer `eval()` par un vrai analyseur d'expressions (par exemple l'algorithme *shunting-yard*).

---

<p align="center"><sub>Fait avec ❤️ et Python par DSKarim</sub></p>
