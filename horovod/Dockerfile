FROM uber/horovod:0.15.2-tf1.12.0-torch1.0.0-py3.5

RUN apt-get update
RUN apt-get -y install libopencv-dev
RUN apt-get -y install build-essential
RUN apt-get -y install checkinstall
RUN apt-get -y install cmake
RUN apt-get -y install pkg-config
RUN apt-get -y install yasm
RUN apt-get -y install libtiff4-dev
RUN apt-get -y install libjpeg-dev
RUN apt-get -y install libjasper-dev
RUN apt-get -y install libavcodec-dev
RUN apt-get -y install libavformat-dev
RUN apt-get -y install libswscale-dev
RUN apt-get -y install libdc1394-22-dev
RUN apt-get -y install libxine-dev
RUN apt-get -y install libgstreamer0.10-dev
RUN apt-get -y install libgstreamer-plugins-base0.10-dev
RUN apt-get -y install libv4l-dev
RUN apt-get -y install python-dev
RUN apt-get -y install python-numpy
RUN apt-get -y install libtbb-dev
RUN apt-get -y install libqt4-dev
RUN apt-get -y install libgtk2.0-dev
RUN apt-get -y install libfaac-dev
RUN apt-get -y install libmp3lame-dev
RUN apt-get -y install libopencore-amrnb-dev
RUN apt-get -y install libopencore-amrwb-dev
RUN apt-get -y install libtheora-dev
RUN apt-get -y install libvorbis-dev
RUN apt-get -y install libxvidcore-dev
RUN apt-get -y install x264
RUN apt-get -y install v4l-utils
RUN apt-get -y install ffmpeg
RUN apt-get -y install unzip
# Install TensorFlow, Keras and PyTorch
RUN pip install docopt hdfs numpy scipy sklearn pandas mpi4py gitpython torchnet pydot tabulate jupyter matplotlib qgrid graphviz ipywidgets bqplot pyyaml pytest xlsxwriter

WORKDIR "/examples"
