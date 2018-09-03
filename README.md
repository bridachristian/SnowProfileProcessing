SnowProfileProcessing
================

R package for the postprocessing of snow pit measurement.

Description
-----------

Snowpit, done following mod.3-4, AINEVA (Cagnati, A., 2003), contain data of layers characteristic (grain type, size, ...) and physical parameter (liquid water content,density, ...).

These data are organized into 2 files, the first contatins the stratigraphy for each snowpit done during the season (possible more than one winter season), the second contain the data of density measured (horizontal sampling) for each layer for each snowpit. There are some cases that the density are not measured, for examples for thin layers the sampler is too large. With the following functions we merge the stratigraphy file with the density file, reconstruct missing density with a method based on grain type and layer hardness (Valt M. & Cagnati A., 2005) and aggregate each profile to extract information about snow height, mean snow density and snow water equivalent.

How to start
------------

Clone the package from <https://github.com/bridachristian/SnowProfileProcessing>

and install using:

``` r
library(devtools)
install_github("bridachristian/SnowProfileProcessing")
library(SnowProfileProcessing)
```

[Package documentation: Vignette](https://github.com/bridachristian/SnowProfileProcessing/blob/master/Vignette/SnowProfileProcessing_vignette.Rmd)
--------------------------------------------------------------------------------------------------------------------------------------------------

References
----------

-   Cagnati, A., 2003. *Sistemi di Misura e metodi di osservazio-ne nivometeorologici*, AINEVA, 14 Trento, p. 186
-   Valt M & Cagnati A., 2005 *Stima della Densità della neve conoscendo la forma dei grani e la durezza*, Neve e Valanghe, 55, p. 40-45

Contacts:
---------

-   Christian Brida: <Christian.Brida@eurac.edu> Insitute for Alpine Environment, Eurac Research
-   Giacomo Bertoldi: <giacomo.bertoldi@eurac.edu> Insitute for Alpine Environment, Eurac Research
