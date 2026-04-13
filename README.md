# Visual prosthesis simulation

This repo generates a 4-panel figure illustrating why electrode arrays do not produce “pixel vision”:

A) Input scene image  
B) Scene-sampled electrode activation pattern  
C) Neural recruitment (non-Gaussian current spread)  
D) Percepts (Gaussian field, inverted: white activation on black)

The script takes a grayscale or color image (PNG/JPG), converts it to a normalized scene (white=1, dark=0),
samples it on an electrode grid, and renders panels for different array sizes (e.g., 10×10 and 50×50).

## Install
```bash
pip install -r requirements.txt
