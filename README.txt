To run the notebooks, you can either download the CarbonData112021.zip and run it in your local python environment (using the environment.yml), or you can use the JupyterHub from the BlueCloud VRE.

To do so :

    - Open a JupyterLab instance using the JupyterHub tab in the the VRE
      The notebooks cannott run inside the demonstrator shared folders, so you will have to copy the archive inside your Jupyter session :
    - Open a Terminal inside the JupyterLab
    - Copy the archive : cp workspace/VREFolders/MarineEnvironmentalIndicators/notebooks/OceanCarbon/CarbonData122021.zip .
    - Change permission : chmod 777 CarbonData122021.zip
    - Unzip it : unzip CarbonData122021.zip

You can then play with the notebooks.

NOTE: if in the Carbon_data_from_ERDDAP.ipnb notebook cell 15 (where it retrieves data) times out, just re-run it again.

