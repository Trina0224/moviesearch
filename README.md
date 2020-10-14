# Movie Search  

This is an exercise from Scrimba's Module11.  

##Importances:

1. Learned how to use API.  
2. Create .env and const xxx = process.env.REACT_APP_....(Remember to restart APP)  
3. ```JavaScript
{movies.filter(movie => movie.poster_path).map(movie => (
   <MovieCard movie={movie} key={movie.id} />
```

4. ```JavaScript
const url = `https://api.themoviedb.org/3/search/movie?api_key=${clientID}&language=en-US&query=${query}&page=1&include_adult=false`;
```

5. REACT, HOOK...  
6. Learned github-page with REACT  
https://dev.to/yuribenjamin/how-to-deploy-react-app-in-github-pages-2a1f  
Steps: a. npm i gh-pages  
       b. Edit package.json  
       "homepage": "https://trina0224.github.io/moviesearch/"  
       and
       "scripts": {//...
          "predeploy": "npm run build",
          "deploy": "gh-pages -d build"
        }  
        c. npm run deploy  

### Use git as usual. and npm run deploy to update new pages.
