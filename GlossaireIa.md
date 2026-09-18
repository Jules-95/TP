# Glossaire sur l'intelligence artificielle mais pas que... 

## Glossaire des termes et des sigles sur l'ia par ordre alphabétique

---

### Agent IA : 
Système d'intelligence artificielle capable de poursuivre un objectif de façon autonome en enchainant lui-même plusieurs étapes en agissant sur son environnement.
* Un LLM seul reçoit un prompt et renvoie du texte
* Un agent utilise un LLM comme "cerveau" pour décider quoi faire puis passer à l'action. Un agent raisonne puis agit. 


### Algorithme : 
Un algorithme est une suite finie et ordonnée d'instructions qui, à partir de données en entrée, permet d'obtenir un résultat en un nombre fini d'étapes. 
* Fini : Il se termine (pas à l'infini)
* Ordonné : Les étapes s'enchainent dans une séquence précise
* Non ambigu : Toute étape est clairement définie 
Un algorithme est indépendant du langage. 

### Biais : 
Distorsion systématique dans les résultats d'un modèle, souvent héritée de données d'entraînement déséquilibrées. Peut mener à des sorties injustes ou discriminatoires.


### Big Data : 
Ensembles de données si volumineux et complexes qu'ils dépassent les outils classiques. Caractérisé par les « 3V » : Volume, Vélocité, Variété.

### ChatBot : 
Programme conversationnel qui interagit en langage naturel. Les chatbots modernes sont souvent propulsés par des LLM.

### Dataset (jeu de données) : 
Ensemble structuré de données utilisé pour entraîner ou évaluer un modèle. Sa qualité et sa quantité conditionnent directement les performances du modèle.

### Deep Learning :
 Sous-domaine du Machine Learning utilisant des réseaux de neurones à nombreuses couches (« profonds »). C'est ce qui a rendu possibles les IA modernes (vision, langage…).

### Données : 
Informations brutes (texte, chiffres, images, sons…) qui servent à entraîner et à alimenter une IA. Sans données, pas d'apprentissage.

### Embedding : 
Représentation d'une donnée (mot, phrase, image) sous forme de vecteur de nombres qui capture son sens. Deux éléments proches en sens ont des embeddings proches.
Base de la recherche sémantique et du RAG.

### European AI Act : 
Première grande réglementation de l'Union européenne encadrant l'IA. Elle classe les systèmes par niveau de risque (inacceptable, élevé, limité, minimal) et impose des obligations correspondantes. Application progressive.

### GPT (Generative Pre-trained Transformer) : 
Famille de LLM génératifs développés par OpenAI, fondés sur l'architecture Transformer. « Pre-trained » = pré-entraîné sur du texte, « Generative » = génère du contenu.

### Hallucination : 
Quand un modèle produit une information fausse mais plausible, énoncée avec assurance.

### IA Adaptative :
IA qui ajuste son comportement au fil du temps, en fonction de nouvelles données ou de retours reçus.

### IA Générale :
IA hypothétique dotée d'une intelligence de niveau humain, capable de s'attaquer à n'importe quelle tâche. N'existe pas encore aujourd'hui.

### IA Générative :
IA capable de créer du contenu nouveau (texte, image, audio, code) plutôt que de simplement classer ou prédire. Ex. : ChatGPT, générateurs d'images.

### LLM :
Modèle entraîné sur d'énormes quantités de texte pour comprendre et générer du langage. Ex. : GPT, Llama, Qwen.

### Machine Learning :
Domaine de l'IA où un système apprend des motifs à partir de données au lieu d'être programmé explicitement pour chaque cas.

### Modèle :
Objet mathématique issu de l'entraînement : il prend une entrée et produit une sortie. C'est le « cerveau » résultant de l'apprentissage sur les données.

### Modelfile :
Fichier de configuration d'Ollama décrivant comment construire ou personnaliser un modèle : modèle de base, paramètres, system prompt… (logique proche d'un Dockerfile).

### NLP :
Branche de l'IA dédiée à la compréhension et à la génération du langage humain par une machine.

### Ollama :
Outil open source permettant de faire tourner des LLM en local sur sa propre machine, via de simples commandes. Gère le téléchargement et l'exécution des modèles.

### Paramètre :
Valeurs internes (les « poids ») ajustées pendant l'entraînement, qui définissent le comportement du modèle. Ex. : un modèle « 7B » a 7 milliards de paramètres. Plus de paramètres = plus de capacité, mais plus lourd.

### Prompt :
Instruction ou question donnée au modèle pour orienter sa réponse. Sa formulation influence fortement le résultat.

### Qwen :
Famille de LLM open source développés par Alibaba Cloud. Disponibles notamment via Ollama pour un usage local.

### RAG :
Technique combinant un LLM avec une base de connaissances externe : le modèle récupère des documents pertinents et s'appuie dessus pour répondre. Permet des réponses à jour, sur données privées, et réduit les hallucinations.

### Réseau de Neurones :
Structure de calcul inspirée du cerveau : des couches de « neurones » interconnectés qui transforment progressivement les données. Base du Deep Learning.

### Singularité Technologique :
Point hypothétique où l'IA dépasserait l'intelligence humaine et s'auto-améliorerait de façon incontrôlable, entraînant des changements imprévisibles. Concept prospectif et débattu.

### System Prompt :
Instruction cachée définissant le rôle, le comportement et les limites du modèle, en amont de l'échange avec l'utilisateur. Ex. : « Tu es un assistant qui répond en français, de façon concise. »

### Test de Turing :
Test proposé par Alan Turing (1950) : une machine le « réussit » si un humain, en conversation, ne parvient pas à la distinguer d'un autre humain.

### Token :
Unité de texte que le modèle manipule (souvent un morceau de mot). Le modèle lit et génère token par token. La taille de contexte et la facturation des API se comptent en tokens.

