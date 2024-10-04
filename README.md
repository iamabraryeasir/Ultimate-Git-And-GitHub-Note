# Ultimate Git and Github Complete Note.

### 1. Initializing a new local git repo.

```bash
git init
```

### 2. Adding files and folders to the repo.

```bash
git add fileName.fileExtension folderName/
```

for adding all.

```bash
git add .
```

### 3. Committing new changes.

```bash
git commit -m "commit massage here"
```

### 4. Renaming the master branch to main.

```bash
git branch -M main
```

### 5. Setting up the remote origin or GitHub repo to upload code.

```bash
git remote add origin https://github.com/<userName>/<remoteRepoName>.git
```

### 6. Pushing the code.

For the first time to set the default branch to main.

```bash
git push -u origin main
```

After first time.

```bash
git push
```

### 7. Every time we do a change in codebase.

Every time we do any kind of change in the code base we need to repeat 3 steps.

1. Adding the files.
2. Committing the changes.
3. Pushing the Local Changes.
