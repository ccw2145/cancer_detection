## Detect cancerous cells on pathology images with deep neural network
---
See the video where I explained my methodology: https://www.youtube.com/watch?v=H3RgC2ngo6g&feature=youtu.be

Tumor images obtained from https://camelyon16.grand-challenge.org/Data/ 

* Orginal Pathology image sample (a 'slide')  
![slide](images/slide.png)

* Cancerous region determined by pathologists marked in red  
![ground_truth](images/Screen%20Shot%202019-02-14%20at%2010.02.00%20AM.png)

* Sliding window approach to extract input patches for each slide  
![sliding_window](https://github.com/ccw2145/cancer_detection/blob/master/images/Screen%20Shot%202019-02-14%20at%2010.00.45%20AM.png)

* Patches with cancerous overlay (red regions are cancerous)   
![](https://github.com/ccw2145/cancer_detection/blob/master/images/Screen%20Shot%202019-02-14%20at%2010.00.55%20AM.png)

* Model trained with transfer learning on 7 slides (model will improve greatly with more training data)  
![model](https://github.com/ccw2145/cancer_detection/blob/master/images/Screen%20Shot%202019-02-14%20at%2010.01.27%20AM.png)

* Predicted likelihood map (the reder reigion are more likely to be cancerous)  
![predicted_result](images/Screen%20Shot%202019-02-14%20at%2010.02.29%20AM.png)

