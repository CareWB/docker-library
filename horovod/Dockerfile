FROM uber/horovod:0.15.2-tf1.12.0-torch1.0.0-py3.5

RUN apt-get -y update
RUN apt-get install -y apt-utils

RUN pip install docopt hdfs numpy scipy sklearn pandas mpi4py gitpython torchnet pydot tabulate jupyter matplotlib qgrid graphviz ipywidgets bqplot pyyaml pytest xlsxwriter opencv-python pystan fbprophet

RUN apt-get install -y \
  libsm-dev \
  libxrender-dev \
  libxext-dev

WORKDIR "/examples"
