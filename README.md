Healthy Human Brain Development Analysis

This repository contains a comprehensive Jupyter Notebook that explores healthy human brain development using 3D MRI scans from the IXI dataset. The analysis focuses on understanding brain structure evolution by processing and analyzing high-resolution MRI data through a systematic pipeline.
Overview

The project leverages advanced neuroimaging techniques to:

    Extract the brain from raw MRI scans.
    Register the scans to a standard space using a well-established atlas.
    Create masks for specific brain regions based on the Harvard-Oxford cortical and subcortical atlas.
    Estimate regional brain volumes.
    Perform a detailed analysis of the healthy brain development across subjects.

Pipeline Details

    Brain Extraction:
    Isolate the brain from non-brain tissues in the MRI scans to focus the analysis on the regions of interest.

    Registration with Atlas (Standard Space):
    Align each brain scan to a common coordinate system using the Harvard-Oxford atlas, ensuring consistency across subjects.

    Creating Region-Specific Masks:
    Generate masks for specific brain regions using the atlas to facilitate targeted volumetric analyses.

    Volume Estimation:
    Compute the volume of selected brain regions to assess structural differences and developmental trends.

    Analysis:
    Analyze the extracted and computed data to draw insights into healthy human brain development, including potential growth patterns and structural variations.

Credits

    MRI Scans:
    The 3D MRI scans utilized in this analysis are provided by the IXI dataset. We extend our gratitude to IXI for making these resources available.

    Atlas:
    The registration and mask creation were performed using the Harvard-Oxford cortical and subcortical atlas. Thanks to the developers for their invaluable contribution to neuroimaging research.
