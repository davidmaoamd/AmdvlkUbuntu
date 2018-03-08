FROM centos
RUN  mkdir amdvlk
WORKDIR /amdvlk
RUN  yum install -y wget
RUN  wget https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
RUN  yum localinstall -y epel-release-latest-7.noarch.rpm
RUN  yum update -y
RUN  yum install -y gcc-c++ cmake3 python34 curl glibc-devel glibc-devel.i686 libstdc++-devel libstdc++-devel.i686 libxcb-devel libxcb-devel.i686 libX11-devel libX11-devel.i686 libxshmfence-devel libxshmfence-devel.i686 git make
RUN  git config --global user.email "david.mao@amd.com" && git config --global user.name "David Mao" && git config --global color.ui false
RUN  mkdir drivers
WORKDIR /amdvlk/drivers
