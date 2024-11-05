# **DEVLOG** - *ScriptGenerator* -> **1.0.0-alpha**

La version **1.0.0-alpha** de l'application **ScriptGenerator** a été déployée ! Cette première version permet de créer automatiquement des scripts à partir de fichiers `json` spécifiques.

Un `installateur` a été mis en place pour simplifier l'installation sur Windows, incluant la création d'un raccourci sur le bureau pour un accès direct à l'application.

## Fonctionnalités

### 📄 Génération de PDF à partir de fichiers JSON
L'application prend un fichier `json` en entrée et génère automatiquement un `pdf` contenant :

1. **Page de couverture**
   - **Informations du document** : Nom du document, nom traduit, type, auteur original, traducteur, créateur du script, lien, site web et email.

2. **Liste des rôles**
   - Détails des rôles :
      - Nombre de rôles
      - Informations sur chaque rôle : nom, genre, lignage, première apparition
      - Le lignage total

3. **Script**
   - Affichage complet en noir et blanc.
   - **Rôles** et **timecodes** en **gras** pour une meilleure lisibilité.

## 💡 Idées d'Améliorations

Nous sommes ouverts à toutes suggestions pour améliorer `ScriptGenerator` ! Faites-nous part de vos idées d'ajouts, que ce soit pour enrichir le `pdf` de script actuel ou pour introduire d'autres types de `pdf`.

### 🚀 Suggestions d'Avenir

Ici figureront toutes les suggestions que nous recevons !

### Nous attendons vos retours et idées avec impatience pour faire évoluer `ScriptGenerator` !