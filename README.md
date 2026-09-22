# Emergency Services Frontend

A React interface concept for discovering emergency-service information, paramedics, and related resources. This repository is the `lmai` version in a family of related frontend iterations.

## Start here

For an overview of the project family, start with [savemedeployment](https://github.com/CyberTekena/savemedeployment). It is a UI prototype; it should not be used to request real emergency assistance.

## Screens in this version

- `/`
- `/Home`
- `/Signup`
- `/Login`
- `/Location`
- `/Call`
- `/ContactUs`
- `/Resources`
- `/ResourcesFirstPage`
- `/ResourcesSecondPage`
- `/ResourcesThirdPage`
- `/ResourcesFourthPage`
- `/Donation`
- `/About`

These routes are declared in [src/App.jsx](src/App.jsx). A screen or form does not imply a live dispatch, payment, or authentication service. Marketing numbers in the interface are presentation copy, not measured usage statistics.

## Run locally

Install Node.js and npm:

```sh
git clone https://github.com/CyberTekena/lmai.git
cd lmai
npm install
npm run dev
```

Open the URL printed by Vite.

## Project structure

- [src/App.jsx](src/App.jsx) — route definitions.
- [src/component/landing.jsx](src/component/landing.jsx) — landing page.
- [src/pages](src/pages) and [src/pagess](src/pagess) — page and account-screen components.
- CSS files alongside the components provide page styling.
- The `src/recourcespage/` directory contains resource screens.

## Development commands

| Command | Existing script |
| --- | --- |
| `npm run dev` | `vite` |
| `npm run build` | `vite build` |
| `npm run lint` | `eslint . --ext js,jsx --report-unused-disable-directives --max-warnings 0` |
| `npm run preview` | `vite preview` |


## Related iterations

[deployment](https://github.com/CyberTekena/deployment) · [learn_website](https://github.com/CyberTekena/learn_website) · [lmao](https://github.com/CyberTekena/lmao) · [lmai](https://github.com/CyberTekena/lmai) · [satur1](https://github.com/CyberTekena/satur1) · [satur2](https://github.com/CyberTekena/satur2) · [satur3](https://github.com/CyberTekena/satur3) · [learnable2187](https://github.com/CyberTekena/learnable2187) · [learnable21](https://github.com/CyberTekena/learnable21) · [savemedeployment](https://github.com/CyberTekena/savemedeployment)

These repositories share substantial interface code. They are grouped as iterations of one project rather than presented as separate completed products. Their source and commit histories remain available.

## Next improvements

Consolidate active development into one repository, separate demonstration data from live integrations, test navigation and form behavior, and document deployment configuration. Existing route names and directory spellings are retained to avoid breaking imports.

## Verification

Routes, scripts, and structure were checked against this repository. No live-service or runtime-validation claim is made.

## Author

Tekena Ajuzieogu · [GitHub](https://github.com/CyberTekena)
