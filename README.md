# HTS
High Throughput Streaming shim to install multiple UUTS in HTS

## Create a fresh user
mkdir ~/bin
make sure ~/bin is in the user's path

mkdir PROJECTS

## Download cs-studio
## Download kst
## Install AFHBA404
https://github.com/D-TACQ/AFHBA404

(
cd PROJECTS
git clone https://github.com/D-TACQ/AFHBA404.git
)
## Install HAPI
(
pip install acq400_hapi
mkdir -p PROJECTS/ACQ400/HAPI
cd PROJECTS/ACQ400/HAPI
git clone https://github.com/D-TACQ/acq400_hapi.git
)
## Install ACQ400CSS
(
cd PROJECTS
git clone https://github.com/D-TACQ/ACQ400CSS
)

## Install HTS
(
cd PROJECTS
git clone https://github.com/D-TACQ/HTS.git
### Customise: acq2106_hts.sh
Check the paths in this file before deploy
run sudo ./make.install
)


