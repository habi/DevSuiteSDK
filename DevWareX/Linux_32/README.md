# Installation under Scientific Linux 6.

To make the installation work, one has to install Python3, which should be
possible with the the following sequence of commands (based on
[this answer on Stack Overflow](http://stackoverflow.com/a/8112006/323100).

  cd /scratch/tmp
  wget http://www.python.org/ftp/python/3.3.2/Python-3.3.2.tar.bz2
  tar -xjf Python-3.3.2.tar.bz2
  cd Python-3.3.2
  ./configure --prefix=/opt/python3 --enable-shared
  make
  make test
  su # to become SuperUser
  make install
