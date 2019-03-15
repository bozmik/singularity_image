Bootstrap: docker
From: nfcore/base


%environment

    PATH=/opt/conda/envs/bozmik-singularity_image/bin:$PATH
    export PATH


%files
    environment.yml 

%post
    /opt/conda/bin/conda env create -f /environment.yml
    /opt/conda/bin/conda clean -a



