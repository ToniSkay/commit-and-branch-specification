## Commit Message Format

#### Commit Message Header

```
<task number> <short summary>
  │                 │
  │                 └─⫸ Summary in present tense. Not capitalized.
  │
  └─⫸ Task Number: PP-1111, PP-2222, PP-3333 etc.
```

All fields are mandatory.

## Branch Name Format

```
<type>/ <task number>-<task name>
  │          │              │
  │          │              └─⫸ Not capitalized. Decorated in Kebab-case.
  |          |                   Don't contain any special characters(", !, $, etc)
  │          │
  │          └─⫸ Task Number: PP-1111, PP-2222, PP-3333 etc.
  │
  └─⫸ Branch Name Type: feature|fix|tech
```

All fields are mandatory.


##### Branch Name Types

Must be one of the following:

* **feature**: A new feature
* **fix**: A bug fix
* **tech**: Some refactoring or feature for improve code style without affect of end user.
