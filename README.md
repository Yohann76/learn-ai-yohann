# Learn AI Yohann

run wiki with docker:

```
docker compose up
```

Available in http://localhost:8000

## Available with Github Page (soon)

```
https://yohann76.github.io/learn-ai-yohann/
```

workflow ci.yml -> mkdocs gh-deploy (generate and deploy static files to gh-pages branch when push to main branch) 
Configure available page -> Github Setting -> Pages -> Source (deploy from a branch)
Branch gh-pages branh + root

## Contribute

1. Clone project
2. Create your branch
3. Add/commit your change
4. push and create merge request

## Ressources:

- [Roadmap AI Engineer](https://roadmap.sh/ai-engineer)

## Program

Module 1 : Fondamentaux (Python & Maths)

```
Python pour la Data Science (listes, dicts, fonctions)
Mathématiques essentielles : Algèbre linéaire, Probabilités, Statistiques
Environnement de dev : Jupyter, VS Code, Conda/Venv
Git pour les Data Scientists
```

Module 2 : Manipulation et Analyse de Données

```
NumPy : Calcul matriciel et vectoriel
Pandas : Manipulation de DataFrames, nettoyage de données
Matplotlib / Seaborn : Visualisation de données (EDA)
SQL pour l'IA : Requêtes de base et jointures
```

Module 3 : Machine Learning Classique

```
Apprentissage Supervisé : Régression, Classification (Arbres, SVM, KNN)
Apprentissage Non-supervisé : Clustering (K-Means), PCA
Scikit-learn : Pipelines, Entraînement, Validation
Métriques d'évaluation : Accuracy, Precision/Recall, F1-score, ROC/AUC
```

Module 4 : Deep Learning & Réseaux de Neurones

```
Introduction aux réseaux de neurones (Perceptron, MLP)
Frameworks : PyTorch ou TensorFlow/Keras
Réseaux de neurones convolutifs (CNN) pour la vision
Réseaux récurrents (RNN/LSTM) pour les séquences
Optimiseurs (Adam, SGD) et Fonctions de perte
```

Module 5 : NLP et LLMs (Large Language Models)

```
Traitement du langage naturel (Tokenization, Embeddings)
Architecture Transformer (Attention is all you need)
Utilisation des LLMs : OpenAI API, Anthropic, Mistral
Hugging Face : Modèles open-source et Hub
```

Module 6 : Prompt Engineering

```
Principes de base : Zero-shot, Few-shot prompting
Techniques avancées : Chain of Thought (CoT), ReAct
Structuration des outputs (JSON mode)
Sécurité et limitations (Hallucinations, Biais)
```

Module 7 : RAG (Retrieval Augmented Generation)

```
Principe du RAG : Contexte + LLM
Bases de données vectorielles (Pinecone, ChromaDB, Weaviate)
Embeddings : Création et recherche sémantique
Frameworks d'orchestration : LangChain, LlamaIndex
```

Module 8 : Agents et Orchestration

```
Concepts d'Agents AI (Autonomie, Outils)
Function Calling / Tool use
Frameworks d'agents : LangGraph, AutoGen
Mémoire et persistance des conversations
```

Module 9 : Fine-tuning et Entraînement

```
Quand faire du Fine-tuning vs RAG ?
PEFT (Parameter-Efficient Fine-Tuning) : LoRA, QLoRA
Préparation des datasets d'instruction
Entraînement sur GPU (Google Colab, RunPod)
```

Module 10 : Déploiement et MLOps

```
Création d'API pour modèles (FastAPI, Flask)
Conteneurisation (Docker pour l'IA)
Serving de modèles (vLLM, TGI)
Monitoring et Observabilité (LangSmith, Weights & Biases)
```

Module 11 : Projets Pratiques

```
Créer un Chatbot RAG sur vos propres documents
Construire un Agent capable de faire des recherches web
Développer une API de classification de texte
Fine-tuner un petit modèle (ex: Llama 3 8B) sur un style spécifique
```

Module 12 : Aller plus loin ("Next")

```
Multimodalité (Texte + Image + Audio)
IA Générative d'images (Stable Diffusion, Midjourney)
Éthique et Régulation de l'IA
Veille technologique (ArXiv, Twitter/X, Newsletters)
```
