### Breaking the I/O and Computation Bottlenecks in Massive MIMO Base Stations

Massive multi-antenna (MIMO) wireless systems, in which the base-station is equipped with hundreds or thousands of antenna elements, will enable unprecedented data rates, cell coverage, and transmission reliability compared to that of existing cellular communication systems. The presence of hundreds or thousands of radio-frequency (RF) transceivers and antennas, however, results in excessively high internal data rates, which results in chip-interconnect and computation bottlenecks that prevent a straightforward deployment of this technology in practice. This project will develop new technologies that rely on decentralized signal processing at the base-station in order to avoid these bottlenecks, which leads to feasible and scalable solutions that enable base-station designs with thousands of antenna elements without sacrificing performance or reliability. In addition to enabling massive MIMO in practice, the project will advance future cellular networks through collaboration with the telecommunications industry, with the [Argos massive MIMO testbed](http://argos.rice.edu/), and other network research testbeds. The project's broader impact on education and outreach will include multiple components, including (i) training a diverse group of students as part of a collaborative, multi-institutional research team in the areas of communication theory and circuit design, (ii) integrating outcomes of the work into undergraduate and graduate courses, and (iii) making research outcomes broadly available through public-domain software packages and open-education resources via OpenStax courseware.

The project develops novel decentralized algorithms as well as very-large scale integration (VLSI) and general-purpose computing on graphics processing units (GPGPU) architectures based on antenna clustering and parallelization, for the uplink (users communicate to base-station) and the downlink (base-station communicates to users). The main idea of decentralized baseband processing is to divide the signal-processing workload at the base-station into multiple computing fabrics that are each connected to only a subset of RF transceivers and antennas. To reduce the chip-interconnect and computation bottlenecks the project investigates (i) optimization-based algorithms that exchange consensus information among the antenna clusters and (ii) message-passing-based algorithms that avoid such consensus exchange altogether. The most promising algorithm solutions will be implemented on field-programmable gate array and GPGPU clusters to assess the efficacy and limits of the developed solutions with real-world performance, hardware, and bandwidth constraints. The results of this analysis will provide guidelines that enable optimal massive MIMO base-station designs that use decentralized baseband processing.

## News

* Dec. 2018: Charles Jeon successfully defended his Ph.D. Thesis on massive MIMO data detection and feedforward architectures for decentralized baseband processing. We wish him good luck at Intel Labs in Hillsboro, OR!

* Nov. 2018: [Kaipeng Li wins 2nd place in the student paper contest at Asilomar 2018](https://engineering.rice.edu/news/more-antennas-means-more-connectivity-mobile-devices)

## Publications

* [Li, Kaipeng and Sharan, Rishi R. and Chen, Yujun and Goldstein, Tom and Cavallaro, Joseph R. and Studer, Christoph. "Decentralized Baseband Processing for Massive MU-MIMO Systems," IEEE Journal on Emerging and Selected Topics in Circuits and Systems, v.7, 2017. doi:10.1109/JETCAS.2017.2775151](https://arxiv.org/abs/1702.04458)

* [Jacobsson, Sven and Durisi, Giuseppe and Coldrey, Mikael and Goldstein, Tom and Studer, Christoph. "Quantized Precoding for Massive MU-MIMO," IEEE Transactions on Communications, v.65, 2017. doi:10.1109/TCOMM.2017.2723000](https://arxiv.org/abs/1610.07564)

* [Jeon, Charles and Li, Kaipeng and Cavallaro, Joseph R. and Studer, Christoph. "On the achievable rates of decentralized equalization in massive MU-MIMO systems," IEEE International Symposium on Information Theory (ISIT), 2017. doi:10.1109/ISIT.2017.8006699](https://arxiv.org/abs/1705.02976)

* [Jacobsson, Sven and Durisi, Giuseppe and Coldrey, Mikael and Gustavsson, Ulf and Studer, Christoph. "Throughput Analysis of Massive MIMO Uplink With Low-Resolution ADCs," IEEE Transactions on Wireless Communications, v.16, 2017. doi:10.1109/TWC.2017.2691318](https://arxiv.org/pdf/1602.01139.pdf)

* [Li, Kaipeng and Skaran, Riski and Chen, Yujun and Cavallaro, Joseph R. and Goldstein, Tom and Studer, Christoph. "Decentralized beamforming for massive MU-MIMO on a GPU cluster," IEEE Global Conference on Signal and Information Processing (GlobalSIP), 2016. doi:10.1109/GlobalSIP.2016.7905910](http://vip.ece.cornell.edu/papers/16GlobalSIP_decent.pdf)

* [Li, Kaipeng and Chen, Yujun and Sharan, Rishi and Goldstein, Tom and Cavallaro, Joseph R. and Studer, Christoph. "Decentralized data detection for massive MU-MIMO on a Xeon Phi cluster," Asilomar Conference on Signals, System, and Computers, 2016. doi:10.1109/ACSSC.2016.7869083](https://ieeexplore.ieee.org/document/7869083)

## People
[**Joe Cavallaro**](http://cavallaro.rice.edu/) at Rice University and [**Christoph Studer**](http://vip.ece.cornell.edu) at Cornell University.

## Contact Information
Email us at nsfbrick@gmail.com
