**steps for cricket object detection project**

1.converting the csv format into darknet yolo format(txt format)
  
  * converting each row into txt file according to image_id
  
  *suffered a lot 

  * preprocessing_images.ipynb does the job
  
  *zipped the preprocessed images and labels into cricket.zip


2.training with yolov5s model 
   
   *Yolov5_custom_training_(1).ipynb does training
   
   *trained for 500 epochs
   
   *trained model=="cricket_best.pt"



3.predicted vidoes with the model

  *zipped inside predicted_vd.zip