# CS224W-Colab
Solutions for Stanford CS224W (Machine Learning with Graphs) Colab, Winter 2021

斯坦福大学 图机器学习课程 CS224W Colab答案

http://web.stanford.edu/class/cs224w/

- [x] Colab 0 (No code needed)
- [x] Colab 1
- [x] Colab 2
- [x] Colab 3
- [x] Colab 4
- [x] Colab 5 (No code needed)

## Problem with importing torch-geometric
If you encounter problems about importing torch-geometric on Colab, you can go to https://colab.research.google.com/drive/1h3-vJGRVloF5zStxL5I0rSy4ZUPNsjy8 to get the correct installing commands for the newest version of torch and cuda, such as 
```
!pip install -q torch-scatter -f https://pytorch-geometric.com/whl/torch-1.9.0+cu102.html
!pip install -q torch-sparse -f https://pytorch-geometric.com/whl/torch-1.9.0+cu102.html
!pip install -q torch-geometric
```
