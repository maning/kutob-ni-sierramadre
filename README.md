# kutob-ni-sierramadre

## About

A collection of Jupyter notebook to analyze sensor data from DOST's weather and stream/river monitoring stations.
The data was [collected](https://github.com/mbasa/dostSensor/) from the old Project NOAH API.  It contains over 30 million records between 2013-2015.

## Setup

```sh
# Clone repo
git clone git@github.com:maning/kutob-ni-sierramadre.git
cd kutob-ni-sierramadre

# Setup your python environment
virtualenv -p python3 .env
. .env/bin/activate
pip3 install -r requirements.txt

# Run jupyter notebook
jupyter notebook
```

## TOC

* [Loading CSVs to AWS Athena](loading-to-athena.ipynb).
* [WIP][Connecting Athena to Jupyter notebook](athena-to-pandas.ipynb).

### What's in a name

Roughly translated as "foresights by Sierra Madre".  [Sierra Madre](https://en.wikipedia.org/wiki/Sierra_Madre_(Philippines)) is the longest mountain range in the island of Luzon, Philippines.  Home to diverse flora and fauna and the headwaters of many rivers in the island.  Locals in my hometown usually say: *"Ang lakas ng ulan sa Sierra Madre kaya baha na naman!"* 
