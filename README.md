Template project for Node
===

Node
---

- `package.json` ready to receive the dependencies (just need to remember to replace the name after the `degit`)
- a `.npmrc` preventing `package-lock`, to be removed if not building a library
- a `.nvmrc` to set the NodeJS version

Linting
---

- code formatting with Prettier, making sure all code looks the same without having to worry about it. In turn, this means more meaningful git diffs.
- linting with ESLint and basic plugins on their recommended default.

Git
---

- Git hooks to lint the files on commit with `husky` and `lint-staged`, a little safeguard.
- consistent commit message format with `commitizen` and `commitlint`. A personal preference, but I like the tidiness and the categorized format.

Testing
---

- testing with `ava`, set up to look for tests in `__tests__` folder, keeping them close to what they test.

CI
---

- basic CI configuration for TravisCI and Appveyor
