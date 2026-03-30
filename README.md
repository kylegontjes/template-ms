# template-ms
Template for reproducible manuscript directories

# Implementation your project's manuscript repository
Use the following steps to implement this in your work:

0. Download github command line interface (https://cli.github.com/)

```
brew install gh
```

1. Clone the repository

```
git clone https://github.com/kylegontjes/template-ms.git
```

2. Remove the git file 

```
rm -rf template-ms/.git
```

3. Change directory name 

```
mv template-ms [repository-name]
```

4. Move into directory

```
cd [repository-name]
```

5. Initialize repository

```
git init
git branch -M master
```

6. Add content
```
git add .
```

7. Commit repository
```
git commit -m 'initialize'
```

8. Authenticate & create repository on great lakes
```
gh auth login
gh repo ccreate [repository-name] --private --source=. --remote=origin --push
gh rep edit --default-branch master
```

9. Edit README.md with relevant information