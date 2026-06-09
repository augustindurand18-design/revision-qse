# Révision QSE - Organisation du dossier

Ce dépôt a été réorganisé pour séparer clairement les cours originaux en PDF/PPTX des fichiers de code, des résumés Markdown et des ressources de l'agent.

## Structure du projet

```text
correia/
├── Cours PDF/                     # Tous les cours originaux au format PDF et PowerPoint (.pptx)
│   ├── Livret 5S.pdf
│   ├── Livret AMDEC.pdf
│   ├── Livret Gestion des risques professionnels.pdf
│   ├── Livret Indicateurs.pdf
│   ├── Livret Qualité et ISO 9001.pdf
│   ├── Livret Système documentaire.pdf
│   ├── Livret Traitement des NC.pdf
│   ├── Livret approche processus.pdf
│   ├── Livret définition et enjeux de la qualité.pdf
│   ├── Livret environnement.pptx
│   └── Livret ergonomie.pdf
│
├── code_agent/                    # Fichiers de code, résumés de cours et configurations de l'agent
│   ├── index.html                 # Application web de révision (QCM)
│   ├── QCM_Entrainement.html      # Copie de l'application web de révision
│   ├── docs/                      # Spécifications et documentation de développement
│   ├── antigravity-skills/        # Dossier des compétences personnalisées de l'agent
│   └── [Livrets].md               # Résumés des cours au format Markdown (utilisés par l'agent)
│
├── .gitignore                     # Configuration Git mise à jour
└── README.md                      # Ce fichier d'explications
```

## Lancer l'application de révision (QCM)

Pour lancer le QCM d'entraînement, ouvrez simplement le fichier `code_agent/index.html` (ou `code_agent/QCM_Entrainement.html`) dans votre navigateur internet.
