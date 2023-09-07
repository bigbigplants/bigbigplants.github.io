<script type="text/javascript"
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.3/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>


<script>
    window.MathJax = {tex: {packages: {'[+]':['mhchem']}}, loader: {load: ['[tex]/mhchem']}};
</script>

<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


* Do not remove this line (it will not be displayed)
{:toc}


# Introduction

So, you want to grow plants?

This document contains my lab notes for a hobbyist/amateur botany project. This project’s aim is to establish and construct optimal growing conditions for a range of plants, with the ultimate achievement being the growth and propagation of rare and exotic species. A side quest of this project is to establish these conditions in as low-cost a way as possible, and as efficiently as possible.

In order to control the growing environment more precisely, I’ll be using a hydroponic setup. This means I can precisely control all variables relating to the plant’s growth, including specifics of their nutrient intake.

# Understanding Plant Growth

Plants, like all living creatures, require nutrients and a suitable environment to grow. This growth follows a lifecycle which can be described in distinct stages. These stages are as follows;

 - Sprout – seeds germinate and grow their first pair of leaves using the nutrients in the seed itself
 - Seedling – roots begin to develop
 - Vegetative – stems and foliage increase
 - Budding – full grown plants develop buds which may become flowers
 - Flowering – the plant produces flowers and possibly fruit
 - Ripening – the plant is fully mature and the flowers/fruits become read


## Plant Reproduction
Plants (specifically spermatophytes aka seed-bearing plants) come from seeds, which are produced by existing plants at full maturity. 
The process of these seeds turning into a plant is called **germination**, and requires specific environmental conditions to be met.
A seed which has completed the germination process (and is now a baby plant), is called a seedling.

Not all seeds from a given sample will germinate over a given period.
This can be expressed as a percentage given a period, for example, a germination rate of 80\% over 20 days means 80\% of the seeds should germinate in specific conditions after 20 days.

Flowers contain the reproductive organs of plants. That's enough detail until we get to cultivating seeds.

Not all plants produce seeds, and some (like the humble Cavendish banana) are actually sterile.

Before germination can occur, a seed must be exposed to the correct environmental conditions, which is a process known as stratification.

Not all seeds germinate.
The viability of a seed depends on several factors, most obviously the physical condition of the seed, its previous exposure to extreme temperatures/pressures, and other parameters such as its age.

## Types of Propagation
Plants don’t always follow the stages outlined above. Instead, some of the stages can be skipped depending on how the plant is propagated. Here the term propagation refers to the creation of a new and independent plant from an existing plant.
The four types of propagation are;

\item Seed propagation (plant seeds, seeds grow)
\item Vegetative propagation (cut and replant a section of an existing plant)
\item Rhizome propagation
\item Tissue cultivation



## Nutrients
There are 14 mineral nutrients which plants need to grow, which can be divided into two groups; macronutrients, and micronutrients. There are also three non-mineral nutrients which are required. Not all plants need all of the nutrients.

### Non-Mineral Nutrients
Hydrogen (H), Oxygen (O), and Carbon (C), are the three non-mineral nutrients needed for plant growth.

### Macronutrients
Nitrogen - chlorophyll production, all round growth

Phosphorus - formation of most cells, encourages blooming and root growth

Potassium - used to build protein, fruit, and combat diseases

Calcium - formation of cell walls and general strength

Magnesium - chlorophyll production and growth enzymes

Sulphur - production of protein, root and seed growth, and overall growth and cold resistance

### Micronutrients

Boron - seed and fruit development, and aids use of other nutrients

Copper - reproductive growth

Chlorine - aids metabolism

Iron - aids metabolism

Manganese - carbohydrate breakdown and nitrogen metabolism

Molybdenum - nitrogen use

Nickel - nitrogen use

Zinc - transformation of carbohydrates, sugar consumption regulation, and growth regulation

## Light

Photoperiodism is the mechanism which plants use to stay in tune with seasons

