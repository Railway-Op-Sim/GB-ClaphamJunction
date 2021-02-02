# Clapham Junction for ROS

Clapham Junction is a busy station in South-West London, on the intersection of the lines out of London Waterloo and London Victoria. The station has 17 platforms. The platforms are numbered from North to South, and are used as below:

* Platform 1 to 2 are used by London Overground.
* Platform 3 to 11 are used by South Western Railway.
* Platform 12 to 17 are used by Southern. (With the Milton Keynes service using 16/17.)

## Simulation

The included timetable contains about 2 hours of services around midday on a Monday. The number of services is slightly reduced compared to normal caused by the current global situation.

*The timetable does not perfectly reflect the real world, it has had minor edits to ensure it works with the route.*

### Important Info for Reading Line services

It should be noted that the Reading services, those using platforms 3 to 6, require some more intervention. For this route, the central two lines are fast, then the outer two are slow at Clapham Junction station.

However, the number of lines go down to three just West of Queenstown Road station. I have designed the timetable such that the London-bound services merge onto one track through Queenstown Road (through platform 1), and continue to the North-most exit point towards Waterloo.

Services from Waterloo enter on a single track and will require sorting onto the slow outer lines, or the fast inner lines.

Therefore, only platforms 1 and 3 at Queenstown Road are used for the slow stopping services.

### Useful Tips for Operation

* Despite the traffic, this route is relatively simple to operate. A lot of it can be operated using the blue automatic routes. However, I would urge you to try without these, as to make it more interesting to operate! (If you fancy something easier, the included session file has the default automatic routes, but no extra.)
* Keep an eye out for services entering the route onto signals, it's very easy to miss these, and have them wait at the signal.
* It is also useful to keep your eye on the London Overground services, as well as the Milton Keynes to Clapham Junction service, as these require to go into different platforms in Clapham Junction and may need to switch to the opposite running line early.

## Development

This project is open on the ROS GitHub which means anyone can contribute to the project. You are welcome to contribute towards this route, may that be creating further timetables, or changing aspects of the route.

The included timetable for this project was partially created with an external program called [TTbuilder](https://github.com/david-humble/TTbuilder). If you'd like to contribute to this specific timetable, have a look at the GitHub repository for more information. You are also welcome to create a new timetable using the conventional method.

If you require any assistance in creation of a timetable or submitting it through GitHub, then visit the helpdesk channel on the ROS community Discord and we'll be happy to help.
