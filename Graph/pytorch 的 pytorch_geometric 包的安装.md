#  pytorch 的 pytorch_geometric 包的安装







- 查看 pytorch 版本
- 查看cuda 版本

例如hatter上:

`conda list`

torch                     1.10.2+cu113             pypi_0    pypi





- 然后 在https://pytorch-geometric.com/whl查找版本依次pip安装以下几个包

```
pip install torch-scatter==latest+cu101 -f https://pytorch-geometric.com/whl/torch-1.4.0.html
pip install torch-sparse==latest+cu101 -f https://pytorch-geometric.com/whl/torch-1.4.0.html
pip install torch-cluster==latest+cu101 -f https://pytorch-geometric.com/whl/torch-1.4.0.html
pip install torch-spline-conv==latest+cu101 -f https://pytorch-geometric.com/whl/torch-1.4.0.html
pip install torch-geometric
```