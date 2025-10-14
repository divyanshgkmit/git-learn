# Pull Request Convention

## PR Title Format

```
<ISSUE TYPE>: Short Description (<CLOSING TYPE> #<ISSUE NUMBERS>)
```

**Examples:**

* `feat: add new feature (close #111)`
* `fix: wrong behavior (fix #111)`
* `chore: change build tool (ref #111)`

### Allowed Issue Types

* `feat`: A new feature
* `fix`: A bug fix
* `docs`: Documentation-only changes
* `style`: Changes that do not affect the meaning of the code (e.g., white-space, formatting)
* `refactor`: Code changes that neither fix a bug nor add a feature
* `perf`: Code changes that improve performance
* `test`: Adding missing tests
* `chore`: Changes to the build process or auxiliary tools and libraries

### Closing Types

* `close`: Resolves the issue completely (non-bug: feature, docs, etc.)
* `fix`: Resolves a bug completely
* `ref`: Related to or partially resolves the issue

---

## PR Checklist

- The title uses the correct issue type and closing format
- Referenced issue(s) are included in the title (e.g., `fix #123`)
- The commit message follows the contribution guidelines
- Tests for the changes have been added (if applicable)
- Documentation has been added or updated
- No breaking changes introduced, or a clear description is provided


