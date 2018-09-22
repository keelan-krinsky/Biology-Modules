---
title: "River Taxonomy"
output: html_document

---

# Imports
import RiverFlowAccumulation as RFA
import RiverBranchingNetwork as RBN
# River Taxonomy
Rivers are classified, by branching network and how they accumulate flow. 

># River Flow Accumulation
>
>## Ephemeral
>Ephemeral rivers are influent, i.e. they experience a new low of water by infiltration. Such rivers are characterised by porous bed material with very little water retention, and tend to dry out periodically. In some cases they may even be dry $\geq 90\%$ of the year, filling only after intense rainfall.
>
>## Intermittent
>Intermittent rivers vary between influent and effluent, with a no net flow between the river water and the ground water, the amount of water in the river, and hence the flow rate and other related factors vary with time/season. In some instances, such as in the eastern cape they river may dry up completely in sections. 
>
>## Perennial
>Perennial rivers are effluent, i.e there is a net inflow of ground water into the river, they are present through the year. 
>
>## Artificial
>Artificial water channels occur in the form of wears, which land owners use to divert water from rivers to croplands or orchards. 

># River Branching Network
>In general when classifying streams within a drainage network, a number is assigned to each stream to reflect the drainage area the channel dimensions and the discharge volume.
>
>## Strahler method
>Numbers are assigned in a cumulative fashion based on the confluence of streams. A second order stream is characterised as forming from/lying directly below the junction of two first order streams, or the junction of a first order and a second order stream. A third order stream is formed from the junction of two second order streams and so forth. A stream must junction with another stream of equivalent order to result in the formation of a higher order stream, because otherwise there would not be a significant increase in the amount of water in the higher order stream forming the junction. These orders reflect the basic rules of drainage basin geometry. 
>


# Appendix

