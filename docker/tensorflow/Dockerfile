FROM tensorflow/tensorflow:2.3.1-jupyter

RUN pip3 install --upgrade pip setuptools
RUN pip3 install matplotlib jupyterlab scipy
RUN jupyter serverextension enable --py jupyterlab

ENTRYPOINT ["jupyter-lab"]

CMD ["--ip=0.0.0.0", "--port=8888", "--allow-root", "--NotebookApp.token=''"]