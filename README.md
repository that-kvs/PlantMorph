**ASSET PREPROCESSING MODULE**

The Input Assets was taken from our previous work - Towards Digital Twin of Crops for Growth Modelling using Virtual Reality @ https://dl.acm.org/doi/abs/10.1145/3595916.3626368

Preprocessing involved removal of unwanted area, hole-filling, and genus-0 enforcement.
The resulting preprocessed meshes (CorrespondenceAlgoInput) were used in the next step.

---

**CORRESPONDENCE FINDING MODULE**

CorrespondenceAlgoInput --> Contains the preprocessed Input Meshes for which the pairwise correspondence is to be found.

landmarks.zip --> Contains the vertex ids of the landmarks used in our experiment for all pairs in the format of x1.pinned and x2.pinned, where x is the transition number. Hence 31.pinned and 32.pinned implies the meshes
                  involved in 3rd transition that are the meshes corresponding to the 3rd and 4th day.

CommonTriangulatedOut --> Contains the commonly triangulated meshes for each pair of transitions as T_00 and T_01 in the output/coarse_to_file folder of each transition pair folder.

For Correspondence Code Base (**SURFACE MAPS VIA ADAPTIVE TRIANGULATIONS**)

Refer this --> [https://github.com/patr-schm/surface-maps-via-adaptive-triangulations](https://github.com/patr-schm/surface-maps-via-adaptive-triangulations)

---

**LINEAR INTERPOLATION MODULE**
