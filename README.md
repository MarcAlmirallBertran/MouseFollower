# Mouse Follower in React + TypeScript + Vite

This project is a minimal setup to get React working in Vite with HMR and some ESLint rules. It includes a feature where a UI element follows the mouse cursor around the screen.
You can check the result here: [MouseFollower](https://mousefollower.pages.dev/)

## Features

- Mouse follower: A UI element that follows the mouse cursor around the screen. This is implemented in the [`FollowMouse`](src/components/FollowMouse.tsx) component.
- ESLint: The project is configured with a set of ESLint rules for React and TypeScript. See the configuration in [`.eslintrc.cjs`](.eslintrc.cjs).
- Styling: The project uses CSS for styling. See the main styles in [`src/index.css`](src/index.css) and [`src/App.css`](src/App.css).

## Getting Started

1. Clone the repository.
2. Install the dependencies with `pnpm install`.
3. Start the development server with `pnpm run dev`.

## Scripts

- `pnpm run dev`: Starts the development server.
- `pnpm run build`: Builds the project for production.
- `pnpm run lint`: Runs ESLint on the project.
- `pnpm run preview`: Previews the production build.

## Dependencies

- React 18.3.1
- TypeScript 5.4.5
- Vite 5.3.1
- And others. See the full list in [`package.json`](package.json).
