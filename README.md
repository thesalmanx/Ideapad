# Ideapad: Next.js 13, React, Convex
## 👀 live demo at https://ideapad.salmann.dev/

A full-stack Notion-inspired app built with Next.js 13, React, Convex, and Tailwind. Features a Notion-style editor, hierarchical documents, dark mode, authentication, file management, and a fully responsive UI for seamless note-taking and organization.

Key Features:
- Real-time database  🔗 
- Notion-style editor 📝 
- Light and Dark mode 🌓
- Infinite children documents 🌲
- Trash can & soft delete 🗑️
- Authentication 🔐 
- File upload
- File deletion
- File replacement
- Icons for each document (changes in real-time) 🌠
- Expandable sidebar ➡️🔀⬅️
- Full mobile responsiveness 📱
- Publish your note to the web 🌐
- Fully collapsable sidebar ↕️
- Landing page 🛬
- Cover image of each document 🖼️
- Recover deleted files 🔄📄

### Cloning the repository

```shell
git clone https://github.com/thesalmanx/Ideapad.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

EDGE_STORE_ACCESS_KEY=
EDGE_STORE_SECRET_KEY=
```

### Setup Convex

```shell
npx convex dev

```

### Start the app

```shell
npm run dev
```
