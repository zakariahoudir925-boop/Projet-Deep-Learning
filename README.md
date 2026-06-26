# Projet Deep Learning - EMSI Casablanca

**Auteur :** Zakaria Houdir  
**Filière :** 4IADO G4  
**Encadrant :** Mme HIDIL Zineb  
**Module :** Deep Learning  
**Année :** 2025–2026

---

## 📋 Description du Projet

Ce projet constitue l'évaluation finale du module de Deep Learning. Il démontre la compréhension théorique et la maîtrise pratique de l'implémentation sous PyTorch de trois grandes familles d'architectures neuronales :

1. **Perceptron Multicouche (MLP)** sur données tabulaires (Breast Cancer Wisconsin)
2. **Réseaux de Neurones Convolutifs (CNN)** sur données images (Fashion-MNIST)
3. **Modèles Séquentiels (RNN, LSTM, GRU)** sur données textuelles (Analyse de sentiment)

---

## 📁 Contenu du Dépôt

- **`Projet_Deep_Learning_Zakaria_Houdir_FINAL.ipynb`** : Notebook Jupyter complet avec :
  - Configuration et reproductibilité (seeds, device)
  - Implémentation MLP avec interprétabilité (Integrated Gradients)
  - Implémentation CNN avec feature maps et évaluation sur le jeu de test
  - Implémentation comparative RNN/LSTM/GRU
  - Visualisations et analyses détaillées

- **`Rapport_Projet_Deep_Learning_Zakaria_Houdir.pdf`** : Rapport académique (46 pages) incluant :
  - Table des matières automatique
  - Liste des figures et tableaux
  - Liste des abréviations
  - Cadre théorique pour chaque architecture
  - Résultats expérimentaux complets
  - Discussion transversale et analyse critique
  - Section Impact sociétal / Éthique
  - Références bibliographiques (format IEEE)

---

## 🎯 Résultats Clés

### Partie I : MLP (Breast Cancer)
- **Accuracy (Test) :** 94,19 %
- **Précision :** 98,04 %
- **Rappel :** 92,59 %
- **F1-Score :** 95,24 %

### Partie II : CNN (Fashion-MNIST)
- **Accuracy (Test) :** 90,21 %
- **Précision macro :** 90,20 %
- **Rappel macro :** 90,21 %
- **F1-Score macro :** 90,11 %

### Partie III : RNN/LSTM/GRU
- Implémentation comparative sur données séquentielles synthétiques
- Analyse des portes (LSTM/GRU) et gradient clipping

---

## 🛠️ Technologies Utilisées

- **PyTorch** : Framework deep learning
- **Python 3.11** : Langage de programmation
- **Scikit-learn** : Métriques et prétraitement
- **Matplotlib & Seaborn** : Visualisations
- **Captum** : Interprétabilité (Integrated Gradients)

---

## ✅ Conformité

Le projet suit strictement le **Guide de Référence pour l'Entraînement de Modèles de Deep Learning** (EMSI) :
- ✓ Structure attendue (10 chapitres)
- ✓ Évaluation sur jeu de test (pas de data leakage)
- ✓ Métriques multiples (pas accuracy seule)
- ✓ Interprétabilité (≥ 1 méthode par architecture)
- ✓ Reproductibilité (seeds, gradients clipping, model.eval())
- ✓ Section Éthique et impact sociétal
- ✓ Références bibliographiques académiques

---

## 🚀 Comment Utiliser

### Exécuter le notebook
```bash
jupyter notebook Projet_Deep_Learning_Zakaria_Houdir_FINAL.ipynb
```

### Consulter le rapport
Ouvrez directement le fichier PDF avec votre lecteur PDF préféré.

---

## 📚 Références

- LeCun, Y., Bengio, Y., & Hinton, G. (2015). Deep learning. Nature, 521(7553), 436–444.
- Hochreiter, S., & Schmidhuber, J. (1997). Long short-term memory. Neural Computation, 9(8), 1735–1780.
- Kingma, D. P., & Ba, J. (2014). Adam: A method for stochastic optimization. arXiv preprint arXiv:1412.6980.

---

## 📧 Contact

Pour toute question, contactez l'auteur ou l'encadrant du module.

---

**Dernière mise à jour :** 26 juin 2026
