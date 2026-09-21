# Larval Chemosensory Analysis Tools

This repository contains custom utilities used during analysis and figure preparation for the larval chemosensory project.

The tools were developed for internal analysis and figure-generation workflows with assistance from ChatGPT/Codex. They are provided primarily for transparency and reproducibility rather than as polished general-purpose software.

## Cell Counter

The cell-counting program was used to assist with manual and semi-automated counting of labeled cells in microscopy images.

The program records cell locations and generates summary files containing counts for individual markers and marker combinations. These outputs were used to organize and summarize cell-counting measurements reported in the manuscript.

Typical output files include:

- `cell_points.csv` — coordinates and identities of counted cells
- `cell_summary.csv` — summary information for each analyzed image or sample
- `cell_marker_counts.csv` — counts grouped by marker or marker combination

The program was developed as a lightweight alternative to performing the same counting workflow manually in software such as Fiji/ImageJ.

The counting procedure itself does not depend on a novel algorithm; the code is included to document the workflow used for the analyses.

## Figure Maker

The figure-making program is a custom utility for arranging microscopy images and other figure elements into figure panels and artboards.

It was created as an alternative workflow to manually assembling figures using Fiji/ImageJ and Adobe Illustrator.

The program was designed specifically for this project and is not intended to be a polished or general-purpose figure-layout application. Some operations may require manual adjustment, and the interface and code reflect the needs of the original figure-preparation workflow.

The Figure Maker was used for layout and presentation only and does not alter the underlying quantitative measurements.

## Development

Both utilities were developed iteratively with assistance from ChatGPT/Codex.

All outputs used for scientific analysis were reviewed by the authors, and the authors take responsibility for the resulting analyses and figures.

## Repository organization

The repository contains the source code and associated files for:

- the cell-counting workflow
- the figure/artboard-making workflow

Additional raw microscopy data and source data associated with the manuscript are archived separately as described in the manuscript Data Availability statement.

## Notes

These programs are provided as analysis provenance and supporting code for the associated manuscript. They may require modification to run outside the original project environment.
