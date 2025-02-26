![Status](https://github.com/NOAA-EMC/NCEPLIBS-nemsiogfs/workflows/Build%20and%20Test/badge.svg)

# NEMSIOGFS

Performs I/O for the NEMS-GFS model. This is part of the
[NCEPLIBS](https://github.com/NOAA-EMC/NCEPLIBS) project.

To submit bug reports, feature requests, or other code-related issues including installation and usage questions, please create a [GitHub issue](https://github.com/NOAA-EMC/NCEPLIBS-nemsiogfs/issues). For general NCEPLIBS inquiries, contact [Edward Hartnett](mailto:edward.hartnett@noaa.gov) (secondary point of contact [Alex Richert](mailto:alexander.richert@noaa.gov)).

## Authors

NCEP/EMC Developers

Code manager: [Hang Lei](mailto:hang.lei@noaa.gov)

## Prerequisites

The following libraries are required:
- [NCEPLIBS-sp] (https://github.com/NOAA-EMC/NCEPLIBS-sp)
- [NCEPLIBS-bacio] (https://github.com/NOAA-EMC/NCEPLIBS-bacio)
- [NCEPLIBS-w3nco] (https://github.com/NOAA-EMC/NCEPLIBS-w3nco)
- [NCEPLIBS-sigio] (https://github.com/NOAA-EMC/NCEPLIBS-sigio)
- [NCEPLIBS-nemsio] (https://github.com/NOAA-EMC/NCEPLIBS-nemsio)
- [NCEPLIBS-ip] (https://github.com/NOAA-EMC/NCEPLIBS-ip)

## Installing

```
mkdir build
cd build
cmake -DCMAKE_INSTALL_PREFIX=/path/to/install /path/to/NCEPLIBS-nemsiogfs
make -j2
make install
```

## Disclaimer

The United States Department of Commerce (DOC) GitHub project code is
provided on an "as is" basis and the user assumes responsibility for
its use. DOC has relinquished control of the information and no longer
has responsibility to protect the integrity, confidentiality, or
availability of the information. Any claims against the Department of
Commerce stemming from the use of its GitHub project will be governed
by all applicable Federal law. Any reference to specific commercial
products, processes, or services by service mark, trademark,
manufacturer, or otherwise, does not constitute or imply their
endorsement, recommendation or favoring by the Department of
Commerce. The Department of Commerce seal and logo, or the seal and
logo of a DOC bureau, shall not be used in any manner to imply
endorsement of any commercial product or activity by DOC or the United
States Government.



