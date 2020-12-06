# k-means
To run the project:
```bash
$ cmake -B build
$ cd build
$ make
$ ./kmeans
```
The csv file used in this project can be downloaded from [this link](https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2009-12.csv). Once downloaded, the csv file should be located in the main folder of the project. The k-means algorithm consider two dimensions: the `Start_Lon` and `Start_Lat` columns. The value of *k* and the number of points are by default `10` and `7000000` respectively, but they can be specified as parameters of the executable in the following ways:
```bash
$ ./kmeans k_value
$ ./kmeans k_value number_of_points
```
Once the points are loaded, you will be asked if you want to predefine the centroids or initialize them randomly.
