## Format

```
<type>(optional scope): <short summary>
```

---
## Types

- **feat** → a new feature
- **fix** → a bug fix
- **docs** → documentation only changes
- **style** → code style (formatting, missing semi-colons, spaces, etc.)
- **refactor** → code changes that neither fix a bug nor add a feature
- **perf** → performance improvements
- **test** → adding or modifying tests
- **chore** → build process, tooling, CI/CD, dependencies
---
## Rules for the `<summary>`

✅ Use **imperative mood**: "add" not "added" or "adds".  
✅ Max **50 characters**.  
✅ **Capitalize** first letter.  
✅ No period at the end.

**Good examples:**

```
feat(auth): add JWT-based authentication
fix(db): resolve migration issue on PostgreSQL
docs(readme): update setup instructions
```

**Bad examples:**

```
Added JWT-based authentication.
fixing the bug with database
Refactored code for performance improvements
```

---
## Common commit scopes

#### General Scopes

- **core** → core logic of the project
- **config** → configuration files (e.g., `application.yml`, `.env`)
- **deps** → dependencies (Maven/Gradle/NPM/etc.)
- **ci** → CI/CD pipelines, GitHub Actions, Dockerfiles

#### Backend / API Projects

- **api** → REST/GraphQL endpoints
- **auth** → authentication & authorization
- **db** → database models, migrations, queries
- **service** → business/service layer
- **repo** → repositories / DAOs
- **test** → unit or integration tests
- **security** → security-related fixes

#### Frontend Projects

- **ui** → user interface components
- **ux** → user experience improvements
- **style** → CSS, Tailwind, design tweaks
- **state** → state management (Redux, Vuex, etc.)

#### DevOps / Infrastructure

- **build** → build system changes (Maven/Gradle/Webpack)
- **docker** → Dockerfiles, Compose setup
- **infra** → server configs, deployment scripts
- **monitoring** → logging, metrics, health checks

#### Documentation

- **readme** → README.md updates
- **docs** → general documentation

--- 
## No scope messages

If you don’t mention a **scope**, the commit message just skips the `(scope)` part — totally valid ✅
### Example **without scope**:

```
feat: add JWT login
fix: correct navbar alignment
docs: update installation steps
```

 **When to use scope**:

- Use it if the project is **large** and you want to show _where_ the change applies (auth, db, api, ui, etc.).
- Skip it if the project is **small** or the commit is self-explanatory.

---

