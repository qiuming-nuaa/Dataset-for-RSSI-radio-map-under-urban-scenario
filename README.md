Note: This work is done by Nanjing University of Aeronautics and Astronautics. Require the latest dataset please contact zhuqiuming@nuaa.edu.cn.
# 1.	Received signal strength under urban scenario (RT-based method)
## 1.1	Simulation setup
<div align=center>
<img src="https://github.com/qiuming-nuaa/Dataset-for-RSSI-radio-map-under-urban-scenario/blob/master/figures/scenario.jpg" width="220px">         <img src="https://github.com/qiuming-nuaa/Dataset-for-RSSI-radio-map-under-urban-scenario/blob/master/figures/meshed%20map.jpg" width="200px"> <br>
Simulation scenario and trajectories. Meshed map. <br> </div>

## 1.2	Data Files
The RT-based simulation data files include two scenarios, dynamic scenario (radiation sources are moving) data at the height of 2m and 80m, and static scenario (radiation sources are fixed) data at the height of 2m, 10m, 20m, 30m, 40m, 50m, 80m.<br>
The received signal strength data in the dynamic scenario is a .mat file in the format of a 250 * 250 * 300 tensor, where x, y represents the spatial grid dimension, z represents the time dimension, and the numerical value represents the signal strength in dBm. The file size at the height of 2m is 113MB, and the one at the height of 80m is 131MB. <br>
The received signal strength data in the static scenario is a .mat file in the format of a 250*250 matrix, where x, y represents the spatial grid dimension, and the numerical value represents the signal strength in dBm. The data file sizes for the heights of 10m, 20m, 30m, 40m, and 50m are 363KB, 385KB, 400KB, 406KB, and 405KB, respectively.<br>
## 1.3	Dataset visualizations 
<div align=center>
Dynamic scenario        Static scenario (t = 100s) <br>
  
![img](https://github.com/qiuming-nuaa/Dataset-for-RSSI-radio-map-under-urban-scenario/blob/master/figures/dynamic.gif) 
<img src="https://github.com/qiuming-nuaa/Dataset-for-RSSI-radio-map-under-urban-scenario/blob/master/figures/static40m.jpg" width="220px"> <br></div>

## 1.4 Recommended references<br>
[1].	J. Wang, Q. Zhu, Z. Lin, J. Chen, G. Ding, Q. Wu, G. Gu, Q. Gao. “Sparse Bayesian Learning-Based Hierarchical Construction for 3D Radio Environment Maps Incorporating Channel Shadowing,” IEEE Transactions on Wireless Communications, early access, 2024, doi: 10.1109/TWC.2024.3416447.<br>
[2].	Y. Zhao, Q. Zhu, Z. Lin, L. Guo, Q. Wu, J. Wang, W. Zhong. “Temporal prediction for spectrum environment maps with moving radiation sources,” IET Communications, vol. 17, no. 5, pp. 538–548, 2023.<br>
[3].	Q. Gao, Q. Zhu, Z. Lin, Y. Zhao, J. Wang, W. Zhong, Y. Huang, Q. Wu. “Spatial Sensor Layout Optimization for Radio Environment Map Construction,” 2024 IEEE Globecom Workshops, 2024, for publication
