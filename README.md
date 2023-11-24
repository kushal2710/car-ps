# Caravel User Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

| :exclamation: Important Note            |
|-----------------------------------------|

## Please fill in your project documentation in this README.md file 

Refer to [README](docs/source/index.rst#section-quickstart) for a quickstart of how to use caravel_user_project

Refer to [README](docs/source/index.rst) for this sample project documentation. 

Refer to the following [readthedocs](https://caravel-sim-infrastructure.readthedocs.io/en/latest/index.html) for how to add cocotb tests to your project. 

## Cloning and setup!!
- Run the following commands 
```
git clone https://github.com/kushal2710/car-ps.git
mkdir ~/asic
export OPENLANE_ROOT=~/asic/openlane
export PDK_ROOT=~/asic/pdk
cd Reverse_Vector/
make setup

ls $PDK_ROOT
ls $OPENLANE_ROOT
ls openlane/
make user_proj_example
ls gds/
klayout gds/user_proj_example.gds
```

I am getting this error

![WhatsApp Image 2023-11-24 at 22 18 00](https://github.com/kushal2710/car-ps/assets/115935208/98a7c5d5-9d3f-4c5b-b3f2-e061829cb8a9)

- Now create a project on the Efabless platform, and then upload your design
- Creat ssh key

![Screenshot from 2023-11-24 20-54-53](https://github.com/kushal2710/car-ps/assets/115935208/04865788-655f-4e5d-a0d7-88dfdabeb370)

![Screenshot from 2023-11-24 20-58-28](https://github.com/kushal2710/car-ps/assets/115935208/e1c6c2d1-9ee5-4547-baf9-221831848daa)

- Associate the generated SSH keys with your account.

![Screenshot from 2023-11-24 22-12-15](https://github.com/kushal2710/car-ps/assets/115935208/5e067214-9687-44f3-b87e-ca4db7d71530)
-  Then continue with the setup process
- To submit precheck and tapeout jobs on the Efabless platform.

![Screenshot from 2023-11-24 22-11-17](https://github.com/kushal2710/car-ps/assets/115935208/afbab407-8f86-4ce1-b24d-1a955be1b994)








