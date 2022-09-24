<div id="top"></div>

# Cluster Analysis
<img width="1080" alt="image" src="https://user-images.githubusercontent.com/30044227/165281870-353a5279-d1e1-4317-b030-3bc13b253722.png">
The method we use follows the approach developed by Bazellières et al.[1]. The method consists of three steps

1. Building the correlation matrix
1. Ordering the correlation matrix
3. Identifying the clusters

This project is a Python version of the code used in the original paper. It is friendly to running on line in Google Colab. If you use this in your work, please cite our paper.
<p align="right">(<a href="#top">back to top</a>)</p>

## Getting Started
Upload the file containing the Z-score matrix (unordered) to Colab and run all cells. The matrices can be downloaded as excel files from Colab.

**Try it on Google Colab:**  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MinahilRaza/ClusteringAnalysis/blob/main/ClusteringAnalysis.ipynb)

<p align="right">(<a href="#top">back to top</a>)</p>

## Usage
After connecting to the runtime, upload the CSV file containing the Z-score matrix.
<p align="center"><img width="438" alt="image" src="https://user-images.githubusercontent.com/30044227/165277320-590b4270-6551-40d2-a18a-3b154f2537d8.png"></p> 

Run all the cells to build and order the correlation matrices. Once the clusters have been identified, the boundaries can be visualized in the notebook. The ordered matrices are saved as excel files which can be dowloaded from the sidepane in the notebook.
<p align="right">(<a href="#top">back to top</a>)</p>

## License
Distributed under the MIT License. See `LICENSE.txt` for more information.
<p align="right">(<a href="#top">back to top</a>)</p>

## Contact
Minahil Raza - [@LinkedIn](https://www.linkedin.com/in/minahil-rz/) - minahilrz@gmail.com
<p align="right">(<a href="#top">back to top</a>)</p>

## References
> <a id="1">[1]</a> 
Bazellières, E., Conte, V., Elosegui-Artola, A. et al. Control of cell–cell forces and collective cell dynamics by the intercellular adhesome. Nat Cell Biol 17, 409–420 (2015). https://doi.org/10.1038/ncb3135
