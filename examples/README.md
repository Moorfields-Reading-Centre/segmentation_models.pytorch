For Moorfields Use:
nvidia-docker run -it --rm -m=4g --shm-size=8g --user $(id -u):$(id -g) -p 16006:8888 -v ~:/home/zhangg -p 16007:8888 msga jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token=gongyu01 --notebook-dir=/
