# 🧠 Natural Language Processing — Tasks & Practicals

> Travaux pratiques et implémentations réalisés dans le cadre du module 
> **Natural Language Processing (NLP)** durant ma formation en Data Engineering .

---

## 📚 Contenu du Repository

### TP1 — 
| Fichier | Description |
|---------|-------------|
| `TP1__spaCy&NLTKbase.ipynb` | Utilisations de base des bibliothèques spaCy and NLTK |

### TP2 — Distance d'Édition & Autocorrection Orthographique
| Fichier | Description |
|---------|-------------|
| `TP2_EDM_Autocorrection.ipynb` | Implémentation de la distance d'édition minimum (MED), backtrace, et correcteur orthographique basé sur le modèle de langage unigramme et les coûts d'adjacence clavier QWERTY |

---

## 🛠️ Concepts & Techniques Abordés

- **Distance d'édition minimum (MED)** — algorithme de programmation dynamique
- **Backtrace** — reconstruction du chemin optimal
- **Modèle de langage unigramme** — calcul de P(c) sur un corpus
- **Correcteur orthographique** — basé sur le théorème de Bayes `argmax P(c) × P(w|c)`
- **Coûts d'adjacence QWERTY** — version intelligente de la substitution
- **Candidats d'édition** — edits0, edits1, edits2

---

## 🧰 Technologies Utilisées

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Colab](https://img.shields.io/badge/Google-Colab-orange)
![NLP](https://img.shields.io/badge/NLP-Natural%20Language%20Processing-green)

---

## 📂 Structure
```
NLP-Tasks/
│
├── TP2_EDM_Autocorrection.ipynb
├── qwerty_graph.txt
├── big.txt
└── README.md
```

---

## 👩‍💻 Auteur

**Yousra Khallou**  
Formation en data engineering
[![GitHub](https://img.shields.io/badge/GitHub-Yousra--khallou-black)](https://github.com/Yousra-khallou)
