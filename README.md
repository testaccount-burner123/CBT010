# CBT010
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 010 is from Greg Price, and contains source code and      *   FILE 010
//*           a load library for his system monitor called IMON     *   FILE 010
//*           or IM.                                                *   FILE 010
//*                                                                 *   FILE 010
//*       IMON used to be a "pay product", but since Greg           *   FILE 010
//*       has no more paying customers, he has released the         *   FILE 010
//*       source code for use by anyone, but only under the         *   FILE 010
//*       conditions specified in the $$NOTICE meember of           *   FILE 010
//*       this pds.                                                 *   FILE 010
//*                                                                 *   FILE 010
//*       This program is an extremely important multi-purpose      *   FILE 010
//*       tool to have in your arsenal.  Every systems              *   FILE 010
//*       programmer should learn how to use its many parts.        *   FILE 010
//*       Previously, this marvelous program wasn't available       *   FILE 010
//*       to the public.  Now, the author has graciously given      *   FILE 010
//*       everyone access to it.                                    *   FILE 010
//*                                                                 *   FILE 010
//*       email:  greg.price@optusnet.com.au                        *   FILE 010
//*                                                                 *   FILE 010
//*       Load modules are included in XMIT format as member        *   FILE 010
//*       LOADLIB.                                                  *   FILE 010
//*                                                                 *   FILE 010
//*       JCL members are included in XMIT format as member         *   FILE 010
//*       IMONCNTL.                                                 *   FILE 010
//*                                                                 *   FILE 010
//*   Sample IMON main menu (condensed to fit in this space)        *   FILE 010
//*                                                                 *   FILE 010
//*      INTERACTIVE MONITORING PROGRAM FOR OS/390 AND z/OS         *   FILE 010
//*   ? - INVOKE THE I-MON TUTORIAL   (PF1/13)                      *   FILE 010
//*   $ - DISK SPACE DISPLAY                     I-MON              *   FILE 010
//*   @ - UNIX USER DATA BASE DISPLAY           PRIMARY             *   FILE 010
//*   A - ADDRESS SPACE MONITOR       (PF6/18)  OPTIONS             *   FILE 010
//*   B - DISPLAY BLDL AND CSVQUERY RESULTS                         *   FILE 010
//*   C - CHANNEL PATH MONITOR                                      *   FILE 010
//*   D - INPUT/OUTPUT DEVICE MONITOR (PF9/21)  USERID-----: CBT0   *   FILE 010
//*   E - RESERVE AND ENQUEUE MONITOR           TERMINAL---: TCP0   *   FILE 010
//*   G - GRAPHIC ACTIVITY MONITOR              NETWORK----: VTAM   *   FILE 010
//*   J - JOB STATUS MONITOR                    DATE-(NOW)-: 2020   *   FILE 010
//*   K - HISTORICAL KNOWLEDGE DISPLAY          DATE-(IPL)-: 2020   *   FILE 010
//*   L - SYSTEM LIBRARY DISPLAY                SYSTEM-ID--: CBT    *   FILE 010
//*   M - SYSTEM/SYSPLEX MANAGEMENT MONITOR     SYSTEM-NAME: CBT    *   FILE 010
//*   N - NUCLEUS MAP DISPLAY AND LOOKUP        SYSPLEX----: LOCA   *   FILE 010
//*   O - OS CONSOLE AND MTT MONITOR            LPAR-NAME--: TRNG   *   FILE 010
//*   P - PAGE DATA SET MONITOR                 CLONE-NAME-: BT     *   FILE 010
//*   R - RATE CPU INSTRUCTION SPEED            VM-GUEST-ID:        *   FILE 010
//*   S - SWAP DOMAIN OR SERVICE CLASS MONITOR  CONFIG-NAME: VI39   *   FILE 010
//*   T - SVC TABLE DISPLAY                     CPU-SERIAL-: 02AB   *   FILE 010
//*   U - PERFORM UNIT I/O SAMPLING             CPU-MODEL--: 3907   *   FILE 010
//*   V - VIRTUAL STORAGE MONITOR                                   *   FILE 010
//*   X - EXIT I-MON                  (PF3/15)                      *   FILE 010
//*   (C) COPYRIGHT PRYCROFT SIX PTY. LTD. 1986-2020                *   FILE 010
//*                                                                 *   FILE 010
//*   IMON originated from the old CHIMP monitor that used to be    *   FILE 010
//*   on the CBT Tape.  But:                                        *   FILE 010
//*                                                                 *   FILE 010
//*   1.  IMON works on current z/OS systems (2.4 at present)       *   FILE 010
//*   2.  IMON was originally modified to work on Fujitsu FACOM     *   FILE 010
//*        systems as well as MVS.                                  *   FILE 010
//*   3.  IMON was a vendor product, sold for pay, for a long time, *   FILE 010
//*        until now.                                               *   FILE 010
//*                                                                 *   FILE 010
//*   Don't pass up an opportunity to install this product,         *   FILE 010
//*    and use its many featues.  This product is very precious.    *   FILE 010
//*                                                                 *   FILE 010
//*   Thanks, Greg....!!!!                                          *   FILE 010
//*                                                                 *   FILE 010
```
