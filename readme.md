## Vidio.com HTML
Just for learning purpose

## How to add key - github

```
1. visit link: https://github.com/andrideng/vidio-dot-com-html/settings/keys
2. run command: ssh-keygen -t rsa -b 4096 -C "ninefoxlab@gmail.com"
    . give filename, example: nfl
3. cat nfl.pub
    . copy public key to deploy key (github)
    . tick allow access to write
    . save
4. run command: eval "$(ssh-agent -s)"
5. ssh-add nfl
```

## Step untuk push project ke github
```
1. git add .
2. git commit -m "pesan commit"
3. git push origin main
```