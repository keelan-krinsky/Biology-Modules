---
title: "Rivers"
output: html_document

---

# Imports

import RiverTaxonomy as RT

import RiverLongitudinalTrends as RLT 

import RiverDischarge as RD

import StreamSlope as SS 

import RiverLongitudinalDivisions as RivLD

import RiverScaleDivision as RSD

import RiperianZone as RZ

# Rivers

## Background

### Important Measurements

># River Discharge
>Discharge is the rate at which a volume of water flows past a given point. 
>
>## Units
>Discharge is measured in Cumecs ($m^3s^{-1}$)
>
>## Measurement.
>To measure the discharge in a stream, the stream is divided horizontally into rectangular cells of an equal width. The depth at the start and end of each cell is then measured and the two value averaged to give an estimate of average depth. A flow device is then used to measure the velocity of the water moving through each cell. The sum of the discharge across all cells is the transect discharge. 
>
>### Equation
>$Q=\displaystlye\sum _{i=1}^{n}w_id_iv_i$
>
>### Remote measurement
>Discharge is often measured remotely with the use of gauging wears. Gauging wears temporarily stop the flow, measuring the height of the water which builds up behind the temporary obstruction, and the slight drop in stream height just in front of the barrier. This difference in height is then used to calculate the water velocity, using a, so a racing curve, which gives a standard relation between height and velocity. (basically a standard curve. Gauging wears are placed at strategic points across the catchment. A logger is used to record this flow data every hour or half hour for months, and all the collected data is stored until an engineer comes to retrieve it.
>
>Discharge should be measured a bit before the wear as the wear retards the flow. Additionally riffles/rapids should be avoided as there is too much turbulence within them, a smooth deep laminar flow is best. This provides a more accurate measure of water volume. 
>
> > NOTE: in the Eastern cape gauging wear are only present on main dams, as all other gauging wears in this region were decommissioned in the 80s
>
>
>§§§ Discharge. 
>Dishcarge is the rate at which a volume of water flows pst a pomt over a unit of time. 
>
>$Q=m^3s^{-1}$
>NOTE: $m^3s^{-1}$ are reffered to as cumecs (?) 
>
>#### Measurement.
>See in back of prac handout one 
>
>The stream is divided into equal width rectangular cells vertically downwards. 
>The width and the depth of each cell will be measured. (the depth at the start and end of each cell is measured and averaged). A flow device is then used to             measure the vvelocity of the water going through each cell. The sum of the discharge across all cells is the transect discharge. 
>
>$Q=\displaystlye\sum _{i=1}^{n}w_id_iv_i$
>
>Dishcarge is often ,easured remotely with the use of gagine wears, which temporariily stop the flow and thenmeasure the height of the stream. Such wears are places 
>at strategic ponyts across the catchment. 
>
>(eatern cape only on main dams, as others decomissioned in the 80s
> 
>A logger logs the flow depth for every hour or half hour for months, and then the data will be retrieved by an engineer. However the data is only height , so a          racing curve, which has a relation of measures of height and discharge. (basically a standard curve. ))Discharge should be measured a bit before the wear as the         wear retards the flwo, also in a riffle/rapid there is too much turbulance, so a smooth depp laminar flow is best. N
> 
>NOTE: the volume is the same thrtought but some areas are more accurate to measure. 
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>
>

># Stream Slope
>The stream slope is the vertical drop along a horizontal distance, it measures how altitude changes along a stream from head waters to mouth. 
>
>$SS=\frac{\text{elevation at contuor A}-\text{elevation at contour B}}{\text{length of stream between contours}}=\frac{\text{Vertical distance}{\text{Horizontal distance}}$
>
>Stream slope is expressed in meters per kilometer, meters per 100 kilometers, or as a percentage or ratio.
>

># River Taxonomy
>Rivers are classified, by branching network and how they accumulate flow. 
>
> ># River Flow Accumulation
>>
> >## Ephemeral
>>Ephemeral rivers are influent, i.e. they experience a new low of water by infiltration. Such rivers are characterised by porous bed material with very little water retention, and tend to dry out periodically. In some cases they may even be dry $\geq 90\%$ of the year, filling only after intense rainfall.
>>
> >## Intermittent
>>Intermittent rivers vary between influent and effluent, with a no net flow between the river water and the ground water, the amount of water in the river, and hence the flow rate and other related factors vary with time/season. In some instances, such as in the eastern cape they river may dry up completely in sections. 
>>
> >## Perennial
>>Perennial rivers are effluent, i.e there is a net inflow of ground water into the river, they are present through the year. 
>>
> >## Artificial
>>Artificial water channels occur in the form of wears, which land owners use to divert water from rivers to croplands or orchards. 
>
> ># River Branching Network
>>In general when classifying streams within a drainage network, a number is assigned to each stream to reflect the drainage area the channel dimensions and the discharge volume.
>>
> >## Strahler method
>>Numbers are assigned in a cumulative fashion based on the confluence of streams. A second order stream is characterised as forming from/lying directly below the junction of two first order streams, or the junction of a first order and a second order stream. A third order stream is formed from the junction of two second order streams and so forth. A stream must junction with another stream of equivalent order to result in the formation of a higher order stream, because otherwise there would not be a significant increase in the amount of water in the higher order stream forming the junction. These orders reflect the basic rules of drainage basin geometry. 
>>
>

># River Longitudinal Trends
>
>## Slope
>The average slope (and altitude), trends to decrease moving down a river, as the first order streams of headwaters are  as usually in high altitude, mountainous regions. A significant exception to this trend is in the highveld in which the rivers drain a huge high altitude plateau. 
>
>
>## Channel width
>The channel width tends to increase moving down the river
>
>## Discharge volume
>The discharge volume tends to increases moving down the river, as streams join up and the collective discharge accumulates. 
>
>## Substrate grain size.
>Particle size of substrate, in particular bed substrate, tends to decrease moving down the river, essentially through the action of a filtering process. 
>
>## Depth
>The depth of the water channel tends to increase moving downstream, however this trend is subject to significant local variation 
>
>## Width
>The width of the water channel tends to increase moving downstream, however this trend is subject to significant local variation 

># River Longitudinal Divisions
>
>## Upper Reaches
>
>### Hydrology
>### Physical conditions
>
>#### Slope
>In general rivers have a very steep gradient by their source, with waterfalls in their upper streams.
> 
>#### Bed material
>The bed material in upper reaches is normally more rocky, and this combined with the shallow water depth frequently leads to the formation of ripples.
>
>### Ecology
>
>#### Riparian zone
>In almost all areas the riparian zone is heavily forested, with overhanding canopy with numerous branches extending over the river. 
> 
>## Lower Reaches/ Lowlands
>
>### Hydrology
>
>#### Flow rate
>In the lower reaches the flow rate is very slow.
>
>### Physical conditions
>
>#### Turbidity
>Lowland rivers are generally very turbid, due do fine suspended particles
>
>#### Bed material
>Lowland rivers have a more uniform bed composition that headwater streams, consisting mainly of sand and silt. 
>
> ># River Zones
>>Generally speaking a river can be divided into three distinct zones, which graduate into each other, normally with not distinct borders. 
>>
> >### Production Zone
>>The production zone contains 1st-4th  order streams, and received water primarily from run off. As a result of the high levels of runoff bring with them a good deal of sediment. 
>>
> >### Transfer zone
>>The transfer zone receives water predominately from upstream, and moves the majority of this water down stream, typically with no large exchange of water between the river and the terrestrial environment occurring. 
>>
> >### Storage Zone.
>>In the storage zone the flow of water is so slow that suspended substrate is alluviated in mass to form terrestrial environments, i.e. sandbanks/islands, within the water channel itself. 
>>
> >### General trends
>>there are several general trends when moving from the head waters downwards. 
>>
>> #. Bed material grain size progressively decreases. 
>> #. Accumulated discharge increases. 
>> #. Depth and width increases. (However the depth does not change much and always shows a large local variation.)
>>
>>NOTE: Velocity does not significantly increase, as in any given section the ration of fast water to slow water remains relatively constant. 
>>
>>
> >#### Storage Zone.
>>In the storage zone the flow of water is so slow that suspended substrate is alleviated en mass to form terrestrial environments (sandbanks/islands) within the water channel. 
>>
>>
>

># River Scale Divisions
>
>### System
>A strech of river above a kilometer forms a system. 
>
>### Segments
>Segments are rough $10^2m$ stretches of a system. Large Predatory Fish tend to move between segments at different stages of their life  cycle.
>
>### Reaches
>Reaches are stretch of river of a $10^1m$ magnitude. 
>
>### Riffles
>Rifles are stretches of river of a $10^0m$ magnitude. Different fish species tend to spend most of their time in different habitats.When the water level in the river is low the difference between environments is much more pronounced. More diverse flow conditions result in more habitats for macro-invertebrates. Deep pools in sequence with shallow rifles form vertical meanders.
>
>#### Pool
>Pools are deep and contain slow flowing water. In pools the base material tends to be fine sediment. 
>
>#### Riffles
>Riffles are fast flowing and shallow containing turbulence created by the uneven bed. The base material in riffles tends to contain large rocks in sand. 
>
>#### Runs
>The base material in runs tends to be gravel. 
>
>
>### Microhabitats
>Microhabitats occur at a magnitude of $10^{-1}m$ magnitude. Insects live in specific habitats such as moss covered boulders, or sandy rock etc. 
>

># Riperian Zone
>A raperian gabitat is the area between the waters endge and the boundary where the water no longer influences the terrestrial environment. In upper water the raparian zone is very narrmow, but further down stream (in the storage zone) The raperian zone becomes very extensive, especially due to the formation of terrerial environments dirrectly in the water channel from alluviation. In the storage zone terraces, (which are ancestral flood plane deposits) surround the current flood plain deposit, in which the steam channel lies. Such areas are referred to as backstamps. Endorheic wetlands form around stream separated from it by berms, (alluvial) deposits. 
>
>NOTE the presence of alluvial deposits (e.g. terraces and benches) adjacent to the active channel is a good indication of zone changes. 
>(ise a third order is belw the junction of two second order streams.
>These orders reflect the basic rules of drainage basin geometry.  
>Firstly the average slope is decreasnig (normally) as first order are in moutnaous/high regions, a exception is the highveld which drains a huge high up plateu.
>The channel width tends to increase wiith the
>discharge volume increases . (as two streams are joining. )
>Particle size of substrata decreases, (through a filtering porcess, )
>

# Appendix

