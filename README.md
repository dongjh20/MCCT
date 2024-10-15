
# <a href="https://dongjh20.github.io/MCCT" target="_blank">Mixed Cloud Control Testbed (MCCT)</a> 

<!--课题组网站链接-->
[![tsinghua-svm-thicv](https://img.shields.io/badge/Tsinghua_University-THICV-brightgreen)](https://www.labxing.com/thicv)

<!---用到的系统-->
<a><img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>
<a><img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"></a>

<!--硬件条件-->
![cloud-gpu](https://img.shields.io/badge/NVIDIA-RTX3090-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![unity-gpu](https://img.shields.io/badge/NVIDIA-RTX2080_SUPER-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![cloud-cpu](https://img.shields.io/badge/Intel-Xeon(R)_Gold_5220R_@2.20GHz-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![unitycpu](https://img.shields.io/badge/Intel-CORE_I7_10700K_@3.80GHz-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![cloud-host](https://img.shields.io/badge/Ubuntu-DELL_Precision_7920-0078D6?style=for-the-badge&logo=ubuntu&logoColor=white)
![unity-host](https://img.shields.io/badge/Windows-Lenovo_ThinkStation_P340-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![HoloLens](https://img.shields.io/badge/Microsoft-HoloLens-258ffa?style=for-the-badge&logo=microsoft&logoColor=white)

<!--用到的语言-->
<a><img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white"></a>
<a><img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"></a>
<a><img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white"></a>
<a><img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"></a>
![matlab](https://img.shields.io/badge/MATLAB-258ffa?style=for-the-badge&logo=matlab&logoColor=white)

<!--用到的软件-->
![ROS](https://img.shields.io/badge/ros-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white)
<a><img src="https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white"></a>
![CLion](https://img.shields.io/badge/CLion-black?style=for-the-badge&logo=clion&logoColor=white)
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)
![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)
![](https://img.shields.io/badge/SCANeR_Studio-FA7343?style=for-the-badge)



In this project, we present demo videos for our miniature experimental platform, Mixed Cloud Control Testbed (MCCT), developed based on a new notion of Mixed Digital Twin (mixedDT). 

## The notion of mixedDT
Combining Mixed Reality with Digital Twin, mixedDT integrates the virtual and physical spaces into a mixed one, where physical entities coexist and interact with virtual entities via their digital counterparts. 

The schematic diagram of the classical Digital Twin is as follows.

<img src="resources/dt-architecture.jpg" align="center" width="50%"/>

The schematic diagram of the proposed mixedDT is as follows.

<img src="resources/mdt-architecture.jpg" align="center" width="50%"/>

## The architecture of the MCCT

Under the framework of mixedDT, MCCT contains three major experimental platforms in the physical, virtual and mixed spaces respectively, and provides a unified access for various human-machine interfaces and external devices such as driving simulators.

<img src="resources/MCCT-architecture.jpg" align="center" width="50%"/>

An corresponding overview of the MCCT is as follows.

<img src="resources/MCCT-overview.png" align="center" width="50%"/>

The detailed physical architecture of the MCCT is as follows, which is not presented in paper due to space limitations.

<img src="resources/MCCT-framework.png" align="center" width="80%"/>

## Demo videos
Cross-platform experiments are carried out on vehicle platooning, which is composed of different types of vehicles from different platforms in MCCT.

**Experiment A:** Mixing physical miniature vehicles and virtual vehicles

The formation of the platoon for experiment A is shown below.

<img src="resources/formation-experiment-A.jpg" align="center" width="50%"/>

The video of the experiment process is shown below.

<img src="resources/experiment-A-V2.gif" align="center" width="100%"/>

**Experiment B:** Mixing physical miniature vehicles, virtual vehicles and a human-driven vehicle via a driving simulator

The formation of the platoon for experiment B is shown below. SCANeR Studio is the supporting software of the driving simulator. 

<img src="resources/formation-experiment-B.jpg" align="center" width="50%"/>

The video of the experiment process is shown below.

<img src="resources/experiment-B.gif" align="center" width="100%"/>

<!--还没放上去，先不放
More longer videos can be found on [![](https://img.shields.io/badge/YouTube-SICity-FF0000?style=logo=youtube&logoColor=white)](https://github.com/cmc623/Formation-control-experiments).
-->

## More experiments on MCCT
- Multi-vehicle coordinated formation control. [![](https://img.shields.io/badge/GitHub-Formation_control-green?style=logo=github&logoColor=white)](https://github.com/cmc623/Formation-control-experiments)
- Data-Enabled Predictive Leading Cruise Control (DeeP-LCC). [![](https://img.shields.io/badge/GitHub-DeeP_LCC-green?style=logo=github&logoColor=white)](https://github.com/soc-ucsd/DeeP-LCC)

## Related publications
1. Yang C, Dong J, Xu Q, et al. Multi-vehicle experiment platform: A Digital Twin Realization Method[C]//2022 IEEE/SICE International Symposium on System Integration (SII). IEEE, 2022: 705-711. <a href="https://www.researchgate.net/publication/359072029_Multi-vehicle_experiment_platform_A_Digital_Twin_Realization_Method" target="_blank">[paper link]</a>
2. Cai M, Xu Q, Yang C, et al. Experimental Validation of Multi-lane Formation Control for Connected and Automated Vehicles in Multiple Scenarios[J]. arXiv preprint arXiv:2112.00312, 2021. <a href="https://www.researchgate.net/publication/356711150_Experimental_Validation_of_Multi-lane_Formation_Control_for_Connected_and_Automated_Vehicles_in_Multiple_Scenarios" target="_blank">[paper link]</a>
3. Wang J, Zheng Y, Dong J, et al. Experimental Validation of DeeP-LCC for Dissipating Stop-and-Go Waves in Mixed Traffic[J]. arXiv preprint arXiv:2204.03747, 2022. <a href="https://arxiv.org/abs/2204.03747" target="_blank">[paper link]</a>
4. Dong J, Xu Q, Wang J, et al. Mixed cloud control testbed: Validating vehicle-road-cloud integration via mixed digital twin[J]. IEEE Transactions on Intelligent Vehicles, 2023. <a href="https://arxiv.org/abs/2212.02007" target="_blank">[paper link]</a>
5. Wang J, Zheng Y, Dong J, et al. Implementation and experimental validation of data-driven predictive control for dissipating stop-and-go waves in mixed traffic[J]. IEEE Internet of Things Journal, 2023. <a href="https://ieeexplore.ieee.org/document/10210648" target="_blank">[paper link]</a>
## Citing MCCT
If you refer to MCCT in your research, please cite this <a href="https://arxiv.org/abs/2212.02007" target="_blank">paper</a>. In BibTeX format:

```bibtex
@article{dong2023mixed,
  title={Mixed cloud control testbed: Validating vehicle-road-cloud integration via mixed digital twin},
  author={Dong, Jianghong and Xu, Qing and Wang, Jiawei and Yang, Chunying and Cai, Mengchi and Chen, Chaoyi and Liu, Yu and Wang, Jianqiang and Li, Keqiang},
  journal={IEEE Transactions on Intelligent Vehicles},
  year={2023},
  volume={8},
  number={4},
  pages={2723-2736},
  publisher={IEEE}
}
```

## Contacts
For more details, please contact <a href="https://scholar.google.com/citations?user=ncDpC9gAAAAJ&hl=en" target="_blank">Jianghong Dong</a> and <a href="https://wjiawei.com" target="_blank">Jiawei Wang</a>.

## Stargazers over time
[![Stargazers over time](https://starchart.cc/dongjh20/MCCT.svg)](https://starchart.cc/dongjh20/MCCT)

 <html>
<!-- Default Statcounter code for MCCT
https://dongjh20.github.io/MCCT/ -->
<script type="text/javascript">
var sc_project=13046661; 
var sc_invisible=0; 
var sc_security="5dc98174"; 
var scJsHost = "https://";
document.write("<sc"+"ript type='text/javascript' src='" +
scJsHost+
"statcounter.com/counter/counter.js'></"+"script>");
</script>
<noscript><div class="statcounter"><a title="Web Analytics"
href="https://statcounter.com/" target="_blank"><img
class="statcounter"
src="https://c.statcounter.com/13046661/0/5dc98174/0/"
alt="Web Analytics"
referrerPolicy="no-referrer-when-downgrade"></a></div></noscript>
<!-- End of Statcounter Code -->
 </html>
