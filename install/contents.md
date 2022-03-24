[env](/download/ci-environment.yml)

1. Download en installeer Anaconda
https://www.anaconda.com/products/individual

2. Windows: open Anaconda promt

(The next step is only needed in windows)
conda install -c menpo wget

wget https://ci.mprog.nl/install/download/ci-environment.yml
conda env create -f ci-environment.yml
rm ci-environment.yml
