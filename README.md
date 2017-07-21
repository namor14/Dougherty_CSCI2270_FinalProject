# Dougherty_CSCI2270_FinalProject
My Project consists of a graph of Airport classes. Each of these airports has a linked list contained within that contains each Airline�s flight map. Each connection between airports will be weighted by the number of miles between the airports. The airline�s flight map will also be a graph which will necessarily be a subset of the primary graph. A user may select two destinations and receive fastest route each airline may offer, display the contents of the Airport map (cities and airlines) or the map of a specific airline, choose a function to output which airline has the most expansive graph, and a function to output which airline offers the most direct (and thus fastest) flights. Each Airport will be a class containing a linked list of airlines present and name of city, where each airline will be a class containing their flight map. Data will be fed into the program using a text file wherein each city exists and has its available airlines contained underneath, which will be processed and read in to the vertices of the airport graph, and from there the airline maps will be subsequently constructed.