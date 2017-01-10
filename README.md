# WARNING
This repository is not ready yet to be used! We are still uploading and preparing files.
------------------
(Installation see below)

# SAxVCxLC
Adds the GTA Vice City and Liberty City maps into GTA San Andreas. GTA SA remains fully playable and modable.
See: http://gtaforums.com/topic/813938-saxvcxlc-vc-and-lc-in-san-andreas/

## Main Author:
PlatinumSerb

## Credits/Special Thanks:
* fastman92 - Limit Adjuster, Debugging 
* goodidea82 - Infrastructure, Installation
* Swoorup - PathMover, COLRenamer(old program :p), Conversion of LC and VC paths
* GTA: Liberty City Team - Use of GTA:LC map
* OpenVice(NTAuthority) - Use of Vice City map
* Silent - ASI Loader and Extended Gangs ASI
* _F_ - use of GTA VC cars Converted to SA
* CJ2000 - use of GTA VC and III vehicles
* artginPL - ENEX/Interior Markers
* Kam - Kam's Max Scripts 
* Deniska - 3dmax script pack
* x-men - 3dmax scripts/IMG Manager
* CLEO Team
* ThirteenAG - Project2dfx
* Beckerbrasil - testing/bug reporting
* Junior_Djjr - Overhaul of CLEO scripts
* ZAZ - some of his CLEO mods were crucial for debugging/getting around the map.
* X-Seti - original concept of combining GTA III era cities so he deserves a shout out :p

Thanks Rock* Games

# Installation
1. Download the project as a Zip file from https://github.com/goodidea82/SAxVCxLC. Extract the Zip file.
2. Click on Install.bat and follow the instructions there. Eventually additional files (radio music) will be downloaded.

# Remarks for developers
## Principles
* Original game must remain fully playable and modable (backwards compatible with older mods)
* Modifications should be published as external mods. This helps to advertise SAxVCxLC on other websites and everybody can customize it as they want.

## GitHub
* Practice Git and GitHub on a hello-world project first.
* To move and rename files/folders install GIT on your computer rather than using the web interface. Some info: https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf
* Git configuration on windows: line endings: Checkout as-is, commit as-is (we use windows line endings)
* Do not upload big files on GitHub. The purpuse of Git is to keep track of many small files. Maxium allowed project size on GitHub is 1000 GB. 
* Let us not use Git Large File Storage (LFS), because all developers will have to install this (making it harder for new developers to start). Take a look in toolsForInstallation\Music.bat how to download large files using wget.exe during installation.

## File structure and installation scripts
* The installation uses BAT files. It is horrible BUT it has the advantages that nobody has to install additional tools, it is understandable, and trasparent (can be read and editied with a text editor).
* Read the installation scripts (.bat files) carefully to understand what is happening. Read also .gitignore, and xcopy_exclude.txt
* Read SAxVCxLC_source\Readme.txt




