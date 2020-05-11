# electroniccoupling
Electronic coupling code from roughly 2012-2013
Implementation formerly ran with the 2013 version of GAMESS but these source files do not currently work with the 2020 release. Debugging has been rigorously attempted but the many issues have not been fixed to be able to offer a stable release.
Please contact me if you are interested in adapting this code to work in the latest releases.

Main modules added for electronic coupling are all in source file:  ecoupl.src

NOTE #1-- the remaining are *NOT* the current gamess release source files-- these were programmed into the version available late 2012 early 2013, and include the necessary modifications to save and pass the info for the electronic coupling from (1) the RHF/UHF routines, general input information, and localization routines into the ecoupling source code, ecoupl.src.
NOTE #2:  the complete input files are not published here due to distribution rights!

Unfortunately all these routines no longer work within the 2020 releases, and you are welcomed to look into reprogramming this into the modern Gamess release.
5 (or, optionally 6) 2013-GAMESS source files must be changed to incorporate the electronic coupling module: inputa, int1, local, mpcint and rhfuhf (Optionally, NBO if you have purchased rights to use this localization routine) Changes to subroutines in these source files are all noted with the comment flags LBERSTIS
