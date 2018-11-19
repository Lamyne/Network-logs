# Network performances logs

This archive contains logs from TCP streaming sessions in  3G/LTE-A(4G) mobile wireless network in France. 
In each test, the python "pyspeedtest" (https://pypi.org/project/pyspeedtest/) were used to measure the 
network bandwidth value. In fact, ping utility is used to  measure delay, jitter and loss rate.
The tests were performed in the period 2017-10-13 to 2017-10-28. 
   
   
The logs are grouped according to the type of used transportation mode (Train, Bus and RER (Train around Paris)). 
Note that each path only have one measurement, i.e., the bandwidth plot does not have a standard deviation.  
Note also that each tranportation mode works woth a specific mobile wireless network technology as follow:
  
   1- Train with 3G technology,
   
   2- RER with 3G technology,
   
   3- Bus with 4G technology.
   
   
 
## Acknowledgement

If you use the proposed logs in your research, you must
   
   1- Include the link to the repository.
   
   2- Cite the following publication:
   
   
@misc{dataset2017,
author = {{L}amine Amour, and {S}ami Souihi, and {M}ellouk {A}bdelhamid},
title = {{Dataset 02~: Controlled Laboratory dataset collecting You Tube QoE IFs using VLC video player. Access: }},
year = {October 2017}, 
howpublished = {\underline{ \url{https://cir.fr/qoe-dataset/xxxxxxxx}}},
}

 ## File Layout
    
The subjective data is contained in the following files:
    
  - `Bus-3G.csv`: Network performances using Bus transportation mode with 3G technology , columns:
     - `time`: Unix timestamps 
     - `bandwidth`:	Network bandwidth (Kb/s)
     - `loss_rate`:	Packet loss rate (%)
     - `delay`:	Network latency (ms)
     - `jitter`: Network jitter (ms)
      
  - `RER-3G.csv`: Network performances using RER transportation mode with 3G technology , columns:
     - `time`: Unix timestamps 
     - `bandwidth`:	Network bandwidth (Kb/s)
     - `loss_rate`:	Packet loss rate (%)
     - `delay`:	Network latency (ms)
     - `jitter`: Network jitter (ms)
     
  - `Train-3G.csv`: Network performances using Train transportation mode with 3G technology , columns:
     - `time`: Unix timestamps 
     - `bandwidth`:	Network bandwidth (Kb/s)
     - `loss_rate`:	Packet loss rate (%)
     - `delay`:	Network latency (ms)
     - `jitter`: Network jitter (ms)
    

 ## Licence
     
Copyright 2018 TinCNet group, Paris Est Créteil Uinversity.

Permission is hereby granted, free of charge, to use this dataset for non-commercial research purposes.

NO EXPRESS OR IMPLIED LICENSES TO ANY PARTY'S PATENT RIGHTS ARE GRANTED BY THIS LICENSE. THE DATASET IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE DATASET OR THE USE OR OTHER DEALINGS IN THE DATASET.
    
## Authors

Main developers:
- Lamine Amour (TincNet group, LiSSi Laboratory, Paris Est Créteil University) 

Contributors:
- Sami Souihi (TincNet group, LiSSi Laboratory, Paris Est Créteil University)
- Abdelhamid Mellouk (TincNet group, LiSSi Laboratory, Paris Est Créteil University)
    
