# swiss-transport-flows

Submission for the make.opendata.ch camp spring 2012.

Demo: http://flows.transport.opendata.ch
Wiki: http://make.opendata.ch/wiki/project:transport:transportflows

## Project

The idea is to map public transportation flows in Switzerland. The focus is on visualizing the network of SBB CFF (trains, S-Bahn). This visualization was later animated and published by the NZZ: [Die Eisenbahn, die nie ganz schläft](http://www.nzz.ch/aktuell/inland-sommerserie-schweizer-karten-interaktiv/sbb-fahrplan-pulsierender-verkehr-1.18129777 "http://www.nzz.ch/aktuell/inland-sommerserie-schweizer-karten-interaktiv/sbb-fahrplan-pulsierender-verkehr-1.18129777").

## Purpose of the project

1.  Learning: Facts about the train network are revealed that are not obvious and surprise the consumer
2.  Aesthetics: the result is visualized in a creative and innovative way and shows the dynamic of the train network
3.  The visualization allows user interactions to have a deeper look into some details
    

## Team

-   Benjamin Wiederkehr
-   Joel Bez
-   Sylke Gruhnwald
-   Dagmar Muth
-   Patrick Stählin
-   Patrick Zahnd
-   Ilya Boyandin
-   Thomas Preusse

## Inspiration

-   [www.swisstrains.ch](http://www.swisstrains.ch "http://www.swisstrains.ch")
-   [www.villevivante.ch](http://www.villevivante.ch "http://www.villevivante.ch")
-   [http://zugmonitor.sueddeutsche.de/#/30.03.2012-17:17/](http://zugmonitor.sueddeutsche.de/#/30.03.2012-17:17/ "http://zugmonitor.sueddeutsche.de/#/30.03.2012-17:17/")
-   [http://www.newsorator.com/what-is-a-credit-card/](http://www.newsorator.com/what-is-a-credit-card/ "http://www.newsorator.com/what-is-a-credit-card/")
    

## Data

swisstrains. The data consists of train-schedules and a mapping from single trains to tracks on a map. As the track-data has been traced from Google Imagery we don't consider this data Opendata. Getting the tracks from OpenStreetmap would be a nice project for another Hackday.

## Solution

Demo: [http://flows.transport.opendata.ch/](http://flows.transport.opendata.ch/ "http://flows.transport.opendata.ch/")

Source: [https://github.com/interactivethings/swiss-transport-flows/](https://github.com/interactivethings/swiss-transport-flows/ "https://github.com/interactivethings/swiss-transport-flows/")

Resource: [http://www.fixithere.net/dvla-contact-number/](http://www.fixithere.net/dvla-contact-number/ "http://www.fixithere.net/dvla-contact-number/")

![](http://make.opendata.ch/wiki/_media/project:transport:2012-03-31_1517_zurich_arrivals_departures.png)

![](http://make.opendata.ch/wiki/_media/project:transport:2012-03-31_1515_transportation_flows_top_cities.png)

![](http://make.opendata.ch/wiki/_media/project:transport:2012-03-31_1506_transport_biggest_cities.png)

## The following parameters were of interest for us

Time

-   Departure
-   Arrival
-   Speed: average speed and speed changes on a train’s track
    

Track

-   A train’s track on the map
-   Stops per track
    

Train capacity

-   Degree of capacity utilized (is the train crowded or not?)
-   Length of trains ⇒ number of passengers
    

Stations

-   Degree of tracks occupied (per hour, per day)
-   Stations as intersections (how important is a station for the network?)
    

Train types

-   Different types: IC, S-Bahn, Interregio etc.
-   Name of a specific train (IC123)
    

Delays

-   Per train
-   Per track
-   Waiting times of trains in a station
