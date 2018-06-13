
# eegvis
- work in progress to visualize EEG files in python
- currently lots of experimentation - not ready for general consumption
- goal is to provide portion of software infrastructure for EEG analysis

## Scope of Project
- functions to work with matplotlib to visualize EEG
- functions to interactively plot EEGs in the jupyter notebook
- web (bokeh) applications to browse and annotate EEGs

### Status
- currently this is still experimental, but it has a useful eeg browser for the jupyter notebook
- basic filtering added, but still need notch and low-pass filter 

### To do
- [x] matplotlib EEG plotting (firstdraft)
- [x] basic bokeh EEG plotting (firstdraft)
- [x] basic montage EEG plotting, (firstdraft)
- [x] simple browsing EEG with bokeh in jupyter (firstdraft)
- [x] first filtering dropdowns added to nb browser tool
- [ ] notch and HF filters dropdowns
- [ ] allow kwargs to set plot width and height
- [ ] remove cruft from plotting in various widgets
- [ ] bokeh application to browse + annotate EEG, - still experimenting
- [ ] montage parser/loader
- [ ] scale/calibration bars
- [ ] keyboard responses, howto?
- [ ] add ability to control scale of each electrode waveform individually
- [ ] rewrite and package
- [ ] publish
- [ ] possible re-write/extend Bokeh for canvas widget

### Other notes
- Note, to respond to keyboard commands in bokeh, probably need an extension:
  see: 
  https://groups.google.com/a/continuum.io/forum/#!searchin/bokeh/keypress/bokeh/XCLqg1nyIgE/CU7lJGcuBgAJ

### Developer Install
```
    hg clone https://bitbucket.org/cleemesser/eegvis
    cd eegvis
    pip install -e .
```   
    
