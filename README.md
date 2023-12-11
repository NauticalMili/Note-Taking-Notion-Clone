# Fullstack Notion Clone: Next.js 13, React, Convex, Tailwind

Welcome to the Fullstack Notion Clone repository! This project is built using Next.js 13, React, Convex, and Tailwind, offering a feature-rich note-taking application with a variety of functionalities. Below, you'll find instructions on setting up and running the project.

## Key Features:

- **Real-time Database** 🔗
- **Notion-style Editor** 📝
- **Light and Dark Mode** 🌓
- **Infinite Children Documents** 🌲
- **Trash Can & Soft Delete** 🗑️
- **Authentication** 🔐
- **File Operations**
  - File Upload
  - File Deletion
  - File Replacement
- **Real-time Icons for Documents** 🌠
- **Expandable Sidebar** ➡️🔀⬅️
- **Full Mobile Responsiveness** 📱
- **Publish Notes to the Web** 🌐
- **Fully Collapsible Sidebar** ↕️
- **Landing Page** 🛬
- **Cover Image for Each Document** 🖼️
- **Recover Deleted Files** 🔄📄

## Prerequisites:

Ensure that you have Node.js version 18.x.x installed on your machine.

## Cloning the Repository:

````bash
git clone https://github.com/nauticalmili/Note-Taking-Notion-Clone.git


### Install Packages

```shell
npm install
````

### Setup .env file

Create a .env file in the root of your project and add the following configuration:

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

### Start the App

Now, you can start the application with the following command:

```shell
npm run dev
```

Feel free to explore the features and functionalities of this Notion Clone!
