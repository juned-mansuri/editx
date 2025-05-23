<p align="center">
  <a href="https://liveblocks.io#gh-light-mode-only">
    <img src="https://raw.githubusercontent.com/liveblocks/liveblocks/main/.github/assets/header-light.svg" alt="Liveblocks" />
  </a>
  <a href="https://liveblocks.io#gh-dark-mode-only">
    <img src="https://raw.githubusercontent.com/liveblocks/liveblocks/main/.github/assets/header-dark.svg" alt="Liveblocks" />
  </a>
</p>

# My Collaborative Rich Text Editor

This project is a collaborative rich text editor built using [Liveblocks](https://liveblocks.io), [Tiptap](https://tiptap.dev), and [Next.js](https://nextjs.org/).

As users edit the document, changes are automatically persisted and synced in real-time across clients. Users can also see each other’s cursors in the document.

## Features
- Real-time collaboration
- Cursor presence
- Rich text editing

## Getting Started

### Prerequisites
- Node.js installed on your machine
- A [Liveblocks](https://liveblocks.io) account

### Steps to Run Locally
1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-name>
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up Liveblocks:
   - Create an account on [liveblocks.io](https://liveblocks.io/dashboard)
   - Copy your **secret** key from the [dashboard](https://liveblocks.io/dashboard/apikeys)
   - Create an `.env.local` file and add your **secret** key as the `LIVEBLOCKS_SECRET_KEY` environment variable
4. Run the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and go to [http://localhost:3000](http://localhost:3000)

## Deploying

### Vercel
To deploy on [Vercel](https://vercel.com), run:
```bash
npx create-liveblocks-app@latest --example nextjs-tiptap-advanced --vercel
```

### CodeSandbox
To develop on CodeSandbox, fork [this example](https://codesandbox.io/s/github/liveblocks/liveblocks/tree/main/examples/nextjs-tiptap-advanced) and create the `LIVEBLOCKS_SECRET_KEY` environment variable as a [secret](https://codesandbox.io/docs/secrets).
