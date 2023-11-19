# A spectral sensitivity analyser

Spectronator is a graphical tool that quantifies spectral sensitivity from
time series data. In sensory neuroscience, for example, this data
can be eyes' responsivness to differently colored light flashes,
measured by extracellular ERG electrodes.

Features
- Open CSV and Biosyst data files
- Low and highpass filtering
- Response quantification by algorithms
    - minmax
    - start-vs-max
    - start-vs-min
- Spectral responsivness plotting
- Export to CSV and PNG

## Installing

```
pip install spectronator
```

## Launching

```
python -m spectronator.tkgui
```
