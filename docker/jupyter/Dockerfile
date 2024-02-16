FROM jupyter/minimal-notebook

COPY ./requirements.txt /tmp/requirements.txt
COPY ./work/.gitkeep /home/jovyan/work/.gitkeep
RUN pip install -r /tmp/requirements.txt
