quadcopter
==========


In the beginning of 2014, [Hassan Bouchiba](http://www.mines-paristech.fr/Services/Annuaire/hassan-bouchiba) and I [Edouard Leurent](http://edouardleurent.com/) decided to make a quadcopter from scratch as a hobbyist robotics project.

# Parts

| Sensors   |  Actuators  |  Frame |
|-----------|-------------|--------|
| <ul><li>ITG-3200 MEMS gyroscope</li><li>ADXL345 accelerometer</li><li>HMC5883L magnetometer</li></ul> |  <ul><li>A2212-13 Brushless Motors</li><li>APC 10x4.7 Propellers</li><li>FlyFun Electronic Speed Controllers 18A</li> | <ul><li>Designed on Catia</li><li>3D printed arms</li><li>Core made of carbon plates</li> |
| ![IMU](assets/images/imu.gif) | ![Motors](assets/images/motors.gif) | See below |

{% twitter https://twitter.com/rubygems/status/425649775141068800 %}

{{< tweet 425649775141068800 >}} {{< tweet 428620119821266946 >}} {{< tweet 441351915444514816 >}}


# Media

{{< video src="videos/first-flight.mp4" controls="yes" >}}

{{< gallery >}}

# Application: the ThugDrone

Now that the drone was up and flying, my good friend [Adrien Rahier](http://adrienrahier.com) came to me with the idea to use it as an aerial graffiti platform.


We actuated a spray can with a servo-motor controlled remotely, and mounted it with a rotating joint on the quadcopter.
{{< video src="videos/can-actuation.mp4" controls="yes" >}}
{{< video src="videos/can-test.mp4" controls="yes" >}}
{{< video src="videos/can-mounted.mp4" controls="yes" >}}

The drone had to be able to automatically stay still against a wall.
![Wall stand](images/thugdrone_1.jpg)
{{< video src="videos/wall-stand.mp4" controls="yes" >}}

Here is the result.

![Thugdrone](images/thugdrone_2.jpg)
{{< tweet 477531375797800960 >}}