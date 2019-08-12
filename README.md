# julia-notebook

To build and run with a shared Jupyter notebook folder:

```bash
docker build -t julia-notebook .
docker run -p 8888:8888 -v /Users/mortenhogh/work:/home/jovyan/work julia-notebook
```
