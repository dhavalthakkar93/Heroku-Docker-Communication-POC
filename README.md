# Heroku-Docker-Communication 

This proof of concept app is intended to demonstrate SSH Tunneling for Docker Containers in Heroku Private Spaces.  

First clone the code

```
git clone https://github.com/dhavalthakkar93/Heroku-Docker-Communication-POC
```

Create Heroku App

```
heroku create

Creating app... done, ⬢ still-reaches-17754
https://still-reaches-17754.herokuapp.com/ | https://git.heroku.com/still-reaches-17754.git
```

# Build Images 

- `docker build -t back backend-container/.`
- `docker build -t front frontend-container/.`
- `docker build -t web web-container-nginx/.`
- `docker build -t debug .`







