# simulate_pv_time_series
A file with a couple of functions for simulating time series of daily normalized energy yields

Contains:

    simulate_PV_time_series(): Model for generating PV soiling time series described in Deceglie et. al. 
        "Numerical Validation of an Algorithm for Combined Soiling and Degradation Analysis of Photovoltaic
        Systems", Proceedings of the 2019 IEEE PVSC. 

    simulate_PV_time_series_gaussian_soiling(): Model for generating PV soiling time series with soiling 
        rates that vary from day to day according to a Gaussian distribution (Åsmund)

    generate_my_soiling_signals(): A function that generates 6 different time series based on the previous 
        two functions. This was used to generate the datasets used in 
        A. Skomedal, M. G. Deceglie, 2020, "Combined Estimation of Degradation and Soiling Losses in PV 
        Systems" 