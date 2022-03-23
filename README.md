## Commit Message Format

#### Commit Message Header

```
<type>: <task number>: <short summary>
  │          │              │
  │          │              └─⫸ Summary in present tense. Not capitalized.
  │          │
  │          └─⫸ Task Number: PP-1111, PP-2222, PP-3333 etc.
  │
  └─⫸ Commit Type: build|ci|docs|feat|fix|perf|refactor|test
```

All fields are mandatory.


##### Type

Must be one of the following:

* **build**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
* **ci**: Changes to our CI configuration files and scripts (examples: CircleCi, SauceLabs)
* **docs**: Documentation only changes
* **feat**: A new feature
* **fix**: A bug fix
* **perf**: A code change that improves performance
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **test**: Adding missing tests or correcting existing tests


## Branch Name Format

```
<type>: <task number>: <task name>
  │          │              │
  │          │              └─⫸ Not capitalized. Decorated in <a href="https://wiki.c2.com/?KebabCase">Kebab-case</a>.
  |          |                   Don't contain any special characters(", !, $, etc)
  │          │
  │          └─⫸ Task Number: PP-1111, PP-2222, PP-3333 etc.
  │
  └─⫸ Branch Name Type: docs|feat|fix|refactor|test
```

All fields are mandatory.


##### Branch Name Types

Must be one of the following:

* **docs**: Documentation only changes
* **feat**: A new feature
* **fix**: A bug fix
* **refactor**: A code change that neither fixes a bug nor adds a feature
* **test**: Adding missing tests or correcting existing tests
