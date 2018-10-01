# HighResMIP-storm_reader
Python code to read the netcdf formatted tropical cyclone tracks generated from HighResMIP simulations
The CMOR-like file format should be fairly self-explanatory in terms of metadata, but an example of reading this in netcdf is provided.
The script plot_storm_tracks_cmor.py can be run as a (python2.7) script. By default it should run the test first, which should generate a plot which should match that in the test_data directory. This shows the tropical cyclone tracks for the given year. There are also options to plot the genesis, lysis or maximum intensity points.


