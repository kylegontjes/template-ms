# template-ms
Template for reproducible manuscript directories

# Implementation your project's manuscript repository
Use the following steps to implement this in your work:

1. Clone the repository

```
git clone https://github.com/kylegontjes/template-ms.git
```

2. Enter into the directory

```
cd template-ms
```

3. Remove the git file

```
rm -rf .git
```

4. Initialize a new repository

```
git init
```

5. Add new remote repository

```
git remote add origin https://github.com/[username]/[repository-name]-ms.git
```

6. Push to GitHub

```
git add . 

git commit -m 'Initialize manuscript repository'

git push -u origin main
```