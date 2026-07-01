# Tailwind CSS 4.1.18 — WSC2026

A small, real **Tailwind CSS** application (version **4.1.18**), part of the WorldSkills 2026
Web Technologies (TP17) set. Runtime pinned to the competition spec.

## Run it

```bash
docker compose up --build
```

Then open **http://localhost:5173**. This starts the app's dev server inside Docker — no local
toolchain required.

Stop it with `docker compose down`.

## Develop

For a hot-reloading loop on your machine you need **Node 24.1.0** and **npm 11.5.0** installed locally (the same versions the Docker image pins).

```bash
npm install
npm run dev
```

The dev server runs on **http://localhost:5173** and reloads on save.
Edit **index.html and src/style.css** to change the app.

## Stack

- Node 24.1.0 / npm 11.5.0
- Tailwind CSS 4.1.18
