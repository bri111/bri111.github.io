---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "Cotton"
date: 2022
published: true
labels:
  - AI
  - Machine Learning
summary: "A small robotic robot from Zumi developed for Fall 2022 AI4All Programˆ."
---

<img class="img-fluid" src="../img/cotton/cotton-header.png">

Computer vision is a field of AI that allows computers to understand what pictures and videos mean and take actions based on what it sees. This can be used to detect objects, collect data, or even perform some human tasks. This is why car manufacturers are starting to use computer vision in their cars. Self driving cars are growing in popularity because of their many uses and safety features. For example, Teslas have auto stop features if the car almost hits something. Our group wants to introduce self-driving cars by demonstrating how a mini car would use computer vision. 

The targeted audience for this project are those who are interested in learning about the applications of the codes we’ve been talking about into real life situations with the help of Zumi bots as our models. 

Our problem we wanted to address is that modern computer vision technologies is changing the way we view self-driving cars. The idea of a self-driving car is innovative but there are still features in these types of cars that are not perfected. What are ways to spread knowledge and demonstrate computer vision for the general public?

```cpp
zumi.mpu.calibrate_MPU() // calibrates the zumi's position
camera.start_camera() // starts zumi camera
   while True:
      image = camera.capture()
      predicate = knn.predicate(image)
      screen.draw_text_center(predict)
      
      if (predicate == 'Green'):
        zumi.forward()
      elif (predicate == 'Red'):
        zumi.stop()
     camera.close

```

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>
