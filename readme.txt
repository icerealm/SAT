## start command
This analysis uses data science-notebook which includes may lib in its container

## run docker jupyter instant like example below
docker run -p 12222:8888 -e JUPYTER_LAB_ENABLE=yes -v "/Users/jakkritsittiwerapong/Workspace/PythonWorkspace":/home/jovyan/work jupyter/datascience-notebook:latest
