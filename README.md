# Deploying_Machine_Learning_model_on_Docker_Container_

![1_UmIpinRYfUlhvGWMsSP8cQ](https://user-images.githubusercontent.com/67523396/119843744-76a2ad80-bf25-11eb-8f2d-8b82fed955cc.png)


Deploying Machine Learning Model on Docker Container .


Docker is a useful tool working with Machine Learning. Normally We can do the below explained part with the help of Dockerfile that makes more sense, but to explain what actually is happening I used a simple approach.





Let’s Start,

To get a better understanding , I would be explaining step by step .

Step1

Trained a model and saved with a file name marks.pk1

![1](https://user-images.githubusercontent.com/67523396/119844237-e44ed980-bf25-11eb-91cd-f3df4679fea2.jpg)

Saving the model.

Step2

Transferred the file on my RHEL8 system .

![2](https://user-images.githubusercontent.com/67523396/119844322-f6307c80-bf25-11eb-9b4d-fcd580d153d8.jpg)


Step3

Installed Docker, Pulled an CentOS image from docker hub and Launched a container with detach mode .

![3](https://user-images.githubusercontent.com/67523396/119844497-19f3c280-bf26-11eb-81be-f84fd2cdff25.jpg)


Installing Docker

![4](https://user-images.githubusercontent.com/67523396/119844537-24ae5780-bf26-11eb-92b0-34af8e21842b.jpg)


Pulling an image.

![5](https://user-images.githubusercontent.com/67523396/119844733-50c9d880-bf26-11eb-9cae-78a1dc8507da.jpg)


Launching a Container.

Step4

Copying the model inside the docker Container.


![6](https://user-images.githubusercontent.com/67523396/119844938-7bb42c80-bf26-11eb-9359-8fc7a275abff.jpg)

Copying model inside docker container.

![8](https://user-images.githubusercontent.com/67523396/119845100-9dadaf00-bf26-11eb-8efd-04969e56d697.jpg)


Model has been successfully copied .

Step5

Going inside the docker Container and Installing python inside that Container.

![7](https://user-images.githubusercontent.com/67523396/119845216-b4540600-bf26-11eb-97b3-f7cd92c75318.jpg)


Going inside the docker Container.

![9](https://user-images.githubusercontent.com/67523396/119845254-bc13aa80-bf26-11eb-8009-d63c2bd803e5.jpg)


Installing python3.


Step6


Installing joblib and scikit-learn library .

![10](https://user-images.githubusercontent.com/67523396/119845305-c635a900-bf26-11eb-9db0-0c060c62180a.jpg)


Installing joblib library

![11](https://user-images.githubusercontent.com/67523396/119845352-d188d480-bf26-11eb-8baf-951c6aa03a52.jpg)


Installing scikit-learn library


Step7

Loading the model, Now We can see Machine learning model has been successfully running on top of the docker Container.

![12](https://user-images.githubusercontent.com/67523396/119845427-dd749680-bf26-11eb-9112-693bb694cf39.jpg)


Open for any queries and suggestions.

Thankyou









