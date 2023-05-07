### Step-1 Creating New Env
```
conda create -p env python==3.8 -y
```
for activating purpose
```
conda activate env/
```
OR
```
source activate ./env
```

To add the file
```
git add <file_name>
```
OR
```
git add .
git status
```
> Note : to ignore file or folder from git we can write name of file/folder in .gitignore file

To check  the git status
```
git log
```

To create a version/commit all changes by git
```
git commit -m 'message'
```

To send version/changes to github
```
git push origin main
```

To check remote url

```
git remote -v
```

to check which branch i am pushing my data 

```
git branch
```