<h1 align="center">Neural Style Transfer using CNN:</h1>


## Follow the steps 
```bash
!wget http://images.cocodataset.org/zips/test2017.zip
!mkdir './dataset'
!unzip -q ./test2017.zip -d './dataset'
```
```bash
!mkdir ./checkpoints
!wget -q -O 'best_model.pth' https://www.dropbox.com/s/7xvmmbn1bx94exz/best_model.pth?dl=1
!mv best_model.pth ./checkpoints
```


```bash
!mkdir ./content
!mkdir ./style
!wget -q https://github.com/myelinfoundry-2019/challenge/raw/master/japanese_garden.jpg -P './content'
!wget -q https://github.com/myelinfoundry-2019/challenge/raw/master/picasso_selfportrait.jpg -P './style'
```
