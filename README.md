\# Inventario CI/CD



Proyecto de laboratorio para la asignatura \*\*Gestión y Configuración del Software\*\*  

Universidad de Guayaquil — Carrera de Ingeniería de Software  

Año lectivo 2026-2027



\## Descripción



Sistema web de inventario desarrollado con Node.js + Express (backend) y React + Vite (frontend), con pipeline completo de CI/CD usando GitHub Actions.



\## Tecnologías



\- \*\*Backend:\*\* Node.js, Express, Jest, Supertest

\- \*\*Frontend:\*\* React, Vite, Vitest, Testing Library

\- \*\*CI/CD:\*\* GitHub Actions



\## Estructura del proyecto

inventario-ci-cd/

├── backend/

│   └── src/

│       ├── app.js

│       ├── app.test.js

│       ├── inventoryService.js

│       ├── inventoryService.test.js

│       └── server.js

├── frontend/

│   └── src/

│       ├── App.jsx

│       ├── App.test.jsx

│       └── setupTests.js

└── .github/

└── workflows/

├── ci-backend.yml

├── ci-frontend.yml

└── deploy.yml


\## Instalación



\### Backend

```bash

cd backend

npm install

npm start

```



\### Frontend

```bash

cd frontend

npm install

npm run dev

```



\## Pruebas



\### Backend

```bash

cd backend

npm test

```



\### Frontend

```bash

cd frontend

npm test -- --run

```



\## Pipeline CI/CD



| Workflow | Descripción |

|----------|-------------|

| CI Backend | Ejecuta pruebas Jest en cada push |

| CI Frontend | Ejecuta pruebas Vitest en cada push |

| Deploy (Simulado) | Se activa cuando ambos CI pasan |



\## Autores



Hector Gonzalez Vera - Walter Bernardi Correa

Universidad de Guayaquil — 2026



