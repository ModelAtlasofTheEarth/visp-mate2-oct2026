### submitter ORCID (or name)

https://orcid.org/0000-0003-4515-9296

### slug

visp-mate2-oct2026

### license

CC-BY-4.0

### alternative license URL

_No response_

### description

```text
This is a dummy submission to test every fields and how it interacts with the new M@TE 2 system
```

### model category

forward model

### model status

completed

### publication DOI

https://doi.org/10.5194/esurf-12-301-2024

### title

_No response_

### contributing authors

```text

```

### abstract

```text
The interplay between climate-forced sea level change, erosional and depositional processes, and flexural isostasy in deep time on passive margin deltas remains poorly understood. We performed a series of conceptual simulations to investigate flexural isostatic responses to high-frequency fluctuations in water and sediment load associated with climatically driven sea level changes. We model a large drainage basin that discharges to a continental margin and produces a large deltaic depocenter, then prescribe synthetic and climatic-driven sea level curves of different frequencies to assess flexural response. Results show that flexural isostatic responses are bidirectional over 100–1000 kyr timescales and are in sync with the magnitude, frequency, and direction of sea level fluctuations and that isostatic adjustments play an important role in driving along-strike and cross-shelf river mouth migration and sediment accumulation. Our findings demonstrate that climate-forced sea level changes produce a feedback mechanism that results in self-sustaining creation of accommodation into which sediment is deposited and plays a major role in delta morphology and stratigraphic architecture.
```

### scientific keywords

FEM, Mantle convection

### funder

```text
AuScope
Sesame street
```

### model links

```text
https://github.com/ModelAtlasofTheEarth/polanco-2024-deltas
```

### include model inputs?

- [x] yes

### model input usage, a.k.a reproducibility

```text
The input and boundary conditions for the model are structured as follows:
an input XML file where the initial and boundary conditions are set
a data folder containing the initial surface and the boundary conditions, in this case different sea-level scenarios
a series of IPython Notebooks used to run the experiment and perform some pre or post-processing tasks.
```

### include model output?

- [x] yes

### model output notes

```text
The model output data is stored in a hdf5 format. You will see a h5 folder and a series of xdmf files.

h5 folder contains the hdf5 data, all the information computed by the model are stored in these files. You will have at least the tin (surface) and flow (stream network) dataset and also the sed (stratigraphy) data if the stratal structure is computed in your simulation.

two .xdmf files for the surface (tin_series.xdmf) and the flow network (flow_series.xdmf) that read the xmf files through time.
```

### model output size

128 Gb

### model embargo?

_No response_

### software DOI/URI

```text
https://doi.org/10.5281/zenodo.1069573
https://zenodo.org/records/15128361
```

### Software source repository

```text

```

### Software version used.

```text

```

### Provide the name of the software (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

```text

```

### software authors

```text

```

### software & algorithm keywords

```text
Badlands, Python, Underworld
```

### computer URI/DOI

Gadi

### add landing page image

<img width="1038" height="586" alt="Image" src="https://github.com/user-attachments/assets/bad6e9fd-59eb-4b55-a7e6-fcef91a8aec3" />
Our simulations produce catchment areas, river lengths, and volumes of deposited sediment that are consistent with the ranges observed in continental-scale deltas such as the Mississippi and Amazon rivers. (a) Example showing the outputs from the numerical simulation showing the elevation and bathymetry (top) and cumulative flexure (bottom). Model dimensions are 4500 km x 2000 km, with a vertical exaggeration of 100x. (b) Scatter plot of river length (top) and 405 shelf width (bottom) versus catchment area from river systems. Data is from Somme et al. (2009), Nyberg et al. (2018), Blum et al. (2013, 2017) and simulations presented in this study. Pal= Paleocene, Oli=Oligocene, PM= Paleo-Mississippi. (c) Example of synthetic stratigraphy from a simulation without (left) and with flexural compensation (right).



### add an animation

https://github.com/user-attachments/assets/475df06e-5068-4c67-b780-c8912e78ffc8
The animation shows the surface and stratigraphic evolution of our simulated continental-scale deltas. We let each simulation initialize and run for 2 Myr without any sea-level fluctuations so that the delta can reach dynamic equilibrium without any disturbances in base level, then impose climate-forced sea-level changes.



### add a graphic abstract figure

[graphicAbstract.pdf](https://github.com/user-attachments/files/34454966/graphicAbstract.pdf)
Output of numerical simulations with imposed synthetic sea-level curves with different frequencies (f) showing elevation, bathymetry and discharge of the river mouth at 8 Myr. Note the difference in lateral extent, elevation due to flexural rebound, and river mouth morphology between the flexural (top) and non-flexural (bottom) cases. (b) Change of river mouth location though time for simulations where synthetic and empirical sea-level curves were imposed. Mean river mouth transit distances in the non-flexurally compensated simulations are shown in lighter shades, whereas the flexurally compensated cases are shown in darker shades. (c) Bar plot showing the frequency of the number of times where the de-trended river-mouth trajectory crosses an arbitrary point in the shelf an indicator of how often the river mouth is close to the shelf break. NF = non-flexural, F = flexural, IH = icehouse, and GH = greenhouse.



### add a model setup figure

<img width="1920" height="2580" alt="Image" src="https://github.com/user-attachments/assets/48c187f2-5b68-406a-b44a-cfcd3fc58a50" />

### add a description of your model setup

```text
Planview of model setup (top) and cross-section in the middle of the modeling domain. The initial configuration of the modeling domain resembles the topography of a natural source-to-sink system with 3400 m elevation in the headwaters, a length of 4500 km, a downstream-decreasing fluvial channel slope, and successive inflections in gradient associated with the coastal-plain to continental shelf and shelf to slope transitions. To ensure that our simulated drainage basin produces a point-source for sediment input to the marine domain we imposed a longitudinal topographic low in the middle of the model.
```

### Provide any feedback on the model submission process?

```text

```