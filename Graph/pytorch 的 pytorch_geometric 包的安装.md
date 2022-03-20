#  pytorch 的 pytorch_geometric 包的安装







- 查看 pytorch 版本
- 查看cuda 版本

例如hatter上:

`conda list`

torch                     1.10.2+cu113             pypi_0    pypi
![图片](https://user-images.githubusercontent.com/35489839/159191192-07441024-0016-42f5-8e74-5e6ac0caf679.png)





- 然后 在https://pytorch-geometric.com/whl查找版本依次pip安装以下几个包
![图片](https://user-images.githubusercontent.com/35489839/159191270-ff377c33-22f5-48e0-8ebf-20470db6b4d4.png)

--- 

![图片](https://user-images.githubusercontent.com/35489839/159191294-4d149e37-06c4-421b-a99b-558e37c4d273.png)

```
pip install torch-scatter==2.0.9 -f https://pytorch-geometric.com/whl/torch-1.10.2%2Bcu113.html
pip install torch-sparse==0.6.13 -f https://pytorch-geometric.com/whl/torch-1.10.2%2Bcu113.html
pip install torch-sparse==0.6.1 -f https://pytorch-geometric.com/whl/torch-1.10.2%2Bcu113.html
pip install torch-sparse==0.6.12 -f https://pytorch-geometric.com/whl/torch-1.10.2%2Bcu113.html
pip install torch-geometric
```

