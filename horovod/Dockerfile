FROM uber/horovod:0.15.2-tf1.12.0-torch1.0.0-py3.5

RUN apt-get -y update
RUN apt-get install -y apt-utils

RUN pip install pystan

RUN pip install docopt hdfs numpy scipy sklearn pandas mpi4py gitpython torchnet pydot tabulate jupyter matplotlib qgrid graphviz ipywidgets bqplot pyyaml pytest xlsxwriter opencv-python  fbprophet

RUN apt-get install -y \
  libsm-dev \
  libxrender-dev \
  libxext-dev \
  && rm -rf /var/lib/apt/lists/*

CMD jupyter notebook --no-browser --ip=0.0.0.0 --allow-root --NotebookApp.token= --NotebookApp.allow_origin='*'
