# Unnecessary "pep440: failed to calculate newValue" warning in logs [#30717](https://github.com/renovatebot/renovate/discussions/30717)

Via https://github.com/renovatebot/renovate/discussions/30717

## Expected behaviour

No `WARN` log is displayed to indicate that the version cannot be updated.

## Actual behaviour

```
 WARN: pep440: failed to calculate newValue (repository=local)
       "result": "<2,>=2.2",
       "newVersion": "2.2.2",
       "currentValue": "<2,>=1.5"
```

And a notice on the Dependency Dashboard.

## Link to the Renovate issue or Discussion

https://github.com/renovatebot/renovate/discussions/30717
