# Energy HPC 2022 - From Zero to Devtio

Workshop Thursday, 3rd March 2022 (09:00 – 12:00 CST): 

* Presented by: Dr. Rhodri Nelson, Imperial College London
* Conference website: https://energyhpc.rice.edu/

[Devito](https://www.devitoproject.org/) is a domain specific language (DSL) and compiler for finite difference schemes. This workshop will provide attendees with an introduction to the core elements of the Devito DSL. A breakdown of the agenda is as follows:
* Introduction to the DSL - Expressing PDEs in Devito
* Introduction to Devito operators
* Building wave-propagators
* Full waveform inversion with Devito

For attendees who would like a more hands on experience with Devito, during the workshop and for a period afterwards we will provide access to Microsoft Azure VMs with Devito and JupyterHub. Alternatively, participants may wish to install Devito on their local machine using the install [instructions provided](https://www.devitoproject.org/devito/download.html).

## Workshop prerequisites:
* Basic Python programming knowledge
* Basic knowledge of finite differences
* A Github account for authentication (if you wish to access the JupyterHub)

To access the workshop material:
* If using the Azure VM's provided:
    * Go to: https://devitocodes.southcentralus.cloudapp.azure.com/
    * Login using your Github credentials
    * Navigate to ```transform2020/workshop_notebooks``` and enjoy!
* If using your own device:
    * After installing devito, in a separate directory run `git clone https://github.com/devitocodes/Energy-HPC-2022.git`
    * Navigate to the ```workshop_notebooks``` in the cloned repository, then with the `Devito` environment enabled run `jupyter notebook` followed by the name of the tutorial you wish to open.
