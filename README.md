# Detectability limits of scaling laws

Data and a worked example for

> A. Kirkley, *Detectability limits of scaling laws* (2026).

`example.ipynb` runs the subgroup analysis of the paper on the mammalian metabolic data (Fig. 2(b), SM Sec. C.2): common exponent, per-order exponents and prefactors with their errors, and the excess-scatter test against the resolution limits. It needs only numpy, pandas and scipy.

## Data

- `data/urban/CAINC1__ALL_AREAS_1969_2019.csv`, `CAGDP1__ALL_AREAS_2001_2019.csv`, `CAEMP25S__ALL_AREAS_1969_2000.csv`, `CAEMP25N__ALL_AREAS_2001_2019.csv`: BEA regional accounts, county tables (personal income and population; GDP; employment by industry, SIC and NAICS).
- `data/urban/us_counties_crosswalk_2019.csv`: county to CBSA crosswalk, March 2020 OMB delineations.
- `data/allometry/PanTHERIA_1-0_WR05_Aug2008.txt`: PanTHERIA (Jones et al., *Ecology* 90, 2648, 2009).
- `data/roads/19584088.zip`: CBSA road-network statistics by decade, 1900-2015, Burghardt, Uhl, Lerman and Leyk (Figshare 19584088; *Comput. Environ. Urban Syst.* 95, 101803, 2022).
