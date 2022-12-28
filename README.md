# Modern-Sounding-Plotter
A Jupyter Notebook that creates a modern way to visualize sounding data for the purpose of environmental analysis.


    > This script was written by Kyle Gillett (@wxkylegillett) (2022)
    
    > The task of this script is to retrieve RAOB data, preform a number of calculations, and plot the data 
      on a Skew-T & hodograph.
    
    > The purpose of this script is to provide a modern, clean, clear, and concise sounding plot that makes
      for quick and easy assessment of the data for environmental analysis purposes, focused on severe weather.
      
    > It should be noted that, as with any sounding plot, many of the calculations & plotting operations here
      shoulder heavy assumptions, and these assumptions should be well understood to get the most out of any 
      sounding plot.
      
    > Numerous python libraries are utilized throughout this script, including MetPy and SharpPy's python packages. 
      Several packages here may need to be installed onto your machine to run this code. 
      
    > If you happen to run into any bugs, have questions or ideas, please message me on Twitter (@wxkylegillett) 
      or open an issue on GitHub.
      
      - MAP INSET -
    > You will be able to plot tornado tracks and storm reports from the SPC on a small map inset on the sounding. 
      Please note: tornado tracks as of 12/22 are only, available between 1950 and 2021. If you are plotting a date 
      in 2022 or 2023 - turn off plot_TorTracks. SPC Storm Reports should be availible now through June 1st, 1999. 
      Missing or bad data is possible.
    
    > You can turn on reports or tracks by setting plot_TorTracks, plot_TorReports, plot_WindReports, & plot_HailReports equal,
      to True, or off by setting them to False.
    
    
POSSIBLE FUTURE FEATURES 
  1. Radar data for map inset 
  2. Addition of RAP reanalysis data 
  3. Addition of ERA reanalysis data
  4. GOES satellite data for map inset
