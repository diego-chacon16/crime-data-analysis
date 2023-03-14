# Crime Data Analysis

# Objective 

#### Analyze the data and draw conclusions on the distribution and nature of crime in Montreal City. 

## Insights to Gather

1. What are the top 3 prevalent crimes or offenses committed in Montreal City?
2. What part of the day did most crime incidents occur?
3. Which top 5 police precincts (PDQ) got the most crime complaints?
4. Which are the top 3 PDQs that got the least crime complaints?
5. Which neighborhoods recorded the highest crime incidents and what are the crime types in these neighborhoods?
6. Which neighborhood has the most cases of murder?

## Data Description

#### The file actes-criminels.csv contains the list of criminal acts recorded by the Service de police de la Ville de Montréal (SPVM). Description of columns and translation of values:

+ CATEGORIE (list of values) : Nature of the event:
1. Introduction (eng. breaking and entering): breaking and entering a public establishment or private residence, theft of a firearm from a residence;
2. Vol dans / sur véhicule à moteur (eng. theft from/to a motor vehicle): theft of the contents of a motor vehicle (car, truck, motorbike, etc.) or of a vehicle part (wheel, bumper, etc.)
3. Vol de véhicule à moteur (eng. theft of a motor vehicle): theft of a car, truck, motorbike, snowmobile with or without a trailer, construction or farm vehicle, all-terrain vehicle
4. Méfait (eng. mischief): graffiti and damage to religious property, vehicle or general damage and all other types of mischief
5. Vol qualifié (eng. robbery) : robbery with the violence of business, financial institution, person, purse, armored car, vehicle, firearm, and all other types of robbery
6. Infraction entraînant la mort (eng. murder resulting in death): first-degree murder, second-degree murder, manslaughter, infanticide, criminal negligence, and all other types of offenses resulting in death
+ DATE (date) : Date the event was reported to the SPVM in YYYY-MM-DD format
+ QUART (list of values): Time of day the event was reported to the SPVM:
1. jour (eng. day): Between 8:01 a.m. and 4:00 p.m.
2. soir (eng. evening) : Between 4:01 pm and midnight
3. nuit (eng. night) : Between 00:01 and 8:00 a.m.
+ PDQ (numeric) : Number of the police precinct covering the territory where the event took place
+ X (spatial coordinates): Geospatial position in MTM8 projection (SRID 2950)
+ Y (spatial coordinates): Geospatial position in MTM8 projection (SRID 2950)
+ LATITUDE (spatial coordinates): geographical position of the event after obfuscation to an intersection according to the WGS84 geodetic reference frame
+ LONGITUDE (spatial coordinates): geographical position of the event after obfuscation at an intersection according to the WGS84 geodetic reference frame
