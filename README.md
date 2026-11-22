** NvToppsFix **

Description:
This fix disables the loading of the nvtopps.dll plugin on systems with an NVIDIA GPU. 
This prevents unnecessary, extensive logging on SSDs (120 GB per hour). 

Read more about this at:
https://www.nvidia.com/en-us/geforce/forums/game-ready-drivers/13/592907/continuous-writing-of-gigabytes-to-ssd-to-nvtopps-/3634607/

How it works:
- the relevant registry key is set
- the NVIDIA service is restarted
- done

(c) 80sKid 20.11.2026
