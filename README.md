[image]: https://github.com/francnascimento/potholesMapping/blob/master/pothole.jpg "Pothole"

# Potholes Mapping
![Pothole][image]

An algorithm that ranks potholes as the cars pass through them.

## Ideia
The idea of this experiment is to generate a solution that would help the institutions responsible for street maintenance, deciding where to allocate their resources.

In order for the solution to reach its potential, a large number of cars should make use of vibration sensors, through devices installed in the cars or an application installed on the driver's cell phone. By capturing the data, such as .csv files on [data/](https://github.com/francnascimento/potholesMapping/tree/master/data), they would be sent to a processing center where would run the algorithm of this repository, which uses the Crowdsensing concept to generate a map with the most harmful potholes to drivers.

## Description
This algorithm aims to segment and group spatial points generated by a vibration sensor during a car trip.</br>
This sensor was primarily installed on mobile phones so that you could use your hardware.</br>

* An application that has a similar result: [Physics Toolbox Sensor Suite](https://play.google.com/store/apps/details?id=com.chrystianvieyra.physicstoolboxsuite)

Due to the metric used, the algorithm detects street bumps as candidates for potholes, to solve this problem, I used a dataset of all street bumps cataloged by the city of São Paulo obtained by the [law of access to information](http://www.sic.sp.gov.br/), to disregard any detection that shares the same geographic location.

I tried to let the main notebook self explanatory, but if you have any doubts, feel free to send me an email.

## License

This project is free to use according to the [MIT License](https://github.com/francnascimento/potholes-mapping/blob/master/LICENSE) as long as you cite me and the License (read the License for more details). You can cite me by pointing to the following link:
- https://github.com/francnascimento/potholes-mapping

