---
title: "MCCF Image Analysis"
layout: textlay
excerpt: "MCCF Image Analysis"
sitemap: false
permalink: /imageanalysis/
---
# Image Analysis

The Molecular Cytology Core Facility can assist with all types of visualization and image analysis tasks from software training to novel algorithm development.

## Common Tasks

- Cell Tracking : Imaris or Fiji/TrackMate can be used to track cells in 2D or 3D. Nuclear labels are a more reliable target for reliable tracking, but tracking can also be performed on florescent cytoplasmic labels and brightfield images. 3D visualization is easier in Imaris while automation can be easily scripted in FIJI. Tracking results can easily be exported from FIJI for post processing and visualization in MATLAB. Expression levels over time can be quantified along with cell tracking.  

- Analysis of Neuron/Vessel/Filament Structures: Neuron, Vessel, and Filament structures can be traced automatically or manually in 3D in Imaris. 2D/3D tracing can be performed with various FIJI plugins or MATLAB.

- Cell Counting, Colocalization: Cell counting and expression quantification can be performed using standard Core scripts in FIJI or using CellProfiler pipelines that can be modified and applied by users with no programming. 

- 3D segmentation: Segmentation and measurement of various labeled structures can be performed in Imaris or FIJI. Machine learning based segmentation can be performed using the Wekaseg plugin in FIJI or in Ilastik. 

## Commonly Used Software:

### Open Source

- [FIJI/ImageJ](https://imagej.net/fiji) All purpose image analysis and visualization software with diverse plugins for almost every usecase.

- [QuPath](https://qupath.github.io/) Free software for visualization and interactive image analysis performed directly on high resolution whole slide images.

- [CellProfiler](https://cellprofiler.org/) A programming free interface for constructing image analysis pipelines by layering image processing and measurement steps.

### Commercial (available on our workstations, bookable through [iLab](https://ilab.mskcc.org))

- [CaseViewer](https://www.3dhistech.com/research/software/digital-microscopes-viewers/caseviewer/) Software for opening, viewing and navigating whole slide microscopy images.

- [Imaris](https://imaris.oxinst.com/) Interactive visualization and image analysis package with tools for segmenting and tracking most 3D structures. 

- [Matlab](https://www.mathworks.com/products/matlab.html) General purpose programming language, often the quickest way to prototype novel image analysis methods or preprocessing methods and to develop novel data analysis routines.

