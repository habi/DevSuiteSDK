# Installation under Scientific Linux 6.

To make the installation work, one has to install Python3, which should be
possible with the the following sequence of commands (based on
[this Stack Overflow answer](http://stackoverflow.com/a/8112006/323100)).

	cd /scratch/tmp
	wget http://www.python.org/ftp/python/3.3.2/Python-3.3.2.tar.bz2
	tar -xjf Python-3.3.2.tar.bz2
	cd Python-3.3.2
	./configure --prefix=/opt/python3 --enable-shared
	make
	make test
	su # switch to SuperUser
	make install
	# symlink libraries (still as SuperUser)
	ln -s /opt/python3/lib/libpython3.3m.so /usr/lib/libpython3.3.so

I also added the Python3-directories to the path, see
[here](https://github.com/habi/dotfiles/blob/master/.bashrc).
Unfortunately, this doesn't solve the problem that I cannot start neither
'Devware.exe` nor `python3`, both complain about
> python3: error while loading shared libraries: libpython3.3m.so.1.0: cannot
>  open shared object file: No such file or directory

