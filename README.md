# astrophysics
Calculate diameter and dynamical mass of cluster of galaxies

SQL is used to query the SDSS spectroscopic data archive. http://skyserver.sdss.org/dr16/en/tools/search/sql.aspx

We use the redshift determined by the SDSS itself for the galaxies in the field. The alternative is to download the spectrum of each
galaxy, use the spectral features to determine the redshift.

**Steps**: 1 Expansion Velocity 2. Mean Cluster Redshift 3. Velocity dispersion of galaxies 4. Angular separation between galaxies

**Library**: Astropy

**Outcome**: Diameter of the cluster is: 0.5722 Mpc and Dynamical Mass is 2.86e+14 s2 Mpc kg/m3 solar mass
