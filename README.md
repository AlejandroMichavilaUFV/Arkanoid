# Como hacer una proyecto

```bash 
git clone <proyecto> ```

```bash 
git flow init 
```

```bash 
git fetch --all 
```

```bash
 git branch -b <nombrebranch> 
 ```

```bash
 for comit in comits
    git add .
    git commit -m "mensaje"


    git push origin <nombrebranch>
```
---

## para hacer una feature sin gitflow

```bash
git checkout -b <feature/nombrebranch>

git add .

git commit -m "mensaje"

git checkout <rama-principal>

git merge <feature/nombrebranch>

git push origin <rama-principal>

git branch -d <feature/nombrebranch>

```
---
```bash
git checkout -b <rama-release>

git merge <rama-desarrollo>

git tag -a <version> -m "mensaje"

git push origin <rama-release>

git push --tags //sube los tags de tu rama
```

