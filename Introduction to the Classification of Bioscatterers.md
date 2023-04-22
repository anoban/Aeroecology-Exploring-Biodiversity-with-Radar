# ___Introduction to the Classification of Bioscatterers___
--------------------

## ___Here, we'll explore what a radar scientist might see when different types of organisms fly into the radar beam!___

- Taxonomic resolution is not a particular strength of radar technology.

- However, there are many techniques available to extract as much taxonomic information as possible.

## ___Method 1___

- This treats the radar datasets as a big "Magic Eye" puzzle. 

- The idea here is to take a step back and examine the broad categories of patterns present in the radar data using machine learning algorithms.

- This allows us to identify a broader types of species in the data.

- This diversity is characterized by different morphotypes/ groups of species with similar shapes & sizes. e.g. There might be geese, gulls, large waders, small waders and passerines among birds. Similarly, insect groups may cosnsist of locusts, butterflies, beetles, dragonflies and flies.

- This data can be passed to clustering algorithms to group the data into smaller subtypes.

- Weather signals are quite distinctly recorded as $\rho hv$ and $ZDR$ in radar data and and can easily be separated as a very distinct cluster.

- The challenging part in analyzing weather radar data is not the clsutering, but discerning what those clusters actually represent!.

## ___Method 2___

- This method uses simulations to predict what the radar might be seeing, if certain groups of organisms were present.

- Here radar data will be synthesized by simulating insect groups using computer models in a virtual radar space and this data will be studied to analyze what a radar data might look like when certain groups of insects are present at certain densities.

- VLRs and custom made birs/insect radars are better suited for this job. By focusing a specialized wavelength beam in a smaller volume, these radars collect more precise estimates on size, shape, wing beat frequency, etc..

- Algorithms can be trained on existing databases containing the above details of known insects, and the models can then be used to identify insects in new radar data.

- This makes dedicated radars very useful in local studies and in tracking flows of organisms through the air.
