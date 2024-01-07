# Vite + React + TypeScript + Supabase

This repository is experimenting with a combined implementation of Vite, React, TypeScript, and Supabase.

## Requirements

- [Supabase](https://supabase.com/)

This application uses Supabase. It is based on a tutorial as of January 2024. For more details on the tutorial, please refer to the [documentation](https://supabase.com/docs/guides/getting-started/tutorials/with-react).

- [Volta](https://volta.sh/)

Node.js is required to run this application. Please install Volta to automatically use the suitable Node.js version.

## Recommended

- [Visual Studio Code](https://code.visualstudio.com/)

The recommended extensions for Visual Studio Code are listed in [.vscode/extensions.json](.vscode/extensions.json).

## Environment Variables

Environment variables are used in the `createClient`. For more details, please refer to the [documentation](https://github.com/supabase/supabase-js?tab=readme-ov-file#usage).

```
VITE_SUPABASE_URL=YOUR_SUPABASE_URL
VITE_SUPABASE_ANON_KEY=YOUR_SUPABASE_ANON_KEY
```

## Getting Started

- Clone repository.

```
git clone https://github.com/kwn1125/vite-react-typescript-supabase-experiment.git <project_directory>
```

- Install dependencies by referencing the package-lock.json.

```
cd <project_directory>
npm ci
```

- Update the empty value and rename `.env.sample` to `.env.local`.
- Launch the application.

```
npm run dev
```
