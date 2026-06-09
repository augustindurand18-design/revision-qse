# Design : Pop-up de Première Visite

Permet d'inviter l'utilisateur à créer un profil dès sa première visite pour simplifier l'accès au classement en ligne.

## Spécifications

1. **Détection au chargement** :
   - Dans le listener `DOMContentLoaded`, après l'appel de `loadProfiles()`, on vérifie si la liste globale `profiles` est vide.
   - Si la liste est vide, on déclenche automatiquement le pop-up `showCreateProfileModal()`.

2. **Simplification des règles du pseudo** :
   - Modification de la fonction `saveNewProfile()` pour n'imposer qu'une seule règle : **3 caractères minimum**.
   - Suppression de la limite supérieure de 15 caractères et de l'unicité du pseudo.
