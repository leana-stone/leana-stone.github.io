

# Daily Git commit process

```
git add .
git commit -m "commit message"
git push origin master
```

# Resolving conflicts

If something goes wrong, and you see this:
```
 ! [rejected]        master -> master (non-fast-forward)
```

What you need to do is:
```
git pull origin master
```