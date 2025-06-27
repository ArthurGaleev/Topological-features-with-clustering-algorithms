# Topological-features-with-clustering-algorithms

The coursework on Topological Point Cloud Clustering method [[1]](#1). The work investigated compatibility of topological features [[2]](#2) with KMeans, Deep Embedding Clustering [[3]](#3), Contrastive Clustering [[4]](#4) algorithms on MNIST and CIFAR10 datasets.

Obtained results:
<table>
  <thead>
    <tr>
      <th rowspan="2" align="center"><strong>Clustering</strong></th>
      <th rowspan="2" align="center"><strong>TOPF</strong></th>
      <th colspan="5" align="center"><strong>MNIST</strong></th>
      <th colspan="5" align="center"><strong>CIFAR10</strong></th>
    </tr>
    <tr>
      <th align="center"><strong>ACC</strong></th>
      <th align="center"><strong>NMI</strong></th>
      <th align="center"><strong>RI</strong></th>
      <th align="center"><strong>FMI</strong></th>
      <th align="center"><strong>BCubed</strong></th>
      <th align="center"><strong>ACC</strong></th>
      <th align="center"><strong>NMI</strong></th>
      <th align="center"><strong>RI</strong></th>
      <th align="center"><strong>FMI</strong></th>
      <th align="center"><strong>BCubed</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2" align="center"><strong>Kmeans</strong></td>
      <td align="center"></td>
      <td align="center">0.74</td>
      <td align="center">0.72</td>
      <td align="center">0.63</td>
      <td align="center">0.67</td>
      <td align="center">0.69</td>
      <td align="center">0.25</td>
      <td align="center">0.12</td>
      <td align="center">0.06</td>
      <td align="center">0.16</td>
      <td align="center">0.17</td>
    </tr>
    <tr>
      <td align="center">✓</td>
      <td align="center">0.79</td>
      <td align="center">0.73</td>
      <td align="center">0.66</td>
      <td align="center">0.70</td>
      <td align="center">0.70</td>
      <td align="center">0.25</td>
      <td align="center">0.12</td>
      <td align="center">0.06</td>
      <td align="center">0.16</td>
      <td align="center">0.17</td>
    </tr>
    <tr>
      <td rowspan="2" align="center"><strong>DEC</strong></td>
      <td align="center"></td>
      <td align="center">0.69</td>
      <td align="center">0.75</td>
      <td align="center">0.62</td>
      <td align="center">0.66</td>
      <td align="center">0.69</td>
      <td align="center">0.19</td>
      <td align="center">0.08</td>
      <td align="center">0.04</td>
      <td align="center">0.19</td>
      <td align="center">0.18</td>
    </tr>
    <tr>
      <td align="center">✓</td>
      <td align="center"><strong>0.84</strong></td>
      <td align="center"><strong>0.83</strong></td>
      <td align="center"><strong>0.77</strong></td>
      <td align="center"><strong>0.80</strong></td>
      <td align="center"><strong>0.82</strong></td>
      <td align="center">0.18</td>
      <td align="center">0.08</td>
      <td align="center">0.03</td>
      <td align="center">0.21</td>
      <td align="center">0.19</td>
    </tr>
    <tr>
      <td rowspan="2" align="center"><strong>CC</strong></td>
      <td align="center"></td>
      <td align="center">0.53</td>
      <td align="center">0.39</td>
      <td align="center">0.32</td>
      <td align="center">0.39</td>
      <td align="center">0.39</td>
      <td align="center">0.21</td>
      <td align="center">0.07</td>
      <td align="center">0.04</td>
      <td align="center">0.14</td>
      <td align="center">0.14</td>
    </tr>
    <tr>
      <td align="center">✓</td>
      <td align="center">0.53</td>
      <td align="center">0.40</td>
      <td align="center">0.33</td>
      <td align="center">0.34</td>
      <td align="center">0.40</td>
      <td align="center">0.19</td>
      <td align="center">0.06</td>
      <td align="center">0.03</td>
      <td align="center">0.13</td>
      <td align="center">0.13</td>
    </tr>
  </tbody>
</table>


## References
<a id="1">[1]</a> 
Vincent P. Grande, Michael T. Schaub. “Topological Point Cloud Clustering”. В: 40th
International Conference on Machine Learning (2023).

<a id="2">[2]</a> 
Vincent P. Grande и Michael T. Schaub. “Point-Level Topological Representation Learning
on Point Clouds”. В: arXiv (2025).

<a id="3">[3]</a> 
Ali Farhadi Junyuan Xie Ross Girshick. “Unsupervised Deep Embedding for Clustering
Analysis”. В: International Conference on Machine Learning (2016).

<a id="4">[4]</a> 
Yunfan Li, Peng Hu, Zitao Liu, Dezhong Peng, Joey Tianyi Zhou и Xi Peng. “Contrastive
Clustering”. В: arXiv (2020).
