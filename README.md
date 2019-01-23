# TX2-installation-and-Software-deployment


# FLashing jetson 
using nvidia JETPACK with a ubuntu host os (not a virtual os) 
  https://developer.nvidia.com/embedded/jetpack

ran into issue to where cuda gpg key was not available. Therefore 



and installing Software on TX2


# installing git
# install pip
# installing aws 
aws configure 
  access key 
  secret access key
  
 # install cmake
  # CMake 3.11+
ver="3.11"
build="0"
url="https://cmake.org/files/v${ver}/cmake-${ver}.${build}.tar.gz"
wget ${url}
tar -xzvf cmake-${ver}.${build}.tar.gz
cd cmake-${ver}.${build}
./bootstrap
make -j4
make install
cd  ${INSTALL_ROOT}
rm -rf cmake*
