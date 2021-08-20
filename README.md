# Unsupervised Learning Crash Course
_Crash Course on Clustering and Dimensionality Reduction Techniques._

In this two-hours long tutorial we will go explore two of the main approaches of Unsupervised Learning, namely _Clustering_ and _Dimension Reduction_. 

Here is the general outline of the course: 

1. Preamble on different (Machine) _Learning Flavours_
	- Quick recap of `sklearn` APIs, with particular emphasis on Clustering

2. Introduction to Clustering
	- Clustering Approaches: Flat vs Hierarchical vs Spectral algorithms
	- Hands-on using `KMeans` clustering w/ limitations
	- Introduction to `HDBscan` and how it works
	- (**EXTRA**) Hands-on Example of Semi-Supervised Learning


3. Dimension Reduction: from `PCA` to `UMAP`
	- UMAP features and Inverse Transformation Example 	


## Instructions

### Get the material

Clone the current repository, in order to get the course materials. To do so, once connected to your remote machine (via `SSH`), execute the following instructions:

```bash
cd $HOME  # This will make sure you'll be in your HOME folder
git clone https://github.com/WebValley2021ReImagined/unsupervised-learning.git
```

**Note**: This will create a new folder named `unsupervised-learning`. Move into this folder by typing:

```bash
cd unsupervised-learning
```

Well done! Now you should do be in the right location. Bear with me another few seconds, following instructions reported below 🙏

### Updating your Environment

To execute the notebooks in this repository, a few _extra_ packages are required, but installing them in your Conda environment is super easy. 

While into the `unsupervised-learning` folder, execute the two following instructions:

```bash
conda activate py38_default  #activate your conda environment
pip install -r requirements.txt  # to install the extra packages
```

🎉 You should be now ready to go!

The last bit is to run your `jupyter lab` server, and open the notebooks:

```bash
jupyter lab
```



## Colophon

**Author**: Valerio Maggio ([`@leriomaggio`](https://twitter.com/leriomaggio)), Senior Research Associate, University of Bristol. 

All the **Code** material is distributed under the terms of the GNU GPLv3 License. See [LICENSE](./LICENSE) file for additional details.

All the instructional materials in this repository is free to use, and made available under the [Creative Commons Attribution
license][https://creativecommons.org/licenses/by/4.0/]. The following is a human-readable summary of (and not a substitute for) the [full legal text of the CC BY 4.0
license](https://creativecommons.org/licenses/by/4.0/legalcode).

You are free:

* to **Share**---copy and redistribute the material in any medium or format
* to **Adapt**---remix, transform, and build upon the material

for any purpose, even commercially.

The licensor cannot revoke these freedoms as long as you follow the
license terms.

Under the following terms:

* **Attribution**---You must give appropriate credit (mentioning that
  your work is derived from work that is Copyright © Valerio Maggio 
  and, where practical, linking to this repository, and indicate if 
  changes were made. You may do
  so in any reasonable manner, but not in any way that suggests the
  licensor endorses you or your use.

**No additional restrictions**---You may not apply legal terms or
technological measures that legally restrict others from doing
anything the license permits. 

### Contacts 

For any questions or doubts, feel free to open an [issue](https://github.com/WebValley2021ReImagined/unsupervised-learning/issues) in the repository, or drop me an email @ `valerio.maggio_at_bristol.ac.uk` (Replace `_at_` accordingly)

