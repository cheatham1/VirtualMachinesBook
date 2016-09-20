# Inside The Virtual Machine

You will get this presentation below, where the **only bookmark** is the tutorial that you are doing now! 

![](NewPictures/VMrunning.jpg)

Open a new **Terminal** ( the icon is at the top, shown here circled in red) and do a **ls**  command right there. You will get the list: ATLAS, Desktop, Documents, Downloads, Dropbox, Public, README and setup_ROOT.sh


![](NewPictures/terminal_ls.jpg)

Go into the ATLAS/analysis folder.  

```cd ATLAS/analysis```

Run the setupROOT script.  

```source setupROOT.sh```

Go into the atlas-outreach-data-tools-framework-1.0 folder.

```cd atlas-outreach-data-tools-framework-1.0```

Here you will see : Analysis, Configurations, Input, Output, Plotting and results folders plus two python scripts and README.md 

![](NewPictures/terminal.jpg)



## Take a look at the datasets.

Data and simulated data root ntuples are in the Input folder.

![](NewPictures/InputFolder.jpg)

Take a look:

```cd Input```

```ls Data```


Launch root, attaching your chosen dataset

    root Data/DataEgamma.root

![](NewPictures/LaunchROOT.jpg)

Use Tbrowser to look at the different variables available.

![](NewPictures/DataEgamma.jpg)

Then plot the variables.

![](NewPictures/Lep_pt.jpg)

To quit root

```- q```

**Note:** You can install a Cloud client to keep a real time contact with your two machines.

   Use Dropbox (included) or Google Drive Client to share files between the VM-SL6 and your host OS:
    
 
![](./pictures/Screenshot_2015-02-03_16.32.37.png)    
    ![](./pictures/Screenshot_2015-02-03_16.34.04.png)
   


## Now you are ready to start your analysis of the data.

Go to the chapter "**take a look at the data**" in the **Software Book**
and follow the instructions, starting with 

    python RunScript.py -a TTbarAnalysis -s "WW, WZ"
                
![](NewPictures/RunScript.jpg)


