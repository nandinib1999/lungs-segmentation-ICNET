# lungs-segmentation-ICNET

<h2>Segmentation using Lungs X-Ray </h2><br>
![alt text](https://raw.githubusercontent.com/theidentity/Unets/master/documentation/sample.png)

## Details
<ul>
  <li>Implementation of ICNet using Tensorflow 2.0</li>
  <li>Dataset Link: https://data.mendeley.com/datasets/rscbjbr9sj/2</li>
  <li>Segmentation maps need to generated manually. I have added a small subset of images with their segmentation maps as <b>data.zip</b>.</li>
</ul>
<br>
<br>
```
| First Header  | Second Header |
| ------------- | ------------- |
| Input  | 256 x 256 GrayScale XRay Images  |
| Output  | 256 X 256 Segmentation Map |
```
## Important Notes
While creating data folder, please ensure the following folder structure:
```
    ├── ...
    ├── train                    
    │   ├── id1
    |   |   ├── images
    |   |   |   ├── id1.png
    |   |   ├── mask
    |   |   |   ├── id1.png
    |   |.....
    │   ├── test         
    │   |   ├── id2
    |   |   ├── images
    |   |   |   ├── id2.png               
    └── ...
```
