# Contributing

## jqwik Contributor Agreement

- Your contribution will be provided under the project's license.

### Project License

_jqwik_ currently uses the [Eclipse Public License v2.0](./LICENSE.md).

## Pull Requests

Please add the following lines to your pull request description:

```markdown
---

I hereby agree to the terms of the jqwik Contributor Agreement.
```

## Coding Conventions

__Work in progress but nevertheless strictly enforced._

Using [`.editorconfig`](./.editorconfig) will simplify your life when formatting jqwik code.

### Everywhere

Use only wildcard imports.

### Tests

Use _jqwik_ itself for all tests and properties.

Use _AssertJ_ for non-trivial assertions.

Use `@ForAll Random random` parameter if you need a random value. 
