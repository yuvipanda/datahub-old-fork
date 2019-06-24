FROM gcr.io/ucb-datahub-2018/primary-user-image:d003281

USER root

RUN git config --system user.email 'jupyterhub-jovyan@example.com'
RUN git config --system user.name 'JupyterHub Jovyan'

USER ${NB_USER}
