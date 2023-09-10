---
title: Hardware & Construction Methods
layout: default
---

# Hardware

## Sensors
At the heart of a successful automated plant factory, are sensors.
These are responsible for measuring the environment, and reporting those measurements back to a central controller.
This controller can then activate devices, pumps, and lights, to create the perfect environment for the plants to grow.

### Nutrient Sensors

### Growth Chamber Sensors

### Auxilliary Sensors

smoke alarm
energy usage sensors
hardware timers

Shelf
Cover
Fan
HEPA Filter
Light
Resevoir
Nutrient Solution
Growth Duct

## Housing


### Shelving


### Enclosure
Insect netting

Solid plastic sheets

Solid fabric sheets

Insulation

Glass mirror

specular (perfect) reflection vs diffuse (blurry) reflection

foil bubble wrap

The R-value of a material is a measurement of its thermal insulation capability.

### Piping

PVC pipe deteriorates in sunlight, so painting it can increase its longevity.

float valve - opens or closes depending on the level of liquid in a container.

#### Filters

Sediment filters may be useful if sourcing data from an external resevoir (e.g. a rain tank).

## Lights

Individual LED's can be purchased in bulk (5,000+) from industry suppliers.
See LM301H series LEDs.

Some bulk LED's are available on Temu.


## Actuators

The collection of sensors described above can be influenced by the outputs of electrical devices.
For example, the temperature can be increased by activating a heater, or the humidity can be increased by activating a humidifier.
Lets call the collection of devices which we can configure to adjust our various environmental parameters actuators.
The list of actuators required for a simple NFT hydroponic setup are as follows;

\item Nutrient solution pump
\item Chamber Fan
\item Humidifier
\item Heater
\item External Fan

### Pumps

Ram pump

Electric pump


### Fans
Good airflow is essential for effective respiration in the plants, which in turn is essential for maximising nutrient absorbtion, and therefore growth.
When considering fans for a hydroponic setup, there are two types to consider; fans within the growth chamber (whose purpose is to circulate air within the chamber), and fans which draw in fresh air.
We can refer to these fans as circulation fans, and inlet fans respectively.
Depending on the scale of the system's design, a single fan may meet both needs, but lets look at some science first.

During photosynthesis, plants absorb carbon dioxide (CO2) and produce oxygen (O2).
However, photosynthesis does not occur when the plant is not under light, which for optimal growth should be at least 8 hours per day.
Plants also respire, which is the process of breaking down food molecules to release energy for growth.
This (aerobic) respiration uses oxygen and releases carbon dioxide (and water), and happens constantly.
**Photosynthesis** and **respiration** are therefore in a constant battle, with one producing \ch{O2} and one using it, and one absorbing \ch{CO2} and the other producing it.
This means that when we want to optimise the conditions for both processes, we want a constant flow of air over the leaf during the day.
For night however, we need to know about **stomata**, which are a structure within plant leaves which regulate the absorbtion and release of gases.
It turns out that stomata are typically triggered to open by light, and close without it.
This means that although carbon dioxide is being produced as plants respire at night, it is not released.
To bring things back to fans, this means our fans should be on the same activation schedule as the lights.

Inlet fan

Circulation fan

#### Air Filtration
In a hermetically sealed growth chamber, or even an imperfectly sealed but reasonably secure chamber, it is a good idea to minimise the amount of bacteria, parasites, and insects in the air.
Given the optimised conditions of a growth chamber, these unwelcome additions can quickly destroy any precious organic matter therein, and may even damage some of the sensors and other actuators.
To avoid this, air filtration at the point of entry to the chamber is advised, which can be achieved in a cost effective way by applying a filter to the outside of the inlet fan.

Before slapping a COVID face mask across your inlet fan and checking this off the list, we should have a more detailed look at air filtration.
Specifically, it's important to know that when it comes to air filtration, it's all about the size of the particles which are allowed through the filter, as this ultimately determines what's on the guest list for your chamber.
A loosey goosey filter may allow particles up to 0.3\textmu{}m (micrometers aka one-millionth of a meter) through, with extremely high quality filters only allowing particles up to 0.02\textmu{}m through.

When it comes to plants however, it's also important to consider perspective.
It is overwhelmingly more likely that a single stray bug lays eggs and completely decimates your farm, than an airborne pathogen lands in the nutrient system and overruns it.
This means that while it's good to know some specifics of air filtration, in the early hobbyist stage of this endeavor it's probably enough to slap a face mask over the inlet fan and move on.

#### Gas Composition
Controlling and adjusting the composition of the air in a growth chamber requires specialist pumps, sensors, and tanks, which are each orders of magnitude more expensive than the other hardware in these notes.
For this reason, if you are deeply invested in the hydroponic way of life, then you can find more information elsewhere.

### Humidifiers


### Heaters


### Summary



