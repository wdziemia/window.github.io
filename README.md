# Blog
Powered by [Ghost](http://ghost.org) and [Buster](https://github.com/manthansharma/buster/).


# Local Dev

1. Start Ghost in /ghost directory via `npm start`
2. Login to `http://localhost:2368/ghost`in Chrome 
3. Apply Changes
4. Run `buster generate` to export a static site into `/static` dir
    ```
    buster.py generate --web-url="http://wdziemia.github.io"
    ```
5. Commit and Push to base branch
