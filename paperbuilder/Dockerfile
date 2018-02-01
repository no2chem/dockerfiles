FROM debian:testing

RUN apt-get update && apt-get install -y \
  wget \
  git \
  make \
  gnuplot \
  texlive-full && \
  curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash - &&\
  apt-get install -y nodejs && \
  apt-get install -y build-essential && \
  apt-get --purge remove -y .\*-doc$ && \
  apt-get clean -y

