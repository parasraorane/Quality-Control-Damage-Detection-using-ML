# Quality-Control-Damage-Detection-using-ML
ML project to determine damage to object using artificially generated images
“Quality Control using Machine Learning” is an attempt to utilize 
ground breaking discoveries in computer technology to improve methods 
of Quality Control in manufacturing industry. Machine Learning can be 
used to enhance/optimize the methods used for production in the 
manufacturing industries in present. The integration of Robots which was 
one of the building blocks of the 3rd Industrial Revolution will now pave a 
way for the advent of the 4th Industrial Revolution through techniques like 
Machine Learning, Deep Learning, Computer Vision. 
This project is an attempt to use Machine Learning/Computer Vision 
to improve the efficiency of quality control after production. It tries to 
provide an alternative to the traditional expensive methodology involving 
sensors to detect imperfections with image capturing devices equipped 
with a powerful algorithm connected to the internet. 
The project makes use of the concept of “Transfer Learning”. It 
utilizes a VGG-16 model with last 3 fully connected layers added with 
additional 2 fully connected Dense layers with a Drop Out layer. Trained 
on an image dataset of 400 images of a medicine box artificially generated 
using Blender to emulate production line imagery. Training is divided into 
3 stages of 200 epochs each. The model gives the probability for 
classification to each class and on the basis of that we classify the images 
as “Intact” or “Damaged”