# Calculadora de Granjas Rust

App de Next.js/React/TypeScript para calcular producción de granjas en Rust
(módulos × planters × plantas × rendimiento), con conversión a tés.
Todo el cálculo corre en el navegador (client component), no usa base de datos ni backend.

## Desarrollo local

```bash
npm install
npm run dev
```

## Deploy en Vercel (recomendado)

1. Sube esta carpeta a un repositorio en GitHub.
2. Entra a vercel.com, inicia sesión con GitHub, "Add New Project" y elige el repo.
3. Vercel detecta Next.js automáticamente. Dale "Deploy".
4. Cada push a la rama principal se publica solo.
