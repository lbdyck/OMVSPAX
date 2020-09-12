OMVSPAX is a package of three small ISPF dialogs written in REXX to
simplify the backup and restoration of a omvs directory.

The dialogs are:

    OMVSPAX   - ISPF Panel menu for the following:
    OMVSPAXB  - backup a omvs directory using pax to a z/OS dataset.
    OMVSPAXL  - list the contents of a backup pax z/OS dataset.
    OMVSPAXR  - restore a pax z/OS backup dataset to the original
                omvs directory or another directory providing it
                exists

To invoke the dialogs:

    1. Must be under ISPF
    2. From ISPF 6 enter %OMVSPAX?   Where ? is B/L/R
    3. From any ISPF command line enter:  TSO %OMVSPAX?
       or TSO %OMVSPAX (for the menu)

Dependencies:
  - This ISPF dialog utilizes the STEMVIEW utility which can be
    found on the CBTTape FILE 183.
