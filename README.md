# TDM-Value-Of-Time-Calculation

See attached value-of-time calculation notebook. Currently the notebook calculates values of time for the 2019 1-year ACS person file for WFRC PUMAs (https://www2.census.gov/programs-surveys/acs/data/pums/2019/1-Year/csv_put.zip). The values of time are segmented by occupancy and purpose (work vs. non-work). A logical extension would be to expand the person data up to trips by calculating average person trip rates by income bin from the household travel survey. The trip rates would be segmented by purpose (work vs. non-work) and mode (DA, S2, S3+, other). Then apply these to scale up the person trips to trips by purpose and mode. Apply the SOV VOT to both drive-alone and ‘other’ modes (walk, bike, transit).  Then you can create just one frequency distribution with all the data. The breakpoints are between 33rd and 66th percentiles. The 99th percentile can be used as a maximum VOT. There is some question about what VOTs to use in assignment since the trips are binned. I would typically use the max for each bin.

You can calculate the share of trips that should be in each VOT bin by income as well. These percentages can then be applied to the trip generation results to split the trips out by VOT bin prior to destination and mode choice.

Note that the in-vehicle time parameters and cost parameters are placeholders for now. We may be able to estimate new time and cost parameters in mode choice which would replace these.

 

