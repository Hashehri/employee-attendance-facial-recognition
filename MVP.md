In our project, we start with Haar cascades algorithm as a baseline; althought it is an older set of algorithms that is used in object detection and specifically face detection; in addition, prone to false positive detections, it is prominent to understand how these set of algorithms work since it was our first project working with computer vision.

Primtively, we decided to lay out our issues and loopholes in our initial problem which is taking attendence of employees just by recognizing their faces. At first, users can fool the algorithm by pointing/displaying "fake/spoofed" picture of themselves at the camera and thus will count them as attended. In order to remedy that, we tried to detect the "liveliness" of the object. Next, you tried to be more fancy and capture emotions. For now we are limiting emotions for happy, sad and netural.



### Liveness and spoofed:


### Emotions detection:
In order to build a model able to detect the emotional expression, we gathered data from Kaggle and performed the transform learning by using mobileNet and we got a disappointing accuracy score with 0.450 on the training dataset, and 0.382 on the validation dataset.

* Accuracy Score:
<img width="392" alt="Screen Shot 2022-01-09 at 10 51 23 PM" src="https://user-images.githubusercontent.com/89771282/148698607-e4457239-b353-40bd-83a6-6ffd6143bc6c.png">

* Loss Score:
 <img width="379" alt="Screen Shot 2022-01-09 at 10 51 39 PM" src="https://user-images.githubusercontent.com/89771282/148698636-60141fa2-60ad-45a9-999a-719dc6d36f2b.png">
