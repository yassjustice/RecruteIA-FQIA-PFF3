# Guide Détaillé du Workflow Notion

## 🎯 Introduction

Ce guide explique comment utiliser efficacement Notion pour le projet RecruteIA. Il est basé sur la vidéo d'onboarding et contient toutes les règles que vous devez suivre.

---

## 📍 Où Travailler ?

### ❌ NE PAS utiliser le tableau général

Le Sprint Backlog principal contient TOUTES les tâches de TOUS les membres. Il est difficile à naviguer et vous risquez de modifier les tâches des autres.

### ✅ UTILISEZ votre page personnelle

Chaque membre a une page dédiée avec :
- Un tableau filtré montrant uniquement VOS tâches
- Les mêmes fonctionnalités que le tableau principal
- Une vue plus claire et organisée

**Accès** : Page d'équipe → Votre nom → Votre tableau

---

## 📊 Les Colonnes de Statut

### Ordre des colonnes (de gauche à droite)

| # | Colonne | Signification | Qui peut y mettre ? |
|---|---------|---------------|---------------------|
| 1 | **To Do** | Tâche non commencée | Manager (assignation) |
| 2 | **In Progress** | Vous travaillez dessus | Vous |
| 3 | **Review** | Prêt pour révision | Vous |
| 4 | **Done** | Tâche validée | Manager UNIQUEMENT |
| 5 | **Blocked** | Problème détecté | Manager |

---

## 🔄 Le Cycle de Vie d'une Tâche

### 1. Nouvelle tâche assignée
```
Manager assigne → Apparaît dans "To Do" sur votre page
```

### 2. Vous commencez à travailler
```
Glissez la carte : To Do → In Progress
```

### 3. Vous terminez votre travail
```
Glissez la carte : In Progress → Review
⚠️ NE METTEZ PAS EN "DONE" !
```

### 4. Le manager révise
**Scénario A** : Travail accepté
```
Manager déplace : Review → Done ✅
```

**Scénario B** : Corrections nécessaires
```
Manager déplace : Review → Blocked 🚫
Manager ajoute un commentaire expliquant le problème
```

### 5. Si votre tâche est "Blocked"
```
1. Lisez le commentaire du manager
2. Comprenez ce qui doit être corrigé
3. Déplacez : Blocked → In Progress
4. Faites les corrections
5. Déplacez : In Progress → Review
6. Attendez la nouvelle révision
```

---

## ⚠️ Règles Importantes

### Règle #1 : Jamais de "Done" par vous-même
> Seul le manager peut marquer une tâche comme terminée. C'est lui qui valide votre travail.

### Règle #2 : Toujours lire les commentaires
> Si une tâche est "Blocked", le manager a laissé un commentaire. Lisez-le attentivement avant de reprendre le travail.

### Règle #3 : Un flux linéaire
> Suivez toujours l'ordre : To Do → In Progress → Review
> Pas de raccourcis !

### Règle #4 : Votre page, vos tâches
> Travaillez uniquement depuis votre page personnelle, pas depuis le tableau général.

---

## 📝 Diagramme du Workflow

```
                    ┌─────────────────────────────────────┐
                    │         WORKFLOW DES TÂCHES         │
                    └─────────────────────────────────────┘

    ┌─────────┐         ┌─────────────┐         ┌─────────┐
    │         │   Vous  │             │   Vous  │         │
    │  To Do  │ ──────► │ In Progress │ ──────► │ Review  │
    │         │ commencez│             │ terminez│         │
    └─────────┘         └─────────────┘         └────┬────┘
                               ▲                     │
                               │                     │ Manager
                               │                     │ révise
                        Vous   │                     ▼
                        corrigez│              ┌──────────┐
                               │              │ Décision │
                        ┌──────┴──────┐       └────┬─────┘
                        │             │            │
                        │   Blocked   │◄───────────┤ Si problèmes
                        │             │            │
                        └─────────────┘            │
                                                   │ Si OK
                                                   ▼
                                            ┌─────────┐
                                            │  Done   │
                                            │   ✅    │
                                            └─────────┘
```

---

## ✅ Checklist Quotidienne

Chaque jour, vérifiez :

- [ ] Ai-je des tâches en "To Do" à commencer ?
- [ ] Mes tâches "In Progress" avancent-elles ?
- [ ] Ai-je des tâches "Blocked" avec des commentaires non lus ?
- [ ] Mes tâches terminées sont-elles en "Review" ?

---

## 💡 Conseils Pratiques

1. **Vérifiez Notion chaque matin** — Les tâches peuvent changer de statut pendant la nuit

2. **Lisez les commentaires** — Le manager communique via les commentaires

3. **Posez des questions** — Si quelque chose n'est pas clair, demandez au manager

4. **Mettez à jour régulièrement** — Ne laissez pas des tâches en "In Progress" pendant des jours sans mise à jour

---

## 🎬 Référence Vidéo

Pour une démonstration visuelle, regardez :
`assets/videos/Video Project 3.mp4`

---

*Ce guide est basé sur le workflow officiel du projet RecruteIA.*
