
Decoders

##Data set is small but has 33 attributes. 

Assignment is to create a model to classify if return is good or bad. Please provide for exploratory data exploration,and model and metrics.


About Dataset
This radar data was collected by a system in Goose Bay, Labrador. This system consists of a phased array of 16 high-frequency antennas with a total transmitted power on the order 
of 6.4 kilowatts. The targets were free electrons in the ionosphere. "Good" radar returns are those showing evidence of some type of structure in the ionosphere. "Bad" returns are those that do not; 
their signals pass through the ionosphere.
Received signals were processed using an autocorrelation function whose arguments are the time of a pulse and the pulse number. There were 17 pulse numbers for the Goose Bay system. Instances in this databse are described by 2 attributes per pulse number, corresponding to the complex values returned by the function resulting from the complex electromagnetic signal.

Attributes

atr1 to atr34 : Rader Data (float)
target : Categorical Data ['g' for Good and 'b' for Bad]

Total Instances

This Dataset has total 351 rows.
