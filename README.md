# DwC-A_Writer
This script transforms long-format data tables used in rocky intertidal surveys of the Marine Biodiversity Observation Network Pole to Pole of the Americas ([MBON Pole to Pole](https://marinebon.org/p2p/)) into Darwin Core Archive (DwC-A) files for publishing data in the Ocean Biodiversity Information System ([OBIS](https://obis.org/)) following instructions from this [manual](https://diodon.github.io/P2P_documents/PublishData/docs/PublishingDataIPT.html). It also generates an integrated file ready for data analysis.

To run this script, you will need to:

- Install R software.

- Create three folders in your working directory: Analysis, Data, IPT.

- Set your working directory to the location of these three folders (e.g. setwd("~/your directory").

- Save the [The DataSheet_longformat_TEST](https://github.com/diodon/P2P-templates/blob/main/DataSheet_longformat_TEST_v2.xlsx) file in the "Data" folder. This is the data table that you will substitute with your own data.

Now, just copy the code chunks below and paste them into your R console.

# Basic Setup

You need a few packages to run this code. Check that the "Data", IPT" and "Analysis" folders are created under your working directory. [The DataSheet_longformat_TEST](https://github.com/diodon/P2P-templates/blob/main/DataSheet_longformat_TEST_v2.xlsx) file should be available in the "Data" folder.
