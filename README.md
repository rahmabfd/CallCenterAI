
# CallCenterAI - Mini-Projet MLOps

## Description
Système de classification intelligente des tickets clients avec MLOps, utilisant TF-IDF+SVM et un modèle Transformer (distilbert-base-multilingual-cased).

## Installation
- Clone le repo : `git clone https://github.com/tonusername/callCenterAI.git`
- Installe les dépendances : `pip install -r requirements.txt`

## Lancement
(À compléter avec instructions pour docker-compose, MLflow, etc.)

## Architecture
- **Agent IA**: Orchestre les prédictions, choisit entre TF-IDF et Transformer.
- **Services**: FastAPI pour TF-IDF+SVM, Transformer, et agent.
- **MLOps**: MLflow, DVC, GitHub Actions, Prometheus, Grafana.
(Diagramme à ajouter plus tard.)

## Environnement
- Développé sur Google Colab avec GPU T4.
- Python 3.10+, torch==2.8.0+cu126, dépendances dans `requirements.txt`.
"""
with open('/content/drive/MyDrive/Colab Notebooks/callCenterAI/README.md', 'w') as f:
    f.write(readme_content)
