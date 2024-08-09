---
title: "! RT-11 v2"
description: "! RT-11 v2 was an operating system for the DEC PDP-11 computer. We can run it using the SIMH emulator."
date: 2024-08-09T09:08:56+05:30
draft: false
images: [rt-11-v2B.webp]
type: docs
weight: 540000
---

{{< load-photoswipe >}}

! RT-11 v2 was an operating system for the DEC PDP-11 computer. We can run using the SIMH emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1975/rt-11-v2/simh/" role="button">! RT-11 v2 on SIMH</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1975/rt-11-v2/rt-11-v2B.webp" alt="! RT-11 v2B" caption="! RT-11 v2B" >}}
  {{< figure src="/1970s/1975/rt-11-v2/rt-11-v2C.webp" alt="! RT-11 v2C" caption="! RT-11 v2C" >}}  
{{< /gallery >}}

Session log for RT-11 v2B:

```console
PDP-11 simulator V4.0-0 Current        git commit id: 670a3728
./pdp11.ini-1> att rk0 RTV2RK.B
%SIM-INFO: RK0: Amount of data in use in disk container 'RTV2RK.B' cannot be determined, skipping autosizing

RT-11SJ    V02B-05

.R PIP
*/L

DXMNSJ.SYS   45  1-MAY-75
DXMNFB.SYS   58  1-MAY-75
DP    .SYS    2  1-MAY-75
RK    .SYS    2  1-MAY-75
RF    .SYS    2  1-MAY-75
TT    .SYS    2  1-MAY-75
LP    .SYS    2  1-MAY-75
BA    .SYS    6  1-MAY-75
MONITR.SYS   45  1-MAY-75
RKMNFB.SYS   58  1-MAY-75
RFMNSJ.SYS   45  1-MAY-75
RFMNFB.SYS   58  1-MAY-75
DPMNSJ.SYS   45  1-MAY-75
DPMNFB.SYS   58  1-MAY-75
DT    .SYS    2  1-MAY-75
DX    .SYS    2  1-MAY-75
CR    .SYS    3  1-MAY-75
MT    .SYS    6  1-MAY-75
MM    .SYS    6  1-MAY-75
PR    .SYS    2  1-MAY-75
PP    .SYS    2  1-MAY-75
CT    .SYS    5  1-MAY-75
DS    .SYS    2  1-MAY-75
SYSMAC.SML   18  1-MAY-75
SYSMAC.8K    24  1-MAY-75
BATCH .SAV   25  1-MAY-75
EDIT  .SAV   18  1-MAY-75
MACRO .SAV   31  1-MAY-75
ASEMBL.SAV   21  1-MAY-75
EXPAND.SAV   12  1-MAY-75
CREF  .SAV    5  1-MAY-75
LINK  .SAV   25  1-MAY-75
LIBR  .SAV   15  1-MAY-75
PIP   .SAV   13  1-MAY-75
PATCH .SAV    5  1-MAY-75
ODT   .OBJ    9  1-MAY-75
VTHDLR.OBJ    8  1-MAY-75
DEMOFG.MAC    5  1-MAY-75
DEMOBG.MAC    4  1-MAY-75
FILEX .SAV   11  1-MAY-75
SRCCOM.SAV   11  1-MAY-75
DUMP  .SAV    5  1-MAY-75
PATCHO.SAV   33  1-MAY-75
VTMAC .MAC    7  1-MAY-75
SYSF4 .OBJ   33  1-MAY-75
KB    .MAC   33  1-MAY-75
46 FILES, 829 BLOCKS
3957 FREE BLOCKS
*^C

.
```

Session log for RT-11 v2C:

```console
PDP-11 simulator V4.0-0 Current        git commit id: 670a3728
./pdp11.ini-1> att rk0 RTV2RK.C
%SIM-INFO: RK0: Amount of data in use in disk container 'RTV2RK.C' cannot be determined, skipping autosizing

RT-11SJ    V02C-02

.R PIP
*/L

MONITR.SYS   46 20-NOV-75
RKMNFB.SYS   58 20-NOV-75
RFMNSJ.SYS   46 20-NOV-75
RFMNFB.SYS   58 20-NOV-75
DTMNSJ.SYS   46 20-NOV-75
DTMNFB.SYS   58 20-NOV-75
DPMNSJ.SYS   46 20-NOV-75
DPMNFB.SYS   58 20-NOV-75
DXMNSJ.SYS   46 20-NOV-75
DXMNFB.SYS   58 20-NOV-75
DSMNSJ.SYS   46 20-NOV-75
DSMNFB.SYS   58 20-NOV-75
DX    .SYS    2 20-NOV-75
DP    .SYS    2 20-NOV-75
DT    .SYS    2 20-NOV-75
RK    .SYS    2 20-NOV-75
RF    .SYS    2 20-NOV-75
TT    .SYS    2 20-NOV-75
LP    .SYS    2 20-NOV-75
CR    .SYS    3 20-NOV-75
MT    .SYS    6 20-NOV-75
MM    .SYS    6 20-NOV-75
PR    .SYS    2 20-NOV-75
PP    .SYS    2 20-NOV-75
CT    .SYS    5 20-NOV-75
DS    .SYS    2 20-NOV-75
BA    .SYS    7 20-NOV-75
CBUILD.SYS   32 20-NOV-75
SYSMAC.SML   18 20-NOV-75
SYSMAC.8K    25 20-NOV-75
BATCH .SAV   25 20-NOV-75
EDIT  .SAV   19 20-NOV-75
MACRO .SAV   31 20-NOV-75
ASEMBL.SAV   21 20-NOV-75
EXPAND.SAV   12 20-NOV-75
CREF  .SAV    5 20-NOV-75
LINK  .SAV   25 20-NOV-75
LIBR  .SAV   15  5-DEC-75
PIP   .SAV   14 20-NOV-75
FILEX .SAV   11 20-NOV-75
SRCCOM.SAV   11 20-NOV-75
DUMP  .SAV    5 20-NOV-75
PATCH .SAV    5 20-NOV-75
PATCHO.SAV   33 25-NOV-75
MTINIT.SAV    3 20-NOV-75
ODT   .OBJ    9 20-NOV-75
VTHDLR.OBJ    8 20-NOV-75
SYSF4 .OBJ   33 20-NOV-75
VTMAC .MAC    7 20-NOV-75
DEMOFG.MAC    5 20-NOV-75
DEMOBG.MAC    4 20-NOV-75
KB    .MAC   33 20-NOV-75
MBOOT .BOT    1 20-NOV-75
MSBOOT.BOT    3 20-NOV-75
MBUILD.MT1   32 20-NOV-75
MBUILD.MT2   32 20-NOV-75
MBUILD.MM1   32 20-NOV-75
MBUILD.MM2   32 20-NOV-75
58 FILES, 1212 BLOCKS
3574 FREE BLOCKS
*^C

.
```
