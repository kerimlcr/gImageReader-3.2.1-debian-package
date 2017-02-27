# gImageReader-3.2.1-debian-package
This package belongs to version 3.2.1

#If you want to rebuild
>git clone git@github.com:kerimlcr/gImageReader-3.2.1-debian-package.git

>cd gImageReader-3.2.1-debian-package/

>rm gimagereader_3.2.1-1_amd64.deb

>cd gimagereader-3.2.1/

>sudo mk-build-deps -r --install  debian/control

>debuild -us -uc

