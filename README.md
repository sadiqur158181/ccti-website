# CCTI Website (static)

## Run on localhost
    python3 -m http.server 8000
Open http://localhost:8000

## Push to GitHub
    git init
    git add .
    git commit -m "CCTI website"
    git branch -M main
    git remote add origin https://github.com/<username>/<repo>.git
    git push -u origin main
Repo Settings > Pages > Deploy from branch > main / (root).

## Custom domain
DNS: CNAME www -> <username>.github.io ; A records @ -> 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
Notice text: edit between NOTICE START / NOTICE END in index.html.
