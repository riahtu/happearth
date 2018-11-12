
<div align="center">
  <h1>Happearth</h1>
  
  <h2> <a href="https://happearth.herokuapp.com"> See the live project.</a></h2>
  <p>Software prototype of a home energy monitor to be used by residents in housing communities to lower the energy consumption, also there is  and app connected to the project current avaliable in playstore. The software is connected to IoT devices such Alexa Amazon and Ecobee Thermostat. Some other technologies used were Docker, Django and Nginx..</p>
  <a href="https://play.google.com/store/apps/details?id=me.danieldev.happearth" align="center">
    <img src="https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png" width="150" height="60" alt="Get it on Google Play" border="0">
  </a> <br>

  <img src="metadata/collage-happy-1.jpg" width="550" height="400" alt="collage1" border="0"><br><br>
  <img src="metadata/collage-happy-2.jpg" width="550" height="400" alt="collage1" border="0"><br>

</div>


<h2> <a href="https://happearth.herokuapp.com/monitor/"> See the monitor.</a></h2>



Video Demos
---------
  * [Walkthrough Normal User](https://www.youtube.com/watch?v=siDfX1V4jSY&list=PL2Adzu29QFW7e-ttRDT6EJDtKi215Ngkb&index=1)
  * [Walkthrough Admin User](https://www.youtube.com/watch?v=CWdd_COiLT0&list=PL2Adzu29QFW7e-ttRDT6EJDtKi215Ngkb&index=2)
  * [Walkthrough App Android](https://www.youtube.com/watch?v=n7ys87E8FRs&list=PL2Adzu29QFW7e-ttRDT6EJDtKi215Ngkb&index=3)
  * [Feature Control with speech](https://www.youtube.com/watch?v=yTx8MR5NCJs&list=PL2Adzu29QFW7e-ttRDT6EJDtKi215Ngkb&index=5)
  * [Feature Alexa](https://www.youtube.com/watch?v=f5FYRmnlgf4&list=PL2Adzu29QFW7e-ttRDT6EJDtKi215Ngkb&index=4)

Installing
----------
There are three different ways to deploy the application in the server, see below the details.

#### Docker Compose
```sh
  $ git clone https://github.com/xdanielsb/Happearth.git repo/ && cd repo/
  $ docker-compose build
  $ docker-compose up -d

  # Do you want to distribute the network traffic across multiple instances? LOAD BALANCING = <3
  $ docker-compose scale app=NUM_SERVERS_YOU_WANT

  # Now open the browser in localhost:8080
```

#### Virtual env
```sh
  $ git clone https://github.com/xdanielsb/Happearth.git repo/ && cd repo/
  $ virtualenv ~/happearth --python `which python3.6`
  $ source ~/happearth/bin/activate
  $ pip install -r requirements.txt
  $ python manage.py runserver

  # Now open the browser in localhost:8000
```

### TroubleShooting Videos
  * [Docker Walkthrough Installing](https://www.youtube.com/watch?v=21nelITwbRs&list=PL2Adzu29QFW7e-ttRDT6EJDtKi215Ngkb&index=6)
  * [Virtualenv Walkthrough Installing](https://www.youtube.com/watch?v=_Cs-qPv-NhE&list=PL2Adzu29QFW7e-ttRDT6EJDtKi215Ngkb&index=7)


<p style="font-size=7">
Note: if you are running in not secure mode change to debug mode.
</p>

Architecture Application
------------------------
<p align="center">
    <img src="metadata/model.png" alt="Model" border="2" />
</p>

Developer
----------
* Name : Daniel Santos
* Email : dfsantosbu@unal.edu.co

License
-------

This project is licensed under the GPL V3 License - see the [LICENSE](LICENSE) file for details
