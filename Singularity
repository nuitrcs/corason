Bootstrap: docker
From: nselem/corason:latest

%environment
	export PATH=$PATH:/opt/corason/CORASON

%post
	mv /root/corason /opt

%runscript
	exec /opt/corason/CORASON/corason.pl "$@"
