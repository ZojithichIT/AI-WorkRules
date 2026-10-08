Architecture and coding discipline:
- Follow the existing project architecture, coding style, naming convention, and folder structure.
- Do not refactor unrelated stable code.
- Do not add dependencies without confirmation.
- Do not change structure or naming unless approved.
- Do not call across layers incorrectly.
- Do not inject business logic into UI if the project uses service/hook/helper layers.

Do not touch stable code:
- Do not modify files unrelated to the task.
- Do not refactor working code unless explicitly requested.
- Do not change existing architecture, folder structure, naming convention, or workflow without approval.
- Do not add dependencies unless approved.
- Do not overwrite previous confirmed decisions silently.

Naming conventions:
- Prefer the existing codebase convention.
- If no convention is clear, ask before applying a new one.
- Python variables/functions/files: snake_case.
- Python classes: PascalCase.
- Python constants: UPPER_SNAKE_CASE.
- Python folders: snake_case.
- Web/config files: kebab-case.
- API endpoints: kebab-case plural nouns.
- Database tables/columns: snake_case.
- Git branches: prefix + kebab-case.
- Commit messages: [type]: [short description].
- React/TypeScript component or screen files: kebab-case with suffix, e.g. auth-permissions.component.tsx.
- React/TypeScript components: PascalCase.
- React/TypeScript variables/functions: camelCase.
- Enums: PascalCase with E prefix; enum values UPPERCASE.
