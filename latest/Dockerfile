FROM ubuntu:20.04
LABEL maintainer "Samuel Jacobs <samjacobs@scimulate.com>"

RUN apt-get update && apt-get install -y software-properties-common
RUN apt-add-repository -y ppa:elmer-csc-ubuntu/elmer-csc-ppa
RUN apt-get update && apt-get install -y elmerfem-csc-eg

RUN DEBIAN_FRONTEND=noninteractive apt-get install -y liboce-modeling-dev \
	liboce-foundation-dev \
	#qtscript5-dev \
	libglu1 \
	libqt5script5 \
	libqt5widgets5 \
	libqt5core5a \
	libqt5gui5 \
	libqt5help5 \
	libqt5opengl5 \
	libqt5xml5 \
	#libqt5opengl5-dev \
	#libqt5svg5-dev \
	libvtk6.3 \
	#libvtk6-dev \
	libvtk6.3-qt
	#libvtk6-qt-dev 

CMD ElmerGUI

#    
#    libqt5printsupport5 \
#    libqt5xml5 \
#    libgl1-mesa-glx libgl1-mesa-dev libglu1-mesa-dev freeglut3-dev libosmesa6 libosmesa6-dev #libgles2-mesa-dev curl imagemagick

#COPY SALOME-9.9.0.tar.gz /tmp
#WORKDIR /tmp
#RUN tar xzvf SALOME-9.9.0.tar.gz

#RUN apt-get update && DEBIAN_FRONTEND=noninteractive TZ="America/New York" apt-get install -y \
#    python3 \
#    libglu1 \
#    wget \
#    libopengl0 \
#    libfontconfig1 \
#    libsm6 \
#    dbus-x11 \
#    libglib2.0-dev \
#    libpangoft2-1.0-0 \
#    libpangocairo-1.0-0 \
#    libgdk-pixbuf2.0-0 \
#    libpango1.0-dev \
#    libegl1 \
#    xterm \
#    netcat \

# CMD /tmp/SALOME-9.9.0/mesa_salome 
