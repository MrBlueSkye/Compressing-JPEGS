# Compressing-JPEGS

  INSTALL JPEGOPTIM
sudo apt-get update
sudo apt-get install jpegoptim

  GRAB THE LATEST VERSION
cd /tmp
wget http://www.kokkonen.net/tjko/src/jpegoptim-1.4.4.tar.gz
tar -xvf jpegoptim*
cd jpegoptim*
./configure --prefix=/usr
make
sudo make install

  CHECK VERSION
jpegoptim -V

  COMPRESS IMAGE
jpegoptim example.jpeg

