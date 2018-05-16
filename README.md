# git-hooks

**Pre-commit**
  - Prevent committing to `master` rather than a feature branch

**Pre-push**
  - Run `coffeelint` on the **app** and **spec** directories
  - Print GitHub compare URL for the branch

## Requirements

[CoffeeLint](http://www.coffeelint.org):
```
npm install -g coffeelint
```

## Installation

```
rm -r /path/to/my-repository/.git/hooks
ln -s /path/to/git-hooks/ /path/to/my-repository/.git/hooks
```
