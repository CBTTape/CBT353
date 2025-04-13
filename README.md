# CBT353
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 353 IS FROM MORTON THIOKOL INC. OF CHICAGO, ILLINOIS AND  *   FILE 353
//*           CONTAINS THE FOLLOWING PROGRAMS TO RUN UNDER SPF.     *   FILE 353
//*           THIS FILE IS IN IEBUPDTE SYSIN FORMAT.  SEE THE       *   FILE 353
//*           MEMBER CALLED $$INDEX FOR ADDITIONAL INFORMATION:     *   FILE 353
//*                                                                 *   FILE 353
//*           KWS SPF SPY DIDOCS QUE QUEUE MCS Q                    *   FILE 353
//*                                                                 *   FILE 353
//*              APPLMON$ - INSTALL DOC FOR APPLMON                 *   FILE 353
//*                                                                 *   FILE 353
//*                         APPLMON IS A VTAM APPLICATION           *   FILE 353
//*                         MONITOR.  IT PROVIDES A MULTI-USER      *   FILE 353
//*                         INTERFACE TO NATIVE VTAM                *   FILE 353
//*                         APPLICATIONS.  IT PROVIDES A            *   FILE 353
//*                         FULL-SCREEN LOGON PANEL, A PRIMARY      *   FILE 353
//*                         OPTION PANEL, AND 4 SAMPLE              *   FILE 353
//*                         APPLICATIONS.  EACH USER THAT LOGS      *   FILE 353
//*                         ON RUNS UNDER A SEPARATE TCB; THE       *   FILE 353
//*                         NUMBER OF USERS THAT COULD BE           *   FILE 353
//*                         SUPPORTED IN ONE ADDRESS SPACE IS       *   FILE 353
//*                         DEPENDENT ON REGION SIZE.               *   FILE 353
//*                                                                 *   FILE 353
//*              CDF$     - INSTALL DOC FOR MVS SP 1.3 CONSOLE      *   FILE 353
//*                         DISPLAY FACILITY (CDF)                  *   FILE 353
//*                                                                 *   FILE 353
//*                         THIS PROGRAM PROVIDES THE ISPF/PDF      *   FILE 353
//*                         USER WITH A DISPLAY OF THE MASTER       *   FILE 353
//*                         CONSOLE.  OPERATOR COMMANDS ARE         *   FILE 353
//*                         ENTERED ON THE STANDARD "COMMAND        *   FILE 353
//*                         INPUT" LINE; PF3 GETS YOU OUT.          *   FILE 353
//*                         SECURITY IS BASED ON THE TSO USERID,    *   FILE 353
//*                         SEE THE CODE FOR CUSTOMIZATION INFO.    *   FILE 353
//*                         YOU HAVE TO HIT "ENTER" TO REFRESH      *   FILE 353
//*                         THE DISPLAY.  YOU MUST ADJUST THE       *   FILE 353
//*                         LINE COUNT BASED ON THE MASTER          *   FILE 353
//*                         CONSOLE'S TERMINAL TYPE.                *   FILE 353
//*                                                                 *   FILE 353
//*              DIF      - ISPF/PDF DISPLAY INITIATORS FACILITY    *   FILE 353
//*                         (DIF)--PART OF JDF.                     *   FILE 353
//*                                                                 *   FILE 353
//*              ETPS$    - INSTALL DOC FOR EMERGENCY               *   FILE 353
//*                         TELE-PROCESSING SERVICES (ETPS).        *   FILE 353
//*                                                                 *   FILE 353
//*                         THIS PROGRAM PROVIDES SOME BASIC        *   FILE 353
//*                         TIME-SHARING SERVICES WHEN TSO OR SPF   *   FILE 353
//*                         IS UNAVAILABLE.  IF YOU DEFINE IT AS    *   FILE 353
//*                         A SUB-SYSTEM, IT CAN BE (AND HAS        *   FILE 353
//*                         BEEN, TO MY GREAT RELIEF) BROUGHT UP    *   FILE 353
//*                         EVEN WHEN JES2 ABENDS, OR WILL NOT      *   FILE 353
//*                         INITIALIZE.                             *   FILE 353
//*                                                                 *   FILE 353
//*                         THE BASIC PROCESSING APPEARS MUCH       *   FILE 353
//*                         LIKE SPF, AS FAR AS THE PRIMARY         *   FILE 353
//*                         OPTION MENU AND SO FORTH ARE            *   FILE 353
//*                         CONCERNED.  THE FULL-SCREEN EDITOR IS   *   FILE 353
//*                         QUITE PRIMITIVE, BUT SHOULD SUFFICE     *   FILE 353
//*                         FOR EMERGENCY USE.  TUBE I/O IS EXCP,   *   FILE 353
//*                         SO YOU DON'T NEED BTAM, TCAM, OR        *   FILE 353
//*                         VTAM/TCAS.                              *   FILE 353
//*                                                                 *   FILE 353
//*                         THE PRIMARY OPTION MENU HAS 4 OPTIONS:  *   FILE 353
//*                                     1. PDS BROWSE               *   FILE 353
//*                                     2. PDS EDIT                 *   FILE 353
//*                                     3. PDS UTILITY              *   FILE 353
//*                                     4. IDCAMS INTERFACE         *   FILE 353
//*                                                                 *   FILE 353
//*                         TERMINALS SUPPORTED ARE 3278-2,         *   FILE 353
//*                         3278-4, 3279-3B. INSTALL AND USER       *   FILE 353
//*                         DOC ARE IN COMMENTS IN THE CODE, AS     *   FILE 353
//*                         WELL AS IN MEMBER "ETPS$" IN THIS       *   FILE 353
//*                         DATASET.                                *   FILE 353
//*                                                                 *   FILE 353
//*                         A NUMBER OF ENHANCEMENTS AND FIXES      *   FILE 353
//*                         ARE INCLUDED IN THIS VERSION, WHICH     *   FILE 353
//*                         IS INDICATED AS 2.4 ON THE PRIMARY      *   FILE 353
//*                         OPTION MENU.  TO INSTALL UNDER XA,      *   FILE 353
//*                         JUST RE-ASSEMBLE USING THE XA MACLIB    *   FILE 353
//*                         AND AMODGEN.  NO SOURCE CHANGES ARE     *   FILE 353
//*                         REQUIRED.                               *   FILE 353
//*                                                                 *   FILE 353
//*              JDF$     - INSTALL DOC FOR ISPF/PDF JES2           *   FILE 353
//*                         DISPLAY FACILITY (JDF)                  *   FILE 353
//*                                                                 *   FILE 353
//*                         THIS PROGRAM PROVIDES THE ISPF/PDF      *   FILE 353
//*                         USER WITH A DISPLAY OF THE JES2         *   FILE 353
//*                         SPOOL, SIMILAR TO THE FAMOUS "QUEUE"    *   FILE 353
//*                         COMMAND.                                *   FILE 353
//*                                                                 *   FILE 353
//*                         REQUIRES MY MODIFIED UAL JES2           *   FILE 353
//*                         INTERFACE SVC AND JES2 HJE2330.         *   FILE 353
//*                                                                 *   FILE 353
//*              JDFMACS  - A SET OF MACROS THAT GENERATE JDF       *   FILE 353
//*                         DSECTS.                                 *   FILE 353
//*                                                                 *   FILE 353
//*              PLF$     - INSTALL DOC FOR ISPF/PDF PAN LIBRARY    *   FILE 353
//*                         FACILITY (PLF)                          *   FILE 353
//*                                                                 *   FILE 353
//*                         THIS PROGRAM PROVIDES THE ISPF/PDF      *   FILE 353
//*                         USER WITH A DISPLAY OF A PAN            *   FILE 353
//*                         LIBRARY, WITH THE ABILITY TO BROWSE     *   FILE 353
//*                         AND EDIT FROM A MEMBER LIST.  THIS IS   *   FILE 353
//*                         BASED IN PART ON THE "PANVIEW"          *   FILE 353
//*                         PROGRAM ON THE SHARE SPLA TAPE (I       *   FILE 353
//*                         THINK).  IT'S NOT NEARLY AS GOOD AS     *   FILE 353
//*                         THE PAN/SPF PRODUCT, OR SO I'M TOLD,    *   FILE 353
//*                         BUT THIS IS A LOT CHEAPER.              *   FILE 353
//*                                                                 *   FILE 353
//*              SMBROWSE - SPF MEMORY BROWSE PROGRAM, INVOKED      *   FILE 353
//*                         WITH A PARAMETER LIST POINTING TO       *   FILE 353
//*                         AN AREA OF MEMORY.  PROVIDES A          *   FILE 353
//*                         LOW-OVERHEAD BROWSE THAT CAN BE         *   FILE 353
//*                         INVOKED FROM ISPF APPLICATIONS.         *   FILE 353
//*                         USED IN JDF.                            *   FILE 353
//*                                                                 *   FILE 353
//*              SPFMACS  - A SET OF MACROS TO INVOKE ISPF          *   FILE 353
//*                         SERVICES.                               *   FILE 353
//*                                                                 *   FILE 353
//*              TCBUVTAM - A MACRO THAT GENERATES A DSECT USED     *   FILE 353
//*                         BY ETPS.  THIS IS FOR A FUTURE          *   FILE 353
//*                         ENHANCEMENT.                            *   FILE 353
//*                                                                 *   FILE 353
//*              VDF$     - INSTALL DOC FOR ISPF/PDF VTOC           *   FILE 353
//*                         DISPLAY FACILITY (VDF).                 *   FILE 353
//*                                                                 *   FILE 353
//*                         THIS PROGRAM PROVIDES THE ISPF/PDF      *   FILE 353
//*                         USER WITH A DISPLAY OF ALL OR           *   FILE 353
//*                         SELECTED ONLINE DASD VOLUMES.  THE      *   FILE 353
//*                         DISPLAY USES THE LSPACE SVC, SO IT      *   FILE 353
//*                         DOESN'T HAVE A LOT OF INFORMATION ON    *   FILE 353
//*                         EACH PACK.                              *   FILE 353
//*                                                                 *   FILE 353
//*                         BECAUSE OF THE SIMPLICITY OF THE        *   FILE 353
//*                         PROGRAM, THIS MAY BE A GOOD PROGRAM     *   FILE 353
//*                         TO SWIPE CODE FROM, IF YOU ARE          *   FILE 353
//*                         WRITING YOUR FIRST ISPF APPLICATION.    *   FILE 353
//*                                                                 *   FILE 353
//*              XDF$     - INSTALL DOC FOR ISPF/PDF EXECUTION      *   FILE 353
//*                         DISPLAY FACILITY (XDF)                  *   FILE 353
//*                                                                 *   FILE 353
//*                         THIS PROGRAM PROVIDES THE ISPF/PDF      *   FILE 353
//*                         USER WITH A DISPLAY OF ACTIVE JOBS      *   FILE 353
//*                         AND STARTED TASKS, BASED ON "CHIMP",    *   FILE 353
//*                         UPDATED FOR SP 2.1.3.                   *   FILE 353
//*                                                                 *   FILE 353
```
