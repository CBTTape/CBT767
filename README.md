# CBT767
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 767 is from Daniel Gaeta and contains frontend REXX       *   FILE 767
//*           execs to invoke TRSMAIN both in terse and unterse     *   FILE 767
//*           mode.  Please see the explanation below.              *   FILE 767
//*                                                                 *   FILE 767
//*     Daniel Gaeta                                                *   FILE 767
//*     email:  dfgaeta@br.ibm.com                                  *   FILE 767
//*                                                                 *   FILE 767
//*     -------------------------------------------------------     *   FILE 767
//*                                                                 *   FILE 767
//*     TPACK and TUNPACK                                           *   FILE 767
//*                                                                 *   FILE 767
//*     Recently I needed to save space in my MVS dasds and I       *   FILE 767
//*     was using TRSMAIN utility. In most of cases I submitted     *   FILE 767
//*     some JCLs.  After a lot of submission I used my know-how    *   FILE 767
//*     in REXX language and developed two small tools.             *   FILE 767
//*     Basically TPACK and TUNPACK, just a front-end for this      *   FILE 767
//*     utility.                                                    *   FILE 767
//*                                                                 *   FILE 767
//*     This utility uses some information included in TERSE        *   FILE 767
//*     dataset header.  Checking header data I can define what     *   FILE 767
//*     will be the DSORG and RECFM for output untersed file.       *   FILE 767
//*                                                                 *   FILE 767
//*     Both tools can be used informing just one parameter and     *   FILE 767
//*     they invoke TRSMAIN utility.  (Please, change the           *   FILE 767
//*     current library if different!)  For TPACK, you can use      *   FILE 767
//*     TPACK 'indataset' 'outdataset' For TUNPACK, you can use     *   FILE 767
//*     TUNPACK 'indataset' 'outdataset'                            *   FILE 767
//*                                                                 *   FILE 767
//*     This tool can be interesting when you use with ISPF         *   FILE 767
//*     option 3.4, in order to don't forget to concat in           *   FILE 767
//*     SYSPROC.                                                    *   FILE 767
//*                                                                 *   FILE 767
//*     Sample :                                                    *   FILE 767
//*                                                                 *   FILE 767
//*        Menu  Options  View  Utilities  Compilers  Help          *   FILE 767
//*      ssssssssssssssssssssssssssssssssssssssssssssssssssss       *   FILE 767
//*      DSLIST - Data Sets Matching SYS1                           *   FILE 767
//*      Command ===>                                               *   FILE 767
//*                                                                 *   FILE 767
//*      Command - Enter "/" to select action                       *   FILE 767
//*      ---------------------------------------------------------------FILE 767
//*      tpack    SYS1.CIDTABL                                      *   FILE 767
//*        or     SYS1.CLIST                                        *   FILE 767
//*      tunpack  SYS1.CMDLIB                                       *   FILE 767
//*               SYS1.COB2LIB                                      *   FILE 767
//*               SYS1.COMMDS                                       *   FILE 767
//*                                                                 *   FILE 767
```
