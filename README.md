# To-Do-List-Laravel
Projet qui nous permettra de prendre en Lavarel
Excellente idée ! Laravel est puissant, mais il vaut mieux commencer avec un **projet web simple**, pour apprendre **les bases solides** : routes, contrôleurs, modèles, vues Blade, formulaires, validation, base de données, etc.

---

## 💡 **Idée de projet web avec Laravel : "Gestionnaire de Tâches"**

> Une mini application de type **"To-Do List"**, où l’utilisateur peut ajouter, modifier, marquer comme terminée et supprimer des tâches.

---

### 🎯 Fonctionnalités à développer :

1. ✅ **Afficher toutes les tâches**

   * Titre, statut (faite ou pas), date de création

2. ➕ **Ajouter une tâche**

   * Formulaire avec champ : `titre`, éventuellement `description`

3. ✏️ **Modifier une tâche**

   * Éditer le texte, changer le statut

4. ❌ **Supprimer une tâche**

   * Avec confirmation

5. ✅ **Marquer comme faite/non faite**

   * Checkbox ou bouton

---

### 🔧 Concepts Laravel que tu vas pratiquer :

| Concept Laravel                        | Exemple dans l'app                         |
| -------------------------------------- | ------------------------------------------ |
| 📁 **Routes** (`web.php`)              | `/`, `/taches/create`, `/taches/{id}/edit` |
| 🧠 **Contrôleurs** (`TacheController`) | logique pour gérer les actions CRUD        |
| 🗄️ **Modèles & migrations**           | `Tache` avec migration de table `taches`   |
| 💻 **Vues Blade** (`index.blade.php`)  | HTML + Blade (boucles, conditions)         |
| 📝 **Formulaires**                     | Ajout/modification de tâche                |
| ✅ **Validation**                       | `request()->validate([...])`               |
| 🔐 **Protection CSRF**                 | avec `@csrf` dans les formulaires          |
| 🔁 **Redirections & messages flash**   | `redirect()->back()->with('success', ...)` |
| 📅 **Eloquent & Timestamps**           | gestion automatique des dates              |

---

### ⚙️ Bonus pour progresser plus loin :

* 🧑‍💼 **Authentification** (`php artisan make:auth` ou Laravel Breeze/Jetstream)
* 🔍 **Filtrage ou recherche** des tâches
* 📈 Statistiques simples : % de tâches terminées
* 📄 **Export PDF** (avec `barryvdh/laravel-dompdf`)
* API RESTful (si tu veux apprendre Laravel API + Flutter/Vue)

---

### 🧪 Résultat attendu (interface simple) :

```
+------------------------------------+
| Mes Tâches                         |
+------------------------------------+
| [ ] Acheter du lait         [✏️] [🗑️] |
| [x] Réviser Laravel         [✏️] [🗑️] |
+------------------------------------+
[ + Ajouter une tâche ]
```

---

### Tu veux aller plus loin ?

Je peux t’écrire :

* la **structure du projet** (fichiers essentiels),
* ou même te générer les **commandes artisan** et le **code des contrôleurs/vues de base**.

Tu veux que je te prépare ça ?
