********************
Meanings of Switches
********************

These are the meanings of the switches in the ```switch`` file,
as given in the `ww3-v5.16 manual`_

.. _ww3-v5.16 manual: http://polar.ncep.noaa.gov/waves/wavewatch/manual.v5.16.pdf


F90     FORTRAN-90 style date and time capturing and program abort.

DIST    Distributed memory model.

MPI     Message Passing Interface (MPI).

LRB4    Use 4 byte words for record length in direct access files.

NOPA    Compilation as a stand-alone program

PR3     Higher-order propagation schemes with Tolman (2002a) averaging technique.

UQ      Third-order (UQ) propagation scheme.

FLX0    Flux computation included in source terms

LN1     Linear input: Cavaleri and Malanotte-Rizzoli with filter.

ST4     Input and dissipation: Ardhuin et al. (2010) source term package

STAB0

NL1     Nonlinear interactions: Discrete interaction approximation (DIA).

BT0     No bottom friction used.

IC0     No damping by sea ice.

IS0     No scattering by sea ice.

REF1    Enables reflection of(sic?) shorelines and icebergs

DB1     Depth-induced breaking: Battjes-Janssen.

TR0     No triad interactions used.

BS0     No bottom scattering used.

XX0     No supplemental source term used.

WNT1    Linear wind interpolation in time

WNX1    Approximately linear wind speed interpolation in space

CRT1    Linear current interpolation in time

CRX1    Approximately linear current speed interpolation in space

NOGRB   No package included.

O0      Output of namelists in grid preprocessor.

O1      Output of boundary points in grid preprocessor.

O2      Output of the grid point status map in grid preprocessor.

NC4     Activates the NetCDF-4 API in the NetCDF pre- and post-processing programs.

RWND    Correct wind speed for current velocity.

