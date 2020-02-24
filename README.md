# 2020-02-24 Git Basics

- `init`: make current folder a git repository
- `status`: see the status of current repository
- `add`: put files into the index (staging area)
- `commit`: commit the files from staging area
  - `commit -m ""`: commit files from staging area with commnet in quotes
- `diff`: look at difference between 2 commit states
- `log`: look at commit messages
- `log --oneline`: only get the oneline view
- `checkout <hash> <file>`: restore a single file from

- `index/staging area`: add files to staging area to be committed later

## Remotes

- `remote`: anywhere you didn't `init` or `clone`
- `remote add origin`
- `push`: send code to our remote
- `pull`: get code from our remote (does a 'fetch' and `merge`)
