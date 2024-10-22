[//]: # (Image references)

[image1]: documentation/Loss_train.svg "Training Loss"
[image2]: https://img.youtube.com/vi/Qz6XNSB0F3E/0.jpg
[image3]: https://img.youtube.com/vi/Qz6XNSB0F3E/0.jpg
[image4]: https://img.youtube.com/vi/Qz6XNSB0F3E/0.jpg


# Project documentation
---------------

# Introduction
**This is official implementation of Neural networks**



| Video1 | Video 2| Video 3|
|-------------|----------------|---|
|[![image2]](https://www.youtube.com/watch?v=Qz6XNSB0F3E)Tekst1|[![image2]](https://www.youtube.com/watch?v=Qz6XNSB0F3E)Tekst 2|[![image2]](https://www.youtube.com/watch?v=Qz6XNSB0F3E) Tekst3|



# General Information
*Brainster data science academy is here* 

> Brainster rocks

The following modules were part of data science academy : 
1. Big Data
2. Machine Learning
    - Neural Networks
    - SVM
    - PCA
3. Python
4. SQL
5. Excel


My favorite code snippet was : 

```
for ii in range(4442):
    mask_1 = (img == ii)
    Hist_ori[ii] = np.sum(mask_1) * 1.0 / N
    if ii == 0:
        # sda das dsa
        Hist_cmu[ii] = Hist_ori[ii] 
    else:
        # dsa das dsa
        Hist_cmu[ii] = Hist_cmu[ii-1] + Hist_ori[ii]
        Hist_cmu[ii] += 48
        
```
# Results 

## Results for model 1 
We have the following performance of our model :

| Training performance | Validation performance|
|-------------|----------------|
|98.8%|43%|
|23%|47%|


## Results for model 2
We have the following performance of our model :

| Training performance | Validation performance|
|-------------|----------------|
|98.8%|43%|
|23%|47%|

<img src = "documentation/Loss_train.svg" width="50%" height="50%"/>
<img src = "documentation/Loss_type.svg" width="50%" height="50%"/>

## Dataset Information
You can download the dataset : [Link](http://brainster.co)

So far we tried the folling algorithms : 
- [x] PCA
- [x] Neural Network
- [ ] ~~KNN~~ 
- [ ] KMeans
