FROM homeassistant/home-assistant
MAINTAINER sosandstrom <s.o.sandstrom@gmail.com>

# Update
RUN apt-get update
RUN apt-get install -y python 
RUN apt-get install -y python-pip
 
# Install app dependencies
RUN pip install --upgrade pip

RUN pip install pyserial
RUN pip install python-datetime
RUN pip install pyserial_asyncio
