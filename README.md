# Marian
Marian Install in Ubuntu 16
Step 1: git clone https://github.com/marian-nmt/marian
Step 2: cd marian
       mkdir build
       cd build
Step 3: sudo apt install cmake
Step 4: sudo apt-get install doxygen
        sudo apt-get install graphviz
Step 5: sudo apt-get install git cmake build-essential libboost-all-dev zlib1g-dev libprotobuf9v5 protobuf-compiler libprotobuf-dev openssl libssl-dev libgoogle-perftools-dev
Step 6: wget https://apt.repos.intel.com/intel-gpg-keys/GPG-PUB-KEY-INTEL-SW-PRODUCTS-2019.PUB
sudo apt-key add GPG-PUB-KEY-INTEL-SW-PRODUCTS-2019.PUB
sudo sh -c 'echo deb https://apt.repos.intel.com/mkl all main > /etc/apt/sources.list.d/intel-mkl.list'
sudo apt-get update
sudo apt-get install intel-mkl-64bit-2019.4
Step 7:  cmake ..
Step 8: make -j4
