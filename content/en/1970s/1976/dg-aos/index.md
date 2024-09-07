---
title: "! Data General AOS"
description: "! Data General AOS was an operating systems for the Data General Nova computer. We can run it using the WildHare Nova emulator."
date: 2024-07-09T09:08:56+05:30
draft: false
images: [aos.webp]
type: docs
weight: 620000
---

{{< load-photoswipe >}}

! Data General AOS was an operating systems for the Data General Nova computer. We can run it using the WildHare Nova emulator.

{{< gallery >}}
  {{< figure src="/1970s/1976/dg-aos/aos.webp" alt="! Data General AOS" caption="! Data General AOS" >}}
{{< /gallery >}}

Session Log:

```console
Wild Hare Nova/Eclipse Emulator [beta 00.00.07] simulator V4.0-0 Current        git commit id: a06fa926
G:/VMs/Others/1970s/1976/Data General AOS/nova.ini-24> attach  TTI1    40000
Listening on port 40000
G:/VMs/Others/1970s/1976/Data General AOS/nova.ini-25> attach  ALM     40001
Listening on port 40001


SPECIFY EACH DISK IN THE LDU
DISK UNIT NAME? DPF0
DEVICE CODE?
SYSTEM PATHNAME?


AOS REV   7.00

DATE (MM/DD/YY) ? 06/19/84

TIME (HH:MM:SS) ? 04:16:32

OVERRIDE DEFAULT SPECS [N] ?

MASTER LDU: DPF0

AOS CLI   REV 07.00     19-JUN-84        4:16:32
) CHAR/NAS/CPL=166
) SEARCH :util : :MACROS :PER
) SUPERUSER ON
*) UP
PID: 3

FROM PID   3 : (EXEC)  REV 07.00 READY

FROM PID   3 : (EXEC)   4:17:00

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON1

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON2

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON3

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON4

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON5

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON6

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON7

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON8

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON9

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON10

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON11

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON12

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON13

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON14

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON15

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON16

FROM PID   3 : (EXEC)   4:17:02

FROM PID   3 : (EXEC)  ENABLED CONSOLE, @CON17

FROM PID   3 : (EXEC)  STREAM_1 CONTINUING

FROM PID   3 : (EXEC)   4:17:12

FROM PID   3 : (EXEC)  STREAM_1 [IDLE]

FROM PID   3 : (EXEC)   4:17:12

FROM PID   3 : (EXEC)   4:17:12

FROM PID   3 : (EXEC)  @LPA CO-OPERATIVE INITIATED

FROM PID   3 : (EXEC)   4:17:12

FROM PID   3 : (EXEC)  @LPA PAUSED

FROM PID   3 : (EXEC)   4:17:12

FROM PID   3 : (EXEC)  @LPA CONTINUING

FROM PID   3 : (EXEC)   4:17:12

FROM PID   3 : (EXEC)  @LPA [IDLE]

AOS CLI   REV 07.00     19-JUN-84        4:17:12

) SUPERUSER ON
*) FILESTATUS

DIRECTORY :

  PER               PROC              NET               PMGR.PR
  TBOOT             GHOST.ST          FIXUP.ST          ALDCU.ST
  SLISC.ST          PATCH_FILES       GHOST.PR          GHOST.OL
  ERMES             SLISC.PR          INSTL             IACRS.ST
  CLI.ST            ALDCU.PR          UPD               UTILS_AOS
  PCOPY             SYSBOOT           HELP              UTIL
  TBOOT.ST          IOPMGR.ST         DFMTR             SWAP.SWAP
  CLI.PR            CLI.OL            IACRS.PR          SYSGEN
  FIXUP             SLDCU.ST          PATCH             UDD
  QUEUE             INFOS_II.ST       UP                IOPMGR.PR
  INSTL.ST          PMGR.ST           DEBUG.ST          LICENSE.TX
  GAMES_1           MACROS            TEST              SLDCU.PR
  PCOPY.ST          SYSBOOT.ST        DFMTR.ST          DEMO
  GAMES_2           INFOS_II.PR       INFOS_II.OL
*) BYE
AOS CLI   TERMINATING   19-JUN-84        4:17:40

 4:17:40
*) BYE
YOU HAVE SONS. DO YOU WANT TO TERMINATE? YES
DO YOU REALLY WANT TO SHUT THE SYSTEM DOWN? YES
STARTING SYSTEM SHUTDOWN        19-JUN-84        4:17:47


SYSTEM SHUTDOWN
```
