# MonoRepo-test

### init
```
lerna init
```

### with yarn
- lerna.json
```json
{
  "npmClient": "yarn",
  "useWorkspaces": true
}
```
- package.json
```json
{
  "workspaces": [
    "packages/*"
  ],
}
```