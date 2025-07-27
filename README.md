# Movie Covers
Movie covers project.

## ID
Use the IMDb movie ID without the initial "tt". For greater compability in the future, remove left zeros (0107048 -> 107048).

## Type Images and How to Use Links
For all types you'll have to implement the automation yourself.

#### Letterboxd
Use this URL pattern for Letterboxd default covers:
```python
    https://raw.githubusercontent.com/st-alves/movie-covers-${decade}/refs/heads/main/movies/${movie_id}/letterboxd.jpg"
```

Example: 
<br>```https://raw.githubusercontent.com/st-alves/movie-covers-1990/refs/heads/main/movies/107048/letterboxd.jpg```

Letterboxd image size: 350 x 525 px

#### DVD
For now, only one variant cover is available. US cover.

Front cover:
Use this URL pattern for default covers:
```python
    https://raw.githubusercontent.com/st-alves/movie-covers-${decade}/refs/heads/main/movies/${movie_id}/dvd/front.jpg"
```
Example: 
<br>```https://raw.githubusercontent.com/st-alves/movie-covers-1990/refs/heads/main/movies/107048/dvd/front.jpg```


Back cover:
Use this URL pattern for default covers:
```python
    https://raw.githubusercontent.com/st-alves/movie-covers-${decade}/refs/heads/main/movies/${movie_id}/dvd/back.jpg"
```
Example: 
<br>```https://raw.githubusercontent.com/st-alves/movie-covers-1990/refs/heads/main/movies/107048/dvd/back.jpg```

DVD image size (front and back): 300 x 415 px

### Decades
[2020 (2021-2030)](#)
<br>[2010 (2011-2020)](#)
<br>[2000 (2001-2010)](https://github.com/st-alves/movie-covers-2000)
<br>[1990 (1991-2000)](https://github.com/st-alves/movie-covers-1990)
<br>[1980 (1981-1990)](https://github.com/st-alves/movie-covers-1980)
