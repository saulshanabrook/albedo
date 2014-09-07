# Albedo Experirement
hey i did an experiment and then I had data and why not use awesome python
for plotting?
## running ipython notebook will all them goodies on DOCKER!

Install docker-osx first, then... 

```bash
docker run -p 8888:8888 -t --rm -e "PASSWORD=MakeAPassword" -v $(pwd):/notebooks/ ipython/scipyserver
open 'https://localdocker:8888'
```

magic! file system syncing! awesomeness!
