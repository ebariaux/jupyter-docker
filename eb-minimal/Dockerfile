FROM jupyter/minimal-notebook
LABEL org.opencontainers.image.authors="Eric Bariaux"
USER jovyan
RUN conda install --yes --channel anaconda beautifulsoup4 && conda clean -tipsy
