##### Git Practice Session

```
mkdir git-practice
cd git-practice
git init
ls -la
git add .
git status
echo "My name is [your-name]" > test_file.txt
cat test_file.txt
git add test_file.txt
```

try line below and you should see no change because the whole file has been added in the command above
```
git add -p
```

run below and you will see errors
```
git commit -s
```

to identify yourself
```
git config --global user.email "maxine.liu@accenture.com"
git config --global user.name "maxine.liu"
```

Now try this again
```
git commit -s
```
you will enter message mode, which is in vim
key `1` for insert mode
when you are done hit `ESC`
the type to save and quit `:wq`

:qa is to quit by the way

when you do this the first time, you will see errors
```
git push
```

git remote add <name of the branch you want to add>> <url or local path>
```
git remote add origin ./
git push origin
```

now git push again
```
git push
```

you will see an issue, do the one below
```
git push --set-upstream origin main
```

check out new branch
```
git checkout -b new-branch
```
now run
```
git branch
```

make changes to the test_file.txt

check using
```
git status
```

