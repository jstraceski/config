# config

## How to clone

```bash
git init
git config core.sparseCheckout true
git remote add -f origin git@github.com:jstraceski/config.git
```

Set the restricted directories.
```bash
git sparse-checkout set ./README.md # Add the directories here
```

Checkout the files.
```bash
git checkout
```
