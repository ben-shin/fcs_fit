# fcs_fit
Useful tools to process and analyze FCS data.

# data processing
The FCS software I use is from correlator.com, which produces .sin files. 
The only scripts I've written are for these formats, but I will eventually get around to doing this for Zeiss and others.
Also requires filenames to end as such:
000.sin, 001.sin, 002.sin

# Models
I have included three models so far to fit to ODEs. 
There is a folder with a script for each, as I have tried to write this to be modular.

# Iterative Fitting
This will give you the ODE fits and stats, as well as a massive number of plots and FCS formula fits.
