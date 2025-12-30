# Analyse des Mouvements de Stock (SAV) : Flux et Rotation
---
**gras**  
*italique*
* puce
  * puce
---
## 📊 Méthodologie / GESTION DE PROJET

STAR+L : Situation (problème) - Task (solution) - Action (méthode) - Result (résultat) - Learning (conclusion)

### Etape 1 : Business Case (le S de STAR)

Situation : La gestion des écarts de stock donne lieu a une prime pour les techniciens, mais les mouvements de stock repartent dans tous les sens depuis le covid. Il faut donc un meilleur contrôle et prévenir les dérapages de coûts.

### Etape 2 : Préparation des données
Gsheets et SQL
### 📖 Dictionnaire des données
| Colonne | Type | Description |
| :--- | :--- | :--- |
| date_vente | DATE | Date de la transaction (YYYY-MM-DD) |
| produit_nom | VARCHAR | Nom complet du produit |
| quantite | INT | Nombre d'unités vendues |
| prix_unitaire | FLOAT | Prix de vente d'une unité (en €) |
