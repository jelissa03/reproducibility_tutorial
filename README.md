# reproducibility_tutorial
This is my first try at the tutorial
#clone to repo   
    2  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    3  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    4  conda
    5  ln -s /opt/conda/pkgs/*/bin/* /bin
    6  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
    7  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
    8  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
    9  python3 -m pip install bash_kernel
   10  git clone https://github.com/jelissa03/reproducibility_tutorial.git
   11  apt-get update
   12  sudo apt install -y python3-pip
   13  python3 -m pip install bash_kernel
   14  python3 pip install ipykernel
   15  python3 -m pip install ipykernel
   16  python3 -m bash_kernel.install
   17  In -s/opt/conda/bin/*/bin
   18  in -s/opt/conda/bin/*/bin
   19  in -s/opt/conda/bin/*/bin
   20  in -s/opt/conda/bin/* /bin
   21  ln -s /opt/conda/bin/* /bin
   22  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   23  git clone https://github.com/jelissa03/reproducibility_tutorial.git
   24  cd /scratch
   25  ls
   26  cd reproducibility_tutorial/
   27  ls
   28  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   29  cd reproducibility_tutorial/
   30  cd /scratch
   31  ls
   32  jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility_tutorial/'
   33  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   34  snakemake --version
   35  apt install snakemake
   36  snakemake --version
   37  ln -s /opt/conda/bin/* /bin
   38  snakemake --version
   39  sudo apt-get update
   40  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   41  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   42  sudo add-apt-repository \
   43  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
   44  sudo apt-get update
   45  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   46  docker run hello-world
   47  cd /scratch/reproducibility_tutorial/
   48  history >>README.md
