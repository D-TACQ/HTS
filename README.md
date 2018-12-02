# HTS
High Throughput Streaming shim to install multiple UUTS in HTS

## Create a fresh user
```bash
mkdir ~/bin
### make sure ~/bin is in the user's path
### make sure the user has sudo with no password required

mkdir PROJECTS
```
## Download cs-studio
## Download kst
## Install AFHBA404
https://github.com/D-TACQ/AFHBA404
```bash
(
cd PROJECTS
git clone https://github.com/D-TACQ/AFHBA404
)
```
## Install HAPI
```bash
(
pip install acq400_hapi
mkdir -p PROJECTS/ACQ400/HAPI
cd PROJECTS/ACQ400/HAPI
git clone https://github.com/D-TACQ/acq400_hapi
)
```
## Install ACQ400CSS
```bash
(
cd PROJECTS
git clone https://github.com/D-TACQ/ACQ400CSS
)
```
## Install HTS
```
(
cd PROJECTS
git clone https://github.com/D-TACQ/HTS
### Customise: acq2106_hts.sh
Check the paths in this file before deploy
cd HTS
run sudo ./make.install
)
```



