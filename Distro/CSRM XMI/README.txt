The file is a vendor neutral version of the CSRM. This file requires the XMI for the 1.1 release of the CSRM Profile (included for conveniance).
Note that this may not load correctly with MagicDraw/Cameo/CATIA-Magic (Dassault Systemes) tools because of the URI for UML and other profiles. 

Steps for Dassault Systemes tools:
	1) Load and save the CSRM profile and correct coruptions (this fixes the profile references).
	2) Resave in the default format of your tool (mdzip for Dassault Systems). 
	3) Then load CSRM and resolve the profile to point to the newe file and correct corruptions (this fixes the profile references).
	4) Save the CSRM in the tool specific format(mdzip for Dassault Sysstems).