# ISAC_learning
在ISAC系统中，包含了通信和感知两个大方面的性能指标（Performance criteria）。
（1）雷达探测性能指标（Radar performance criteria）主要是检测（Detection）和估计（Estimation）两个方面：
在刻画目标检测性能上，可以描述为正确检测概率、错误检测概率和虚警（False alarm）概率，对于单个基站单个目标（Target）的检测可以建模为一个二元假设问题，从而根据一些统计推断的理论，可以得到获得对应的检测器。
对于参数估计（Parameter estimation）问题，估计器的性能通常可以用均方误差（Mean Squared Error, MSE）和克拉美-罗下界（Cramér–Rao Lower Bound，CRLB）进行刻画。
[1] Fishler E, Haimovich A, Blum R S, et al. Spatial diversity in radars—Models and detection performance[J]. IEEE Transactions on signal processing, 2006, 54(3): 823-838. [2] Bekkerman I, Tabrikian J. Target detection and localization using MIMO radars and sonars[J]. IEEE Transactions on Signal Processing, 2006, 54(10): 3873-3883.
[3] S. M. Kay, “Fundamentals of statistical signal processing,” in Estimation Theory. Englewood Cliffs, NJ, USA: Prentice Hall, 1998.

（2）通信的性能指标，多为SNR、SINR、误码率、通信速率等。
基本的性能指标、更多相关的基础内容、ISAC研究的基本理论和场景框架，可以参考南科大Fan Liu老师等[4]、北邮Yuanhao Cui博士等[5]、浙大An Liu老师等[6]的ISAC综述。
[4] Liu F, Cui Y, Masouros C, et al. Integrated sensing and communications: Towards dual-functional wireless networks for 6G and beyond[J]. IEEE Journal on Selected Areas in Communications, 2022. 
[5] Cui Y, Liu F, Jing X, et al. Integrating Sensing and Communications for Ubiquitous IoT: Applications, Trends, and Challenges[J]. IEEE Network, 2021, 35(5): 158-167. 
[6] Liu A, Huang Z, Li M, et al. A survey on fundamental limits of integrated sensing and communication[J]. IEEE Communications Surveys & Tutorials, 2022.