## Fertilizer
Plant fertilizer is a collection of chemical compounds which together promote healthy plant growth.
Such collections of compounds should contain all of the nutrients a plant requires, and at the right relative concentrations for the plant they are supplied to.
The exact and optimal concentrations of each compound vary both between types of plant, and between the stages of the plant's lifecycle.

Plant fertilizer can be purchased based on a three-number combination describing its contents.
E.g. 24-8-16
The first number is the percentage of nitrogen $$\ce{N}$$, the second is the percentage of phosphate $$\ce{P2O5}$$, and the third is the percentage of potash $$\ce{K2O}$$.

Fertizer grades describe...

Fertigation = adding nutrients to a crop using irrigation systems.


## Types of Plant

### Determinate vs Indeterminate Growth
Plants can either follow a set lifecycle, in which they germinate, grow, flower, and eventually die, or they can live indefinitely under the correct conditions.
Plants which follow a set lifecycle are said to be **determinate**.
Plants which can live indefinitely under the correct conditions are said to be **indeterminate**, or exhibit indeterminate growth.
Whether or not a plant is determinate or indeterminate depends on the genetic structure of the plant itself, rather than its environmental conditions.
One cannot make a plant of a determinate species live forever, and, given favourable and unchanging conditions, one cannot expect an indeterminate plant to stop growing.



### Transgenic Plants
Plants into which one or more genes from another species have been introduced into the genome, are called transgenic plants.
The creation of these plants requires a genetic engineering process of some kind, of which there are several options. 

#### CRISPR
Each living cell (in the Eukarya domain) contains a nucleus, which itself contains a molecule which describes how that cell should develop, function, grow, and reproduce.
This molecule is called **DNA**, which stands for deoxyribonucleic acid.
DNA is structured as two long strands of nucleotide bases (type of smaller molecule).
These strands wrap together based on these bases to form a large double-helix shaped molecule.
The four nucleotide bases in DNA are adenine (A), cytosine (C), guaning (G), and thymine (T).
These bases always exist as pairs along the strands of DNA, these 'base pairs' are A-T and C-G.

RNA is a molecule which can carry genetic information, and which has a number of purposes...
One purpose is to associate with enzymes and guide them to a location on another RNA (or DNA) molecule.
In CRISPR, a short sequence of nucleic acids called **guide RNA** (gRNA) helps guide enzymes to specific sections in DNA strands.
Using a word-search analogy, the gRNA is the word to find in a string of text - in this case the sequence to find in a string of DNA.

**Cas9** is an enzyme which can cut apart DNA.
The Cas9 enzyme then cuts the DNA completely at the location the gRNA identified.
When the DNA in a cell is damaged, the cell will try to repair the break.
This repair can happen in two ways.
The first is **nonhomologous** (the ends join back together).
This usually results in gene disfunction, but is useful for finding what a gene does.
The second is **homology directed repair**, which uses a strand of nucleotide bases to guide cell repair.
They do this by having a middle part of a strand (the bit you want to add to the DNA), and 'homology arms' on each side, which exactly match the DNA sequences on either side of the cut.
This directs the cell to use the middle part as a guide when repairing its DNA, thereby inserting the patch's sequence into the cell's DNA.

Clustered regularly interspaced short palindromic repeats (CRISPR).

Human DNA has 3 billion base pairs.

Chloroplasts have their own DNA.

The genotype of an organism is its complete genetic material.
The phenotype of an organism is its set of observable characteristics.

A segment of DNA which carries genetic information is called a gene.

When a cell is about to divide, DNA is condensed around histone proteins, which splits it into chromosomes.

A chromosome is a long DNA molecule which contains part or all of the genetic material of an organism.
Polyploids are organisms whose cells have more than one pair of chromosomes.


## Plant Classification
The classification of plants, and by extension of all living creatures, is an ongoing and heavily debated area of science.
A simplification is currently done according to eight levels, with each encompassing a subset of the last.
This system is always evolving and changing as new species and relationships are discovered.
That said, we have to start somewhere, so the generally accepted system we use today contains the following levels;

