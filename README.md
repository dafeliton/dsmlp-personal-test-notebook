# My Personal Test Notebook
Notebook created for testing purposes. 

## Notable Events
Users may get a ```buildx failed with: ERROR: denied: permission_denied: write_package``` error when first creating the docker image from the provided template. This may be resolved by clicking on the package under the package tab, then navigating to ```Package Settings``` and finally granting this repository admin or write privileges.
apt-get was unable to locate the ```btop``` package, despite it being present on a normal Ubuntu install. Likely a simple fix, but going to investigate why this particular package was not found after a successful compile.

Manually created user ```dominic``` with built-in ```useradd``` command in Ubuntu. However, running pip with this newly created user did not work, and defaulted to jovlan user. Attempting to use ```$NB_UID``` instead; unsure what this does 
