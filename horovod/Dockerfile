FROM uber/horovod:0.15.2-tf1.12.0-torch1.0.0-py3.5

RUN apt-get -y install libglib2.0
RUN apt-get -y install libsm-dev
RUN apt-get -y install libxrender-dev
RUN apt-get -y install libxext-dev
# Install TensorFlow, Keras and PyTorch

RUN curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
RUN python get-pip.py --force-reinstall

RUN pip install docopt hdfs numpy scipy sklearn pandas mpi4py gitpython torchnet pydot tabulate jupyter matplotlib qgrid graphviz ipywidgets bqplot pyyaml pytest xlsxwriter 
RUN pip install opencv-python

WORKDIR "/examples"
