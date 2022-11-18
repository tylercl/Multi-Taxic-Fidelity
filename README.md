# Multi-Taxic-Fidelity
Abundance data from live-dead surveys of marine invertebrates of North Carolina

Data associated with: The quality of the fossil record across higher taxa: compositional fidelity of phyla and classes in benthic marine associations

Authors: Carrie L. Tyler[1] and Michal Kowalewski[2]<br>
[1] Department of Geoscience, University of Nevada, Las Vegas, Nevada, 89154, USA, carrie.tyler@unlv.edu<br>
[2] Florida Museum of Natural History, Invertebrate Paleontology, University of Florida, Gainesville, Florida, 32611, USA<br>

This research was supported by a grant from the National Science Foundation (EAR-1243484) to Kowalewski and Tyler<br>

**The data format for each file is as follows:**

**Localities.csv** (Locality numbers correspond to the first column in the abundance data matrices)<br>
Column 1: Sample Collection Dates<br>
Column 2: Locality Number<br>
Column 3: Sample Number<br>
Column 4: Type of Dredge Equipment Deployed<br>
Column 5: Maximum Dredge Depth (meters)<br>
Column 6: Minimum Dredge Depth (meters)<br>
Column 7: Starting Latitudinal GPS Co-ordinates (decimal degrees)<br>
Column 8: Starting Longitudinal GPS Co-ordinates (decimal degrees)<br>
Column 9: Ending Latitudinal GPS Co-ordinates (decimal degrees)<br>
Column 10: Ending Longitudinal GPS Co-ordinates (decimal degrees)<br>
Column 11: Dredge Duration (minutes)<br>

**Taxa.csv** (Numeric species codes correspond to the first row of the abundance matrices)<br>
Column 1: Numeric Species Code<br>
Column 2: Taxon<br>

**Live_Assemblage_Abundance_Data.csv** (Species abundance matrix for live assemblages)<br>
Column 1: Locality Number<br>
Row 1: Numeric Species Code<br>
Column 2-246: Abundance of live<br>

**Death_Assemblage_Abundance_Data.csv** (Species abundance matrix for death assemblages)<br>
Column 1: Locality Number<br>
Row 1: Numeric Species Code<br>
Column 2-246: Abundance of dead<br>
