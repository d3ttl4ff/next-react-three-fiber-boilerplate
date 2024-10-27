# Next React Three Fiber Boilerplate

This is a boilerplate for React Three Fiber projects with Next.js.

## `Features`

|                              Feature/ Dependency                              | Version Installed |                                    Description                                    |
| :---------------------------------------------------------------------------: | :---------------: | :-------------------------------------------------------------------------------: |
|                        [next](https://nextjs.org/docs)                        |      14.2.16      |       Next.js is a React framework for building full-stack web applications.      |
|                 [three](https://www.npmjs.com/package/three)                  |      0.169.0      |                              JavaScript 3D library.                               |
|       [@react-three/fiber](https://github.com/pmndrs/react-three-fiber)       |      8.17.10      |                            React renderer for threejs.                            |
|              [@react-three/drei](https://github.com/pmndrs/drei)              |      9.115.0      | A collection of useful helpers and ready-made abstractions for react-three-fiber. |
| [@react-three/postprocessing](https://github.com/pmndrs/react-postprocessing) |      2.16.3       |                   Postprocessing wrapper for @react-three/fiber.                  |
|             [postprocessing](https://www.npmjs.com/package/three)             |      6.36.3       |                        Post processing libray for threejs.                        |
|                    [leva](https://github.com/pmndrs/leva)                     |      0.9.34       |           A GUI component for debugging react three fiber applications.           |
|               [r3f-perf](https://github.com/utsuboco/r3f-perf)                |       7.2.2       |          Monitor the performances of your react-three-fiber application.          |

## `Folder Structure`

```bash
.
└── src/
    └── app/
        ├── components/
        │   ├── canvas/
        │   │   └── Scene.jsx
        │   └── dom
        ├── experience/
        │   ├── common/
        │   │   ├── index.jsx
        │   │   ├── LevaPane.jsx
        │   │   └── PerformanceMonitor.jsx
        │   ├── environment/
        │   │   ├── index.jsx
        │   │   └── Lights.jsx
        │   ├── post-processing/
        │   │   ├── index.jsx
        │   │   └── Effects.jsx
        │   ├── world/
        │   │   ├── index.jsx
        │   │   └── Base.jsx
        │   └── Experience.jsx
        ├── layout.js
        └── page.js
```

## `Quick Start`

```bash
git clone https://github.com/d3ttl4ff/react-three-fiber-boilerplate.git
```

```bash
npm install
```

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev

```
