# Inside The Virtual Machine


## Software Available

If you open a Firefox window, you will get this presentation below, but where the **only bookmark** is the tutorial that you are doing now! 

![](pictures/Screenshot_2015-02-03_15.35.23.png)

Open a new **Terminal** ( _the icon is at the top..._ ) and do a "ls"  command right there, you will get the list:  (_picture below_)

I. The two scripts to setup the
  **AnalysisBase 2.0.24** and **AnalysisBase 2.1.24**;  
   AnalysisBase 2.0.24.sh and AnalysisBase 2.1.24.sh
   
   
II. The ATLAS folder containing the **software** and **xAOD input** we will use

III. Other Standard Linux folders

![](pictures/Screenshot_2015-02-03_15.36.28.png)

Going into the ATLAS folder you will find the next _relevant for us_ structure:

To be fixed:
ATLAS
  |
  ---- AnalysisBase     ## Our workspace place with the ATLAS Analysis software
        |
        ---- 2.0.24
        |
        ---- 2.1.24
  |
  ---- roots              ## Our two possible ROOT versions, very up-to-date (February 2015) They are use to run 2.0.24 (ROOT5) and 2.1.24 (ROOT6) 
        |
        ---- root-v5-34-24
        |
        ---- root-v6-02-04
  |
  ---- samples          ## The xAOD sample useful for tutorial and development, as you see (picture below) it's a real sample with 3GB size.
        |
        ---- mc14_8TeV.160009.*ggH125_gamma*/
               |
                ---- AOD.01512140._000094.pool.root.1
                
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

You can take a look to the **xAOD** file too as it is mention in the tutorial, but browsing the file locally!

![](pictures/Screenshot_2015-02-03_01.00.00.png)

**Note:** You can install a Cloud client to keep a real time contact with your two machines.

 <CENTER>
   Dropbox or Google Drive Client to share files between the VM-SL6 and your host OS:
     <img src="pictures/Screenshot_2015-02-03_16.32.37.png" alt="Screenshot_2015-02-03_16.32.37.png" width="400" height="300" />
     
     <img src="pictures/Screenshot_2015-02-03_16.34.04.png" alt="Screenshot_2015-02-03_16.34.04.png" width="400" height="300" />
   </CENTER>
   
