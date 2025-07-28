# 📦 ShareJSON

**ShareJSON** est une application web moderne qui permet de créer, stocker, visualiser et partager des données JSON de manière simple, sécurisée et intuitive.

---

## ✨ Fonctionnalités

✅ Authentification sécurisée avec Clerk  
✅ Création de fichiers JSON personnalisés  
✅ Stockage local (SQLite via Prisma ORM)  
✅ Dashboard personnel pour visualiser les données  
✅ Visualisation des JSON partagés  
✅ Interface responsive et moderne avec Tailwind CSS  

---

## 🔍 Aperçu

![Homepage](./screenshots/home.png)  
![Dashboard](./screenshots/dashboard.png)  
![JSON Viewer](./screenshots/json-viewer.png)

---

## 🚀 Démo en ligne

🔗 [https://sharejson.vercel.app](https://sharejson.vercel.app)

---

## 🧪 Technologies utilisées

| Outil / Framework   | Rôle                        |
|---------------------|-----------------------------|
| [Next.js](https://nextjs.org/)        | Frontend + Backend intégré |
| [TypeScript](https://www.typescriptlang.org/)   | Typage du projet            |
| [Tailwind CSS](https://tailwindcss.com/)        | Design et mise en page      |
| [Clerk](https://clerk.dev/)          | Authentification utilisateur|
| [Prisma](https://www.prisma.io/)      | ORM (SQLite/PostgreSQL)     |
| [SQLite](https://www.sqlite.org/)     | Base de données légère      |

---

## ⚙️ Installation locale

```bash
# 1. Clone ce dépôt
git clone https://github.com/RihemMersani/ShareJSON.git
cd ShareJSON

# 2. Installe les dépendances
npm install

# 3. Configure ton fichier .env
cp .env.example .env
# puis remplis les clés Clerk et la DATABASE_URL

# 4. Initialise la base de données
npx prisma generate
npx prisma db push

# 5. Lance le projet en local
npm run dev
