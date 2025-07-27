# Movie Covers
Movie covers project.

### ID
Use the IMDb movie ID without the initial "tt". For greater compability in future, remove left zeros (0121765 -> 121765).

### How to use links
Use this URL pattern for default covers (you'll have to implement the automation yourself):
```python
    https://raw.githubusercontent.com/st-alves/movie-covers-${decade}/refs/heads/main/${type}/${movie_id}.jpg"
```

Example: 
<br>```https://raw.githubusercontent.com/st-alves/movie-covers-2000/refs/heads/main/default/121765.jpg```

Only "default" is available for ```${type}``` for now.

### Decades
[2000 (2001-2010)](https://github.com/st-alves/movie-covers-2000)
<br>[1990 (1991-2000)](https://github.com/st-alves/movie-covers-1990)
