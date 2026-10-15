FROM quay.io/jupyter/datascience-notebook:2024-04-22

RUN pip install --no-cache-dir bokeh neo4j pyvis && \
    fix-permissions /home/jovyan

ENV NOTEBOOK_ARGS="--ServerApp.allow_origin='*' --ServerApp.token='' --ServerApp.password=''"
