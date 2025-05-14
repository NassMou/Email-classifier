# Email-classifier
Classifier des e-mails comme « spam » ou « non-spam »

# Spam Classifier with Neural Networks

Un projet de classification d'e-mails spam / non-spam utilisant un réseau de neurones avec TensorFlow et un dataset réel de messages SMS.

---

##Objectif

Ce projet utilise un modèle de deep learning pour détecter automatiquement les spams dans des messages textes, en s'appuyant sur le jeu de données SMS Spam Collection. Il illustre la capacité des réseaux de neurones simples à résoudre des problèmes concrets de NLP.

---

- **Source :** [Kaggle - SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- 5 574 messages textuels
- Étiquettes : `ham` (non spam) ou `spam`

---

##Tech Stack

- Python 3.x
- Pandas / scikit-learn
- TensorFlow / Keras
- Tokenizer + Embedding Layer
- Architecture dense avec GlobalAveragePooling

---

##Comment exécuter le projet

1. Télécharger `spam.csv` depuis [Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
2. Placer le fichier dans le dossier du script
3. Exécuter :

```bash
python spam_classifier.py
