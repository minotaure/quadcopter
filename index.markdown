---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

In the beginning of 2014, [Hassan Bouchiba](http://www.mines-paristech.fr/Services/Annuaire/hassan-bouchiba) and I ([Edouard Leurent](http://edouardleurent.com)) decided to make a quadcopter from scratch as a hobbyist robotics project.

# Parts

| Sensors   |  Actuators  |  Frame |
|-----------|-------------|--------|
| ITG-3200 MEMS gyroscope | A2212-13 Brushless Motors | Designed on Catia
| ADXL345 accelerometer  | APC 10x4.7 Propellers | 3D printed arms
| HMC5883L magnetometer |  FlyFun Electronic Speed Controllers 18A | Core made of carbon plates
| ![IMU](images/imu.gif) | ![Motors](images/motors.gif) | See below |

{% twitter https://twitter.com/rubygems/status/425649775141068800 %}
{% twitter https://twitter.com/rubygems/status/428620119821266946 %}
{% twitter https://twitter.com/rubygems/status/441351915444514816 %}


# Media

<video width="100%" preload="auto" muted controls>
    <source src="videos/first-flight.mp4" type="video/mp4"/>
</video>

|  ![media](gallery/media_1.jpg) | ![media](gallery/media_2.jpg) | ![media](gallery/media_3.jpg) |
|-----------|-------------|--------|
|  ![media](gallery/media_4.jpg) | ![media](gallery/media_5.jpg) | ![media](gallery/media_6.jpg) |
|  ![media](gallery/media_7.jpg) | ![media](gallery/media_8.jpg) | ![media](gallery/media_9.jpg) |

# Application: the ThugDrone

Now that the drone was up and flying, my good friend [Adrien Rahier](http://adrienrahier.com) came to me with the idea to use it as an aerial graffiti platform.


We actuated a spray can with a servo-motor controlled remotely, and mounted it with a rotating joint on the quadcopter.

<video width="100%" preload="auto" muted controls>
    <source src="videos/can-actuation.mp4" type="video/mp4"/>
</video>
<video width="100%" preload="auto" muted controls>
    <source src="videos/can-test.mp4" type="video/mp4"/>
</video>
<video width="100%" preload="auto" muted controls>
    <source src="videos/can-mounted.mp4" type="video/mp4"/>
</video>


The drone had to be able to automatically stay still against a wall.
![Wall stand](images/thugdrone_1.jpg)
<video width="100%" preload="auto" muted controls>
    <source src="videos/wall-stand.mp4" type="video/mp4"/>
</video>

Here is the result.

![Thugdrone](images/thugdrone_2.jpg)

{% twitter https://twitter.com/rubygems/status/477531375797800960 %}
