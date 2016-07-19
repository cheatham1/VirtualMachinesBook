# Get and Run the Virtual Machine


## Getting the Virtual-Machine-Scientific-Linux-6.7 ( **VM-SL6.7** ) with the **ATLAS Data & Tools Software and Samples**


In order to obtain the Virtual Desktop Infrastructure (**VDI**) file of our **VM-SL6.7**, we need to be sure that our host system has space for it.  At least **30GB** of space should be reserved.

Select the black Download button at the top right of the webpage, then Virtual Machines.  

<img src="./pictures/Download.jpg" width="100" />
<img src="./pictures/VMbutton.jpg" width="150" /> 



There are four versions of Virtual Machine (VM):  
**VM-S** 
: S for “small”, it has a compressed size of ~4.6GB, and a uncompressed size of ~11GB. This contains a complete Scientific Linux OS 6.7, important software dependencies and the latest version of ROOT v6-07-06

**VM-M** 
: M for “medium”, it has a compressed size of ~10.6GB, and a uncompressed size of ~22GB. This contains a complete Scientific Linux OS 6.7, important software dependencies, the latest version of ROOT v6-07-06 and the **complete set of datasets** (data and simulated Monte Carlo) of the ATLAS release.

**VM-N**
: N for “NET” with unknown sizes yet, but smaller that VM-S. This will contain a complete Scientific Linux OS 6.7, important software dependencies and CVMFS access to public software repositories.

**VM-mu**
: mu for “micro” with unknown sizes yet, but much smaller that VM-N or VM-S. It will contain a Linux distribution with not graphical user interface. It will have important software dependencies and the latest version of ROOT v6*

Select the VM Version appropriate to your needs.  VM Version M is recommended, if you have the space, as it contains all the software and datasets.

**Download will take some time.  Please be patient.**

The **VDI** file of the **VM-SL6**
might be unzipped automatically.
ScientificLinux67_ATLAS_Outreach_DataAndTools_July_2016-size_[S/M/N/mu].vdi 

If not, you can directly select the option of opening the .vdi.gz file.

![](NewPictures/DownloadVMS.jpg)


Which will unzip the file

![](NewPictures/orangeVDI.png)



## Addding the VDI file of the VM-SL6 to the VirtualBox machine: 

You must click **Settings** on the top-left position of your VirtualBox window (the " _gear_  " icon)


![](NewPictures/Settings.jpg)

Now in the new _pop-up_ window, you must go to **Storage** ( _4th left to the right_ ) 



![](NewPictures/Storage.jpg)

Select your .vdi
You will then see on the right the **Hard Disk** and a small icon of a _hard disk_ .If you click there, the system will give you two options. 
You have to select: **Choose a virtual hard disk file...**


![](NewPictures/VirtualHardDisk.jpg)

Browse for the recent downloaded (and uncompressed) **VDI** file of the **VM-SL6.7** :


![](NewPictures/Choosevdi.jpg)

Open.
Now say **OK** to the **Settings** window and **Start** your **VM-SL6.7**   

![](NewPictures/Start.jpg)

You will see something like this below

![](pictures/Screenshot_2015-02-03_15.33.12.png)

![](pictures/Screenshot_2015-02-03_15.34.04.png)

**IMPORTANT NOTE:** To login to the **VM-SL6** use as _username_ = **adminuser** and as _password_ = **adminuser**
(This is your *root* password if you plan/need to do su and/or sudo ).

