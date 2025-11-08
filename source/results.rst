Explore Result
==================
A brief usecase for each of the results is provided in our paper (*H. M. A. Mohit Chowdhury, Mattie Fuller and Oluwatosin Oluwadare. Robin:  An Advanced Tool for Comparative Loop Caller Analysis Leveraging Large Language Models (under review)*).

For a comprehensive expalanation and interepretation of eah plots, please review: **Chowdhury, H.M.A.M., Boult, T. & Oluwadare, O. Comparative study on chromatin loop callers using Hi-C data reveals their effectiveness. BMC Bioinformatics 25, 123 (2024)**. `https://doi.org/10.1186/s12859-024-05713-w <https://doi.org/10.1186/s12859-024-05713-w>`_ 


Overlap
-------
    * Overlap defines the precentage of common and unique results among the tools.
    * Maximum number of overlaps allowed is 3.

    .. raw:: html

      <video controls style="max-width:100%; height:auto;">
         <source src="_static/video/overlap.mp4" type="video/mp4">
      </video>


Regression
----------
    Regression plots shows the stastical correlation among the tools considering the resolutions.

    * It shows the Average Bin Size (of the number of bins) vs. Resolution. 
    * It shows the Average Bin Size (of the number of bins in KB) vs. Resolution. 
    * It shows the regression plots.
    * It shows the category regression plots.
    
    .. raw:: html

      <video controls style="max-width:100%; height:auto;">
         <source src="_static/video/regression.mp4" type="video/mp4">
      </video>


Protein (e.g. CTCF)
-------------------
    * Protein plots are the biological validation plots. It is available per resolution uploaded by the user.
    * It contains line plot explaining the Recovery Rate in every 1000 loops for each tool. It also contains the bar plot showing the total Recovery Rate.
    * The other two bar plots are Recovery Efficiency Rate plots for every individual total score and low vs. high resolution scores.
    * Users can observe other tabs named with the protein as much as user provide them. User can toggle tools, view specific resolution results.
        
    .. raw:: html

      <video controls style="max-width:100%; height:auto;">
         <source src="_static/video/protein.mp4" type="video/mp4">
      </video>


HiGlass
-------
    * HiGlass has different features. Here, we demonstrate a little features. User referred to go through the full document `here <https://higlass.io/>`_.
    
    .. raw:: html

      <video controls style="max-width:100%; height:auto;">
         <source src="_static/video/higlass.mp4" type="video/mp4">
      </video>


Data
----
    * Data tab will help users to view their all uploaded data and they can be downloaded for furthur usecase.

    .. raw:: html

      <video controls style="max-width:100%; height:auto;">
         <source src="_static/video/data.mp4" type="video/mp4">
      </video>