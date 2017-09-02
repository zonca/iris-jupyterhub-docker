FROM jupyter/datascience-notebook:cf6258237ff9
ARG JUPYTERHUB_VERSION=0.7.2
RUN pip install --no-cache \
    jupyterhub==$JUPYTERHUB_VERSION
RUN pip install --no-cache obspy
RUN wget https://cran.r-project.org/src/contrib/seismicRoll_1.1.2.tar.gz && /opt/conda/bin/R CMD INSTALL seismicRoll_1.1.2.tar.gz
RUN wget https://cran.r-project.org/src/contrib/IRISSeismic_1.4.6.tar.gz && /opt/conda/bin/R CMD INSTALL IRISSeismic_1.4.6.tar.gz
RUN wget https://cran.r-project.org/src/contrib/IRISMustangMetrics_2.0.8.tar.gz && /opt/conda/bin/R CMD INSTALL IRISMustangMetrics_2.0.8.tar.gz
