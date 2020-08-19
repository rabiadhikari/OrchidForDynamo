# Orchid  
Orchid is a solution designed for use in the [Dynamo](http://dynamobim.org) environment. The solution is designed to support practical, technical, logical, and mathematical issues. In particular, is some solutions designed to handle nD-list issues. In addition, are solutions for applications included that not necessarily are Autodesk products.  
  
**Software environment:**  
Built for Dynamo 2.6.0 (Revit 2021), 2.3.0 (Revit 2020), and 2.0.4 (Revit 2019, 2018).  
Note: The version for Dynamo 1.3.4 (Revit 2019, 2018, 2017) is obsolete!  
  
**Orchid Samples:**  
In the [samples](Samples) folder are examples in using the Orchid package placed. For further informations read the [Readme](Samples/readme.md) file!    
  
**History/Change Log:**  
<a href="Orchid_260.md">Orchid 260</a>   
<a href="Orchid_230.md">Orchid 230</a>  
<a href="Orchid_200.md">Orchid 200</a>  
<a href="Orchid_130.md">Orchid 130</a> &nbsp;&nbsp;&nbsp; Note: the version is <b>obsolete</b>  

---
## Install or Update in Dynamo  
Use the executable installer in the **[Builds](Builds)** folder to install the Orchid package.  
  
Select the executable according to your dynamo version!  
OrchidforDynamo_260 &nbsp;&nbsp;&nbsp; (for the dynamo 2.6.x branch)  
OrchidforDynamo_230 &nbsp;&nbsp;&nbsp; (for the dynamo 2.3.x branch)  
OrchidforDynamo_200 &nbsp;&nbsp;&nbsp; (for the dynamo 2.0.x branch)  
OrchidforDynamo_130 &nbsp;&nbsp;&nbsp; (for the dynamo 1.3.x branch. Note: the version is obsolete)  
  
<span style="color:red">**REVIT AND DYNAMO MUST BE CLOSED DURING INSTALLATION!**</span>  
  
### Manually installation
The Orchid package may also be installed by manually copying files from the **[Zipped](Zipped)** folder. This is only recommendable for experienced users! To install/update this way, please unzip the zip-file of the chosen version into your dynamo package folder, into a folder named **Orchid**. Download may be handled either by downloading a single file, or by cloning or zipping the repository. The package folder path can be found in Dynamo via the menu item 'Settings' -> 'Manage Node and Package Paths'.  

Select the zip-file according to your dynamo version!  
Orchid_260_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.6.x branch)  
Orchid_230_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.3.x branch)  
Orchid_200_? &nbsp;&nbsp;&nbsp; (for the dynamo 2.0.x branch)  
Orchid_130_? &nbsp;&nbsp;&nbsp; (for the dynamo 1.3.x branch. Note: the version is obsolete)  

The individual version is avalible both for the sandbox version and for the version used Inside revit.  
?_Revit &nbsp;&nbsp;&nbsp; (the Revit version)  
?_Core &nbsp;&nbsp;&nbsp; (the Sandbox version)  
  
### Error handling
If Orchid dosnt work after installation, then try to see if you have one of these <a href="error.md">errors</a>!  
  
---
## Node description and organization  
Nodes are generally seen arranged in four node assemblies depending on the version. Two assemblies cover the Revit version and two assemblies cover the Core (Sandbox) version. Each of the two sets of assemblies has an assembly for base/standard nodes and an assembly for extensible nodes, mainly dropdown nodes. Besides these four, are assemblies covering icons for the nodes present.  
The nodes may also be used as textual scripted functions in code blocks and custom nodes, example using design script as the Dynamo functions.  
  
Inside Dynamo is the Orchid package nodes arranged into different main branches: Common, RevitFamily, RevitMaterial, RevitProject, About, and Applications. The last branch covers functions for external applications outside Revit. The first four branches covers functions to be used inside Revit. the About branch cover nodes for information about the Orchid package.  
  
Nodes in the four Revit driven branches can be recognized by their icon ribbon color:  
Common -> yellow &nbsp;|&nbsp; RevitFamily -> blue &nbsp;|&nbsp; RevitMaterial -> green &nbsp;|&nbsp; RevitProject -> red  
  
---
## License  
Copyright(c) 2014  
Erik Falck Jørgensen  
  
All content in this repository is part of the Orchid package.  
  
<a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/4.0/88x31.png" /></a>  
  
This work is licensed under the <a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">
Creative Commons Attribution-NoDerivatives 4.0 International License</a> (CC BY-ND 4.0).  
  
In short terms does the CC BY-ND license state: This license allows for redistribution, commercial and non-commercial, as long as it is passed along unchanged and in whole, with credit to the author.  
