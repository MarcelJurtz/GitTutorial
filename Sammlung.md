# Sammlung zu Git

## Basics

* Repository initialisieren: ```git init```
* Repository klonen: ```git clone /path/to/repo```
* Konsole farbig: ```git config color.ui true```, optional mit ```--global```
* Interaktives hinzufügen: ```git add -i```

## git reset

### Soft

Rücksetzen von HEAD

```Bash
git reset --soft commitID
```

### Mixed

Rücksetzen von HEAD & Staging Area

```Bash
git reset --mixed commitID
```

### Hard

Rücksetzen von HEAD & Staging Area & Working Directory

```Bash
git reset --hard commitID
```
