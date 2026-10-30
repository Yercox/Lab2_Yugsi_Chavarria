# Lab2_Yugsi_Chavarria

Sitio web estático desarrollado **únicamente con HTML** para la Práctica 2 de *Fundamentos de Sistemas Web* (Versionamiento de Aplicaciones con Git y GitHub) — ESPE, Tecnologías de la Información, nivel 4.

## Objetivo

Aplicar versionamiento con Git y GitHub mediante ramas de funcionalidades, desarrollo, pruebas y producción, integrando el trabajo de dos estudiantes.

## Integrantes

| Integrante | Rama | Funcionalidad |
|---|---|---|
| Marcos Yugsi (Yercox) | `feature-marcos` | Página principal y navegación (`index.html`) |
| Dayana Chavarria (dmchavarria-rgb) | `feature-dayana` | Páginas secundarias (`sobre-nosotros.html`, `pasatiempos.html`) |

## Funcionalidades implementadas

- **Inicio**: bienvenida, imagen, listas y navegación entre páginas.
- **Sobre nosotros**: tabla de integrantes, listas ordenadas/no ordenadas y lista de definiciones.
- **Pasatiempos**: lista, tabla con encabezado y pie, y formulario con distintos tipos de campos.

## Estructura de archivos

```
Lab2_Yugsi_Chavarria/
├── index.html
├── sobre-nosotros.html
├── pasatiempos.html
└── README.md
```

## Estructura de ramas

| Rama | Propósito |
|---|---|
| `main` | Producción (versión final aprobada) |
| `pruebas` | Validación antes de pasar a producción |
| `desarrollo` | Integración de las funcionalidades |
| `feature-*` | Trabajo individual de cada integrante |

Flujo: `feature-*` → `desarrollo` → `pruebas` → `main`.

## Cómo visualizar el sitio

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Yercox/Lab2_Yugsi_Chavarria.git
   cd Lab2_Yugsi_Chavarria
   ```
2. Abrir `index.html` en el navegador (doble clic o *Open with Live Server* en VS Code).

## Comandos principales utilizados

```bash
git init · git branch -M main · git add . · git commit -m "..."
git remote add origin <url> · git push -u origin <rama>
git switch <rama> · git switch -c <rama> · git merge <rama>
git branch -a · git status · git log --oneline --graph --all · git remote -v
```

## Protección de `main`

Los cambios a `main` se incorporan únicamente mediante *Pull Request* con al menos una aprobación.
