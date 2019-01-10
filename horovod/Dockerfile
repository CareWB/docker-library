FROM uber/horovod:0.15.2-tf1.12.0-torch1.0.0-py3.5

apt-get -y install libopencv-dev
apt-get -y install build-essential
apt-get -y install checkinstall
apt-get -y install cmake
apt-get -y install pkg-config
apt-get -y install yasm
apt-get -y install libtiff4-dev
apt-get -y install libjpeg-dev
apt-get -y install libjasper-dev
apt-get -y install libavcodec-dev
apt-get -y install libavformat-dev
apt-get -y install libswscale-dev
apt-get -y install libdc1394-22-dev
apt-get -y install libxine-dev
apt-get -y install libgstreamer0.10-dev
apt-get -y install libgstreamer-plugins-base0.10-dev
apt-get -y install libv4l-dev
apt-get -y install python-dev
apt-get -y install python-numpy
apt-get -y install libtbb-dev
apt-get -y install libqt4-dev
apt-get -y install libgtk2.0-dev
apt-get -y install libfaac-dev
apt-get -y install libmp3lame-dev
apt-get -y install libopencore-amrnb-dev
apt-get -y install libopencore-amrwb-dev
apt-get -y install libtheora-dev
apt-get -y install libvorbis-dev
apt-get -y install libxvidcore-dev
apt-get -y install x264
apt-get -y install v4l-utils
apt-get -y install ffmpeg
apt-get -y install unzip
# Install TensorFlow, Keras and PyTorch
RUN pip install docopt hdfs numpy scipy sklearn pandas mpi4py gitpython torchnet pydot tabulate jupyter matplotlib qgrid graphviz ipywidgets bqplot pyyaml pytest xlsxwriter

WORKDIR "/examples"
