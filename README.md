# Foot Sensor App
Web based application written in Python using the Plotly Dash framework for data visualization. The application presents a graphical visualization of measurements of monitoring device simulator which provides 'real time'measurements of pressure of feet on the ground of real people.


## How to run?

1. Connect to the EE VPN.

2. Build docker container:
```
$ docker build -t foot-sensor-app .
```

3. Run docker container:
```
$ docker run --name foot-sensor-app -d -p 80:8080 foot-sensor-app
```

4. Access the app at `localhost`.

5. To stop the container:
```
$ docker stop foot-sensor-app
```

6. To restart the container:
```
$ docker start foot-sensor-app
```
