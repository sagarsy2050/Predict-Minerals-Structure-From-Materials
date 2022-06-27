# Predict-Minerals-Structure-From-Materials
About this file
This dataset is the collection of 3112 minerals, their chemical compositions, crystal structure, physical and optical properties. The properties that are included in this database are the Crystal structure, Mohs Hardness, Refractive Index, Optical axes, Optical Dispersion, Molar Volume, Molar, Mass, Specific Gravity, and Calculated Density.

Introduction

The term ‘dielectric’ is applied to a class of materials - usually solids - that are poor conductors of
electricity. Dielectrics are of significant technological and industrial importance, being essential
functional components of almost all electronic devices. For most of these applications, they are
required to be mechanically tough and thermally robust. The defining physical attribute of a
dielectric is electric polarizability which is the tendency for charges to be non-uniformly
distributed across a chemical bond. Most dielectrics contain dipoles due to their ionic bonds or
covalent bonds with strong ionic nature. At a macroscopic scale, this implies that an external
electric field can interact with these charges and result in various optical and electric phenomena.

**Provenance of Data. **

The names, hardness, optical axes, specific gravity, and refractive index have been scraped from Wikipedia: https://en.wikipedia.org/wiki/List_of_minerals

The crystallographic information has been scraped from the structure database at The American Mineralogist Crystal Structure Database at http://rruff.geo.arizona.edu/AMS/amcsd.php

Compared to other properties, dispersion of minerals has been hard to find. Dispersion values of
60 minerals found at: http://gemologyproject.com/wiki.

The chemical formula, molar mass, molar volume, and calculated density are available for all minerals. The availability of other properties vary.

**Chemical Formula **

The chemical formula has been parsed so that the number of each element has been separated tabulated. For example, the mineral Quartz has the formula 'SiO2' - so that the corresponding entry for the column 'Silicon' is 1 and the entry for 'Oxygen' is 2. The entries for all the other elements are 0.

In this way, the chemical formula for each mineral is converted into a vector where each column correponds to an element in the periodic table and the value corresponds to the number of atoms of the element in a formula unit of the mineral.

In addition to the pure elements, ionic species such as carbonate, phosphate, nitrate, cyanide, hydrated water, etc are also counted separately.

Molar Mass

The molar mass of the mineral is calculated by adding together the mass of each atom in a mole of the mineral.

Molar mass = Summation( no of atoms * mass of each atom)

**Molar Volume **

The molar volume of the mineral is calculated by adding together the volume of each atom in a mole of the mineral.

Molar volume = Summation( no of atoms * volume of each atom)

**Refractive Index **

The refractive index of the mineral is defined as the ratio of the speed of light in the mineral to the speed of light in free space.

This is a function of the frequency of light. The RI of blue light is not the same as the RI of red light in the same mineral. This variation is measured by 'dispersion'.

Mohs Hardness

Mohs hardness is a qualitative measure for the hardness of a mineral that is frequently used by
the geologist. Diamond (hardest mineral) is given the highest value of 10 and talc (softest
mineral) is given the value of 1. A mineral that can scratch a second mineral has a higher Mohs
hardness. In this way, all the minerals can be ranked on a relative scale of hardness. It is not exactly clear what physical parameter is represented by the Mohs Hardness. Several absolute scales for hardness such as toughness, yield strength, etc. are known from the mechanics of materials, however, none of them seem to correspond exactly to Mohs Hardness. However, this remains a very intuitive way to understand the physical property of a material.

# Operative Index
Workflow stages:

Question or problem definition.
Import protocol, acquire training and testing data.
Wrangle, prepare, cleanse the data.
Analyze, identify patterns, and explore the data.
Model, predict and solve the problem.
Visualize, report, and present the problem-solving steps and final solution.
Summary
