# Recognition_of_a_traffic_situation_in_real_time
we try to build a model which could recognize the traffic situation as human could do by using artificial intelligence like Deep Learning. This experimental analysis gives some meaningful conclusion in recognition of a traffic situation in real-time. 
# OVERVIEW
We try to develop a system which use a video footage of a street and automatically recognize or give a decision of traffic situation . Even if traffic is flowing very slowly, system could recognize the actual traffic situation efficiently. With the help of an intelligent system, the system could able to detect the number of vehicles, the change of vehicles in every second and ultimately adapt the decision for traffic situation accordingly to get the optimal outcome. We implement this system that use a deep neural network to decide  on which time of the given video footage has congested street or free street.  We also deploy this model with OpenCV  in  a Computer with an attached camera. Thus, the OpenCV  will capture images of the street at brief intervals and will use the Deep neural network to estimate traffic density and then relay this information to the computer, where further processing can be done.
By training with the help of Machine Learning techniques, the computer could to do the same by itself. We chose deep neural networks to use as the machine learning technique. Thus, given a video sequence, the task of computer vision-based traffic situation recognition is: 
1) analyze video frame sequences; 
2) estimate traffic congestion and 
3) predict the traffic situation.

The problems of common traffic Flow control system are mentioned below: 

Heavy Traffic: 
The number of exponentially increased vehicles on road causes heavy traffic congestion which is also increased in major cities. The problem for heavy traffic usually occurs in some major junctions before and after the office hour. The main effect of the problem is the wasting of time of the people on the road. 

Low traffic, but still need to wait: 
At certain junctions, often even if there is no traffic, people have to wait. Because the traffic light remains red for the preset time period, the road users should wait until the light turn to green. This problem can be solved by developing a system which detects traffic flow on each road and set timings of signals accordingly.

# TOOLS AND PACKAGES
To implement our propose system we used different python packages. Those packages are very popular and very effective in machine learning, image processing and on the others field.

1. ImageAI
2. Tensorflow
3. Pillow
4. Keras
5. Numpy
6. SciPy
7. OpenCV
8. H5py
9. Matplotlib
10. Training datasate You Only Look Once <a href="https://github-production-release-asset-2e65be.s3.amazonaws.com/125932201/1b8496e8-86fc-11e8-895f-fefe61ebb499?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20201122%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20201122T123104Z&X-Amz-Expires=300&X-Amz-Signature=d90f29005d624f365fd6c7a4536b2fd0359844e05540ab6ef8aad2a3b8e33976&X-Amz-SignedHeaders=host&actor_id=40733913&key_id=0&repo_id=125932201&response-content-disposition=attachment%3B%20filename%3Dyolo.h5&response-content-type=application%2Foctet-stream">(YOLO)</a>  

More Documantation here https://github.com/pretomksaha/Recognition_of_a_traffic_situation_in_real_time/tree/main/Documentation
