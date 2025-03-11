# OpenHardwareMonitor

## Purpose of this fork
* added support for non-GUI platforms like e.g. Windows Core or Linux shells

## New Features
* selectable categories of data (e.g. only cpu and ram data, disable output of hdd, etc.), see #880 
![image](https://user-images.githubusercontent.com/3033827/42097749-324280aa-7bb9-11e8-935b-77a9f934b3bc.png)
* improves existing work on command line version, see #776 and #870 and #230, e.g. check for administration privileges, exception handling, console/logging output
* added option to write output to file 
![image](https://user-images.githubusercontent.com/3033827/42097967-d42def30-7bb9-11e8-9602-95e4349c0f7d.png)
* added option to run webserver from console application, e. g. very useful on monitoring continueously windows server core editions like windows hyper-v server from remote workstations   
![image](https://user-images.githubusercontent.com/3033827/42097628-e126032c-7bb8-11e8-8d25-b3e0cb40c0a5.png)
* added help and syntax output  ![image](https://user-images.githubusercontent.com/3033827/42097571-bb11d972-7bb8-11e8-9adb-d761dd082a61.png)
