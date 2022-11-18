# Multi-Taxic-Fidelity
Abundance data from live-dead surveys of marine invertebrates of North Carolina

Data associated with: The quality of the fossil record across higher taxa: compositional fidelity of phyla and classes in benthic marine associations

Authors: Carrie L. Tyler[1] and Michal Kowalewski[2]

[1] Department of Geoscience, University of Nevada, Las Vegas, Nevada, 89154, USA, carrie.tyler@unlv.edu

[2] Florida Museum of Natural History, Invertebrate Paleontology, University of Florida, Gainesville, Florida, 32611, USA

This research was supported by a grant from the National Science Foundation (EAR-1243484) to Kowalewski and Tyler

The data format for each file is as follows:

**Localities.csv** (Locality numbers correspond to the first column in the abundance data matrices)

Column 1: Sample Collection Dates
Column 2: Locality Number
Column 3: Sample Number
Column 4: Type of Dredge Equipment Deployed
Column 5: Maximum Dredge Depth (meters)
Column 6: Minimum Dredge Depth (meters)
Column 7: Starting Latitudinal GPS Co-ordinates (decimal degrees)
Column 8: Starting Longitudinal GPS Co-ordinates (decimal degrees)
Column 9: Ending Latitudinal GPS Co-ordinates (decimal degrees)
Column 10: Ending Longitudinal GPS Co-ordinates (decimal degrees)
Column 11: Dredge Duration (minutes)

**Taxa.csv** (Numeric species codes correspond to the first row of the abundance matrices)

Column 1: Numeric Species Code
Column 2: Taxon

**Live_Assemblage_Abundance_Data.csv** (Species abundance matrix for live assemblages)
Column 1: Locality Number
Row 1: Numeric Species Code
Column 2-246: Abundance of live

**Death_Assemblage_Abundance_Data.csv** (Species abundance matrix for death assemblages)
Column 1: Locality Number
Row 1: Numeric Species Code
Column 2-246: Abundance of dead