\item Domain
\item Kingdom
\item Phylum
\item Class
\item Order
\item Family
\item Genus
\item Species


To keep these notes shorter than several libraries worth, we'll only look at the levels which relate to plants we may eventually grow, and even then will greatly simplify their taxonomy to save space.
To begin, we start with the domain of **Eukarya**, which contains all organisms whose cells have a nucleus.
From there, we are interested in the phylum of **Plantae**, which are organisms which obtain their energy from sunlight using chlorophyll.
Once we are talking about Plantae, things are still surprisingly broad.
In the business of hydroponics, we are likely going to be focussing on the class of Plantae called **Angiosperms**, which are commonly referred to as `flowering plants'.
These plants produce seeds, and contain over 300,000 species.
Of the Angiosperms, it then becomes a bit more specific, with things like carrots being classified as being in the order of Apiales (a group of molecularly similar plants), and tomatoes being classified as being in the order of Solaneles.

Angiosperm Phylogeny Group (APG) is a 

### Visualising Classification Systems
The levels in a classification system can be represented as vertical measures on a dendrogram, or for a more interesting visual appearance a phylogenetic tree.
These trees are essentially radial dendrograms which show which species, shown on the outermost ring, are most closely related to oneanother, and where their genetic material diverges.


### Ornamental Plants
Saffron is a flower

### Edible Plants

#### Leafy Greens
Leafy greens/herbs

#### Root Vegetables
Root vegetables

Carrots = 80 days

Potatoes = 110 days

Lettuce = 50 days

#### Legumes
Lentils

Soybeans



#### Fruits
Fruits
- citrus
- berries
- banana? Pumpkin? Watermelon? Kiwi? Avocado? 

Tomato = ~60 days

Banana = 1 year

Strawberry = 1.5 years

Blueberries (bush) = 2 years

### Succulents


### Bonsai Plants
Bonsai is the art of growing and training miniature trees. This isn’t necessarily related to hydroponics, although it is possible to use hydroponics to create them. They are mentioned here as being loosely under the ‘rare and exotic’ remit in the introduction of these notes, but practically speaking the value of Bonsai plants comes from the work invested in their pruning/maintenance rather than their growth. For this reason, they won’t be discussed further.

### Special Mentions

#### Ginseng
Ginseng is the root of a plant in the Panax genus.


# Hydroponic Basics

\minitoc

Hydroponics is the growth of plants without soil. To achieve this, the soil’s role is replaced by a) an inert **growth medium**, and b) **nutrients** delivered in solution.
These components each support plant growth in different ways. Growth mediums provide physical support to the plant, and the nutrient solution provides essential chemical compounds in addition to water.

## Growth Mediums
In hydroponics, a growth medium, or substrate, is an inert substance which provides physical support to a growing plant.
Whilst these mediums are not strictly necessary, without them a set of supporting ropes/frames would be needed for each plant, so using them reduces the amount of labor/attention needed.

Growth mediums may also not be completely inert. 
Some mediums can absorb nutrients, which is expressed as their cation exchange capacity (**CEC**). 
Mediums with high CEC's are generally better as more nutrients can reach the plants where they directly contact the medium, but this can cause the medium itself to degrade.
Several popular growth mediums exist, each with their own benefits and drawbacks.

Water holding capacity (WHC)? 

Air filled porosity (AFP)

### Lava Rocks
Lava rocks can be heated which causes them to dramatically expand. 
This produces a strong and lightweight material which can be used as a growth medium.
Examples of lava rock devired growth mediums are perlite and vermiculite.
Both of these mediums are lightweight, cheap, and moderately porous.
They can also both be dangerous if not handled carefully, as their dust contains silicon dioxide.
If inhaled, this can cause physical damage and scarrification of your lungs (a condition called silicosis), which permanently lowers your lung capacity and is untreatable.

### Coco Coir
The fibrous material which forms the shell of a coconut can be processed and used as a growth medium.
This material, known as coco coir, is lightweight, organic, renewable, and has a high capacity for absorbing nutrients.
This material can however naturally contain salt, which can affect the balance of the nutrient solution being used.

### Expanded Clay
Clay can be rolled into pebbles and cooked, which results in the creation of expanded clay pebbles.
These pebbles are a less dangerous, but more expensive, version of the lava rocks described above.
This considered, they can be beneficial given their size compared to other mediums, as larger gaps allow more oxygen in the air to reach parts of the roots.
However, they can also increase the PH of the nutrient solution.

### Peat Moss
A final growth medium for consideration is called peat moss.
It is gathered from naturally occurring (and finite) peat bogs, and is more expensive than other growth mediums.
It's benefit is that it doesn't leech nutrients from the nutrient solution it's used with, however as any organic material it will decay over time.

### Blends
Any pair, or group of the growth mediums mentioned above can be combined to form a composite growth medium. 
This can bring the benefits of one while reducing the drawbacks from another.
The sky is the limit when concocting composite mediums, and some plants may grow better in different mixes (for example, tall, heavy plants like corn may do better in a heavier medium like peat moss than in perlite).

### Special Mentions
Glass beads are not a suitable growth medium because the growth medium also acts to block light from reaching the roots. 
The roots themselves can function in light, but so can algae which may compete with the plants for nutrients. 
Therefore, opaque growth mediums are preferred - not because they’re better for the plant, but because they’re worse for the algae.
Additionally, large glass beads are much heavier than other mediums, which make it harder for younger/weaker plants to grow roots.

## Nutrient Solutions
In the absense of soil, the nutrients which plants need must be delivered somehow.
One way to achieve this is through a solution provided directly to the roots of the plants.
This nutrient solution must provide everything the plant needs other than the oxygen, carbon, and hydrogen it can access in the air.

Nitrogen, Phosforus, and Potassium (NPK), are the three ‘main ingredients’ for plant growth.
NPK Fertilizer
2
Calcium Nitrate
2
Magnesium Sulphate (Epsom Salt)
1

### Preventing Algae Bloom

#### Hydrogen Peroxide

#### Beneficial Bacteria
In order to avoid algae growth and other unwanted consumers of the nutrient solution, beneficial bacteria can be added.
These bacteria will out-compete any other organisms (other than the plants) which exist in the solution, which decreases the need for maintenance in the form of solution cleaning.


### 1:250 Stock Solution
This solution is described as a good general purpose hydroponic nutrient mix for a range of plants.

\item Create solution A
	\item to 100ml of warm water, add 15ml of NPK fertilizer
	\item add 7.5ml of magnesium sulphate to the water
	
\item Create solution B
	\item to a new 100ml of warm water, add 15ml of calcium nitrate
	\item add 4ml of A for each 1L of final solution
	
\item Create nutrient solution
	\item add 4ml of B for each 1L of final solution
	


Total dissolved salts (TDS) meter measures electrical conductivity (EC). The 1:250 stock solution provides a 1900 us/cm (800ppm).

### Irrigation Cycles
While not essential, in some hydroponic configurations (e.g. Bato buckets), not providing a constinuous stream of nutrients to the plants can be beneficial.
Low irrigation can cause a build-up of salts which can damage the roots, but over-irrigation can prevent oxygen from being absorbed by the roots (depending on configuration).
- pauses in irrigation cause runoff
- runoff = roots exposed to oxygen (= good if not exposed already)
less absorbant growth  mediums = longer/more frequent irrigation cycles
more absorbant growth mediums = shorter/les frequent irrigation cycles

## Lighting
Most plants which use light to produce sugar using CO2, this process is called photosynthesis. However, not all light sources can be used for photosynthesis.

In this lab, we won’t be using any natural light from the sun, so the question is; which lights can be used instead?

To understand which lights we need, we need to know exactly how plants use light to produce sugar. 
This process begins with a 

Plants need red and blue wavelengths of visible light to grow. 

Inverse square law, luminosity decreases with the inverse square of the distance to the source.
1m away = 1m2, 2m away = 4m2, 3m away = 9m2
100W light 2m away is just 25W/m2
This only applies to distance, not bleeding off the edges.
You can reduce bleeding by adding mirrors, but you can't reduce the inverse square law.

## Electricity

### Basic Circuitry
The ampere (amp) is the unit of measure for electrical current (the speed at which electrons flow through a conductor).
Volts are the unit of measurement for the difference in electrical potential between any two points in an electrical circuit.
Ohms are the unit of measurement for eletrical resistance.

$$V = I * R$$

Watt is the unit of measurement for the rate at which eletrical energy is transferred in a circuit.

$$P = V * I$$

### Solar Panels
Solar panels generate electricity from sunlight.


### Batteries

### Biogas
Biogas is produced by the anaerobic decomposition of organic material.

The equation for anaerobic decomposition is

$$Organic Waste -> Biogas + Digestate + Water$$

## Economics
Like other types of farming, the economics of hydroponics is fairly simple: the plants you grow should be more valuable than it costs to grow them.
We can express this as an equation which covers the entire lifecycle of a plant.

startup cost + lifetime expenses - plant value = total profit

here the startup cost is self-explanatory

the lifetime expenses are the cost of the seeds, nutrients, water, and total energy (lights+heating+pumps)

and the plant value is the total value of all biomass produced.
This can be the number of plants x the number of plants grown, or for fruits it may be the total weight of sellable product.

### Worked Example

Lets say we have an all-in startup cost of \pounds1000, and our plants take a 100W bulb running for 14 hours a day.
This bulb, at \pounds0.20 per KWh will cost us \pounds8.68 per month to run.
Other energy, nutrients, and general repairs may double this to \pounds16.00 in total per month, which for a plant growth cycle of three months gives us a total lifetime cost of \pounds48.


# Hydroponic Techniques
Circulating vs non-circulating techniques
Kratky Method
The Kraty method is a non-circulating technique, and involves setting a seedling plant in 
Bato Buckets
Bato buckets, also known as Dutch buckets, are a hydroponic technique whereby nutrient solution is 
Nutrient Film Technique (NFT)
This technique involves passing a shallow stream of nutrient solution past the bare roots of 

float valve – opens if liquid level drops


## Growth Chamber
Target and tolerance values allow strict control over parameters.
Hermetically sealed (airtight) chambers allow total control over air contents and flow.
Chamber Parameters
Temperature
CO2 Level
Humidity


## Nutrient Solution Parameters
These can all be varied by growth stage
Electrical Conductivity

PH
Temperature

Water Tanks
Intermediate bulk containers (IBC) tanks are plastic with a metal housing which makes for easy transportation. 1000L IBC tanks are available, but may be overkill for non-commercial systems.

# Hardware

\minitoc

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

foil bubble wrap

The R-value of a material is a measurement of its thermal insulation capability.

### Piping

PVC pipe deteriorates in sunlight, so painting it can increase its longevity.

#### Filters

Sediment filters may be useful if sourcing data from an external resevoir (e.g. a rain tank).

## Lights


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



# Software
Configuring a hydroponics system to run automatically is possible using only hardware control switches. However, in order to gain some visibility into the health of the system, and to allow more fine-grain control over the parameters, additional software is required.
This software periodically checks the levels of different parameters by reading data from sensors, and then reacts to the values retrieved from these sensors by turning on fans, adding nutrients, and so on. These reactions to the sensor readings can be 


## Reactive Controllers

## Coordinators

## Data Storage
Each of the reactive controllers, whilst recording measurements from sensors and acting accordingly, may additionally send their measurements for storage and analysis.


# Outstanding Questions
which light specifically can be used in photosynthesis and why?
