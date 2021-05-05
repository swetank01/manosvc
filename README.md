# nanoSVC



## Architecture

              |----->   Post Service   ----->   Posts Feature
              |
REACT APP ----
              |
              |-----> Comments Service ----->   Comments Feature


## Framework
- REACT 
- EXPRESS


# Project Setup:

1. Client (Frontend) 
 npx create-react-app client


2. Post (API)
```
mkdir posts && cd posts 
npm init && npm install express cors axios nodemon
```

3. Comments (API)
```
mkdir comments && cd comments
npm init && npm install express cors axios nodemon
```