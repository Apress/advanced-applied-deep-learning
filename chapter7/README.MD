# Where to download the files

You can download a zipped file of the following files (the ones used in the Jupyter notebook)

- ```coco.names``` (642 bytes)
- ```yolov3.cfg``` (8 Kb)
- ```yolov3.weights``` (248 Mb)

Download link: [http://toe.lt/q](http://toe.lt/q). 

# Original download link for weights and cfg file

The weigts can also be downloaded directly from the yolo website 

[https://pjreddie.com/yolo/](https://pjreddie.com/yolo/)

there you will find also different versions of the weights, that has been generated training different models on different datasets.

# Image file

The file used in the notebooks is contained in this directory ```table.jpg```. Put it in the directory of your choice and don't forget to update the code in the notebook

    image = cv2.imread("images/table.jpg")
    imageorig = cv2.imread("images/table.jpg")
    
Change ```image/``` to where the image is.
