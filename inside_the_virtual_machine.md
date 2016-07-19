# Inside The Virtual Machine


## Software Available

You will get this presentation below, where the **only bookmark** is the tutorial that you are doing now! 

![](NewPictures/VMrunning.jpg)

Open a new **Terminal** ( the icon is at the top, circled in red) and do a **ls**  command right there, you will get the list: ATLAS, Desktop, Documents, Downloads, Dropbox, Public, README and setup.sh


![](NewPictures/terminal_ls.jpg)

I. The two scripts to setup the
  **AnalysisBase 2.0.24** and **AnalysisBase 2.1.24**;  
   AnalysisBase 2.0.24.sh and AnalysisBase 2.1.24.sh
   
   
II. The ATLAS folder containing the **software** and **xAOD input** we will use

III. Other Standard Linux folders

![](pictures/Screenshot_2015-02-03_15.36.28.png)

Going into the ATLAS folder you will find the structure:

![](pictures/RootStructure.png)
                
![](pictures/Screenshot_2015-02-05_16.31.54.png)

You can see the behavior of **ROOT** using the two versions (ROOT5 and ROOT6 here below)

![](pictures/Screenshot_2015-02-03_15.38.22.png)

![](pictures/Screenshot_2015-02-03_15.39.45.png)

Taking a look into the two AnalysisBase setup scripts mentioned before (using command more ) you can see how **ROOT** is sourced and RootCore (+ _boost_ that is necessary to compile...) 

![](pictures/Screenshot_2015-02-03_15.41.40.png)

An internal view of one of the **AnalysisBase** releases: 

![](pictures/Screenshot_2015-02-03_15.53.00.png)

At this point you can start to work with the instructions in the Tutorial (_copying and pasting instructions..._) 

![](pictures/Screenshot_2015-02-03_15.56.19.png)

![](pictures/Screenshot_2015-02-03_16.17.42.png)

You can take a look at the **xAOD** file too, as mentioned in the tutorial, but browsing the file locally!

![](pictures/Screenshot_2015-02-03_01.00.00.png)

**Note:** You can install a Cloud client to keep a real time contact with your two machines.

 
   Dropbox or Google Drive Client to share files between the VM-SL6 and your host OS:
    
 
![](./pictures/Screenshot_2015-02-03_16.32.37.png)    
    ![](./pictures/Screenshot_2015-02-03_16.34.04.png)
   

