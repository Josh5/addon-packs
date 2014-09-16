addon-packs
===========

Meta-data repository for the Add-on Pack Installer


## Introduction
This repository contains meta data for the TinyHTPC Add-on Pack Installer to find and download pre-packaged / configured Kodi add-ons.



## How to add to the repository
1. Create a backup of your current addon configuration saving the folders in this structure:    

    addons
    >  |_   #### Your addons ####    

    userdata   
    >  |_   addon_data    
    >>  |_   #### Your addon settings ####      

2. Create a fork of this repo and add your add-on pack to the file "packs.txt" in this format:

    **Name your Add-on Pack:**   
    *name="###"*    

    **Link to your pack (must be a direct download):**   
    *url="https://###"*    

    **Add link to an icon for your pack. Make it something meaningful:**   
    *img="http://###.png"*    

    **Add link of a background image (try to keep the file size small):**   
    *fanart="http://###.jpg"*    

    **Give a brief description of your pack. (less than 70 characters):**   
    *description="###"*    

3. Open a pull request



Alternately you can just PM me the above details in our [forum](http://tinyhtpc.co.nz/forum/ucp.php?i=pm&mode=compose&u=2)

>> **Josh.5** - TinyHTPC    
