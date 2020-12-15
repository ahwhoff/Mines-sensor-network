# mines-sensor-network
Sensor network data from Colorado School of Mines, used for building occupancy research.

This is a dataset from the Colorado School of Mines in Golden, Colorado. It is from a sensor network of passive infrared sensors mounted in a large campus building. The sensors detect motion and the time is logged. Sensors are placed roughly every 5 meters. Data was collected for one academic school year from 2007 to 2008 and there are more than 23 million sensor readings.

Sensors were mounted in the building, and their locations are shown on the map. Each group of 4 or 5 sensors was attached to a "mote", which communicated the reading over wifi to a central mote attached to a PC.

The detections are stored in text files, called "detections[M][N].text. [M] is the mote number, 0 through 10, where 0 is the central collection mote. [N] is the number of a sensor attached to the mote.

A MATLAB script for reading the text files is included for convenience.

A complete description of the network and the data is given in the paper: J. Howard, W. Hoff, “Forecasting Building Occupancy Using Sensor Network Data,” Proc. of 2nd International Workshop on Big Data, Streams and Heterogeneous Source Mining (BigMine 13), pp. 87-94, August 2013, Chicago, Illinois.

It was also used in Jim Howard's PhD thesis, "A Method for Using Activity Recognition to Improve Ensemble Forecasting for Traffic Systems", Ph.D. thesis, Computer Science Department, Colorado School of Mines, Golden, Colorado, 2014.
