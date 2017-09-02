FROM jupyter/datascience-notebook:cf6258237ff9
ARG JUPYTERHUB_VERSION=0.7.2
RUN pip install --no-cache \
    jupyterhub==$JUPYTERHUB_VERSION
RUN pip install --no-cache obspy
