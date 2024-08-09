---
title: "! Nova RDOS"
description: "! Nova RDOS, as the name suggests, was an operating system for the Data General Nova computer."
date: 2024-08-06T09:08:56+05:30
draft: false
images: [nova-zrdos.webp]
type: docs
weight: 251000
---

{{< load-photoswipe >}}

! Nova RDOS, as the name suggests, was an operating system for the Data General Nova computer. We can run using the Wild Hare Nova emulator, or the SIMH emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1972/nova-rdos/wh/" role="button">! Nova RDOS on Wild Hare Nova emulator</a></p>
      </div>
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1972/nova-rdos/simh-nova/" role="button">! Nova RDOS on SIMH Nova Emulator</a></p>
      </div>
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1972/nova-rdos/simh-eclipse/" role="button">! Nova RDOS on SIMH Eclipse Emulator</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1972/nova-rdos/nova-urdos.webp" alt="! Nova URDOS on WH emulator" caption="! Nova URDOS on WH emulator" >}}
  {{< figure src="/1970s/1972/nova-rdos/nova-mrdos.webp" alt="! Nova MRDOS on WH emulator" caption="! Nova MRDOS on WH emulator" >}}
  {{< figure src="/1970s/1972/nova-rdos/nova-nrdos.webp" alt="! Nova NRDOS on WH emulator" caption="! Nova NRDOS on WH emulator" >}}
  {{< figure src="/1970s/1972/nova-rdos/nova-zrdos.webp" alt="! Nova ZRDOS on WH emulator" caption="! Nova ZRDOS on WH emulator" >}}
  {{< figure src="/1970s/1972/nova-rdos/nova-rdos-nova.webp" alt="! Nova RDOS on SIMH Nova emulator" caption="! Nova RDOS on SIMH Nova emulator" >}}
  {{< figure src="/1970s/1972/nova-rdos/nova-rdos-eclipse.webp" alt="! Nova RDOS on SIMH Eclipse emulator" caption="! Nova RDOS on SIMH Eclipse emulator" >}}
{{< /gallery >}}

Session Log for URDOS on WH emulator:

```console
Wild Hare Nova/Eclipse Emulator [beta 00.00.07] simulator V4.0-0 Current        git commit id: a06fa926

Filename? URDOS


NOVA RDOS Rev 7.60
Date (m/d/y) ? 08/06/1984
Time (h:m:s) ? 02:07:19

R
LIST
BASIC.DR            512  DY
LINKUTIL.BU          36
RCLI.SV           38400  SD
CREATEUTIL.MC       512  D
MRDOS.OL          30720  C
COMPUCALC.DR        512  DY
NRDOS.OL          30720  C
ZRDOS.OL          31232  C
URDOS.SV          62464  SD
CLI.OL            50176  C
CLI.CM             1877  D
BASIC.SV                  BASICE:ZBASIC.SV
BASICHELP.DR        512  DY
C.DR                512  DY
DEMO$FORT4.DR       512  DY
UTIL$BU.DR          512  DY
DEMO$FORT5.DR       512  DY
FORTRAN5N.DR        512  DY
CREATEUTIL.BU       500  D
ABOOT.SV           6144  SD
DEMO$BASIC.DR       512  DY
UP.MC               270  D
FORT.DR             512  DY
CLI.ER             3584  D
LD.MC                     MACROS:LD.MC
FCLI.S1            1024  D
BASIC.AF            682  D
MD.MC                     MACROS:MD.MC
MRDOS.SV          40448  SD
LL.MC                     MACROS:LL.MC
LM.MC                     MACROS:LM.MC
LN.MC                     MACROS:LN.MC
FORTRAN5E.DR        512  DY
COBOL.DR            512  DY
COM.CM                9
UTILFILES.          231  D
NRDOS.SV          40960  SD
BOOTSYS.SV        60416  SD
LS.MC                     MACROS:LS.MC
MACROS.DR           512  DY
ICOBOLN.DR          512  DY
ZRDOS.SV          40960  SD
DGL.DR              512  DY
LICENSE.TX         5227
LINKUTIL.MC         156  D
DEMO.DR             512  DY
CLI.SV            11264  SD
EBOOT.SV           7168  SD
BYE.MC               17
DEMO$ALGOL.DR       512  DY
URDOS.OL          30720  C
BASICE.DR           512  DY
BASIC.OL                  BASICE:ZBASIC.OL
FCOM.CM               9
ALGOL.DR            512  DY
DEMO$ASM.DR         512  DY
DEMO$DGL.DR         512  DY
BASICN.DR           512  DY
ICOBOLE.DR          512  DY
UTIL.DR             512  DY
LISP.DR             512  DY
FORTH.DR            512  DY
R
```

Session Log for MRDOS on WH emulator:

```console
Wild Hare Nova/Eclipse Emulator [beta 00.00.07] simulator V4.0-0 Current        git commit id: a06fa926
sim> set CPU NOVA_840
sim> boot DZP

Filename? MRDOS


Mapped NOVA RDOS Rev 7.60
Date (m/d/y) ? 08/06/1984
Time (h:m:s) ? 02:40:10

R
LIST
BASIC.DR            512  DY
LINKUTIL.BU          36
RCLI.SV           38400  SD
CREATEUTIL.MC       512  D
MRDOS.OL          30720  C
COMPUCALC.DR        512  DY
NRDOS.OL          30720  C
ZRDOS.OL          31232  C
URDOS.SV          62464  SD
CLI.OL            50176  C
CLI.CM             1877  D
BASIC.SV                  BASICE:ZBASIC.SV
BASICHELP.DR        512  DY
C.DR                512  DY
DEMO$FORT4.DR       512  DY
UTIL$BU.DR          512  DY
DEMO$FORT5.DR       512  DY
FORTRAN5N.DR        512  DY
CREATEUTIL.BU       500  D
ABOOT.SV           6144  SD
DEMO$BASIC.DR       512  DY
UP.MC               270  D
FORT.DR             512  DY
CLI.ER             3584  D
LD.MC                     MACROS:LD.MC
FCLI.S1            1024  D
BASIC.AF            682  D
MD.MC                     MACROS:MD.MC
MRDOS.SV          40448  SD
LL.MC                     MACROS:LL.MC
LM.MC                     MACROS:LM.MC
LN.MC                     MACROS:LN.MC
FORTRAN5E.DR        512  DY
COBOL.DR            512  DY
COM.CM                9
UTILFILES.          231  D
NRDOS.SV          40960  SD
BOOTSYS.SV        60416  SD
LS.MC                     MACROS:LS.MC
MACROS.DR           512  DY
ICOBOLN.DR          512  DY
ZRDOS.SV          40960  SD
DGL.DR              512  DY
LICENSE.TX         5227
LINKUTIL.MC         156  D
DEMO.DR             512  DY
CLI.SV            11264  SD
EBOOT.SV           7168  SD
BYE.MC               17
DEMO$ALGOL.DR       512  DY
URDOS.OL          30720  C
BASICE.DR           512  DY
BASIC.OL                  BASICE:ZBASIC.OL
FCOM.CM               9
ALGOL.DR            512  DY
DEMO$ASM.DR         512  DY
DEMO$DGL.DR         512  DY
BASICN.DR           512  DY
ICOBOLE.DR          512  DY
UTIL.DR             512  DY
LISP.DR             512  DY
FORTH.DR            512  DY
R
```

Session Log for NRDOS on WH emulator:

```console
Wild Hare Nova/Eclipse Emulator [beta 00.00.07] simulator V4.0-0 Current        git commit id: a06fa926
sim> set CPU NOVA_4/X
sim> boot DZP

Filename? NRDOS


Mapped NOVA 3/4 RDOS Rev 7.60
Date (m/d/y) ? 08/06/1984
Time (h:m:s) ? 02:41:13

R
LIST
BASIC.DR            512  DY
LINKUTIL.BU          36
RCLI.SV           38400  SD
CREATEUTIL.MC       512  D
MRDOS.OL          30720  C
COMPUCALC.DR        512  DY
NRDOS.OL          30720  C
ZRDOS.OL          31232  C
URDOS.SV          62464  SD
CLI.OL            50176  C
CLI.CM             1877  D
BASIC.SV                  BASICE:ZBASIC.SV
BASICHELP.DR        512  DY
C.DR                512  DY
DEMO$FORT4.DR       512  DY
UTIL$BU.DR          512  DY
DEMO$FORT5.DR       512  DY
FORTRAN5N.DR        512  DY
CREATEUTIL.BU       500  D
ABOOT.SV           6144  SD
DEMO$BASIC.DR       512  DY
UP.MC               270  D
FORT.DR             512  DY
CLI.ER             3584  D
LD.MC                     MACROS:LD.MC
FCLI.S1            1024  D
BASIC.AF            682  D
MD.MC                     MACROS:MD.MC
MRDOS.SV          40448  SD
LL.MC                     MACROS:LL.MC
LM.MC                     MACROS:LM.MC
LN.MC                     MACROS:LN.MC
FORTRAN5E.DR        512  DY
COBOL.DR            512  DY
COM.CM                9
UTILFILES.          231  D
NRDOS.SV          40960  SD
BOOTSYS.SV        60416  SD
LS.MC                     MACROS:LS.MC
MACROS.DR           512  DY
ICOBOLN.DR          512  DY
ZRDOS.SV          40960  SD
DGL.DR              512  DY
LICENSE.TX         5227
LINKUTIL.MC         156  D
DEMO.DR             512  DY
CLI.SV            11264  SD
EBOOT.SV           7168  SD
BYE.MC               17
DEMO$ALGOL.DR       512  DY
URDOS.OL          30720  C
BASICE.DR           512  DY
BASIC.OL                  BASICE:ZBASIC.OL
FCOM.CM               9
ALGOL.DR            512  DY
DEMO$ASM.DR         512  DY
DEMO$DGL.DR         512  DY
BASICN.DR           512  DY
ICOBOLE.DR          512  DY
UTIL.DR             512  DY
LISP.DR             512  DY
FORTH.DR            512  DY
R
```

Session Log for ZRDOS on WH emulator:

```console
Wild Hare Nova/Eclipse Emulator [beta 00.00.07] simulator V4.0-0 Current        git commit id: a06fa926
sim> set CPU Eclipse_S/140
sim> boot DZP

Filename? ZRDOS


Mapped ECLIPSE RDOS Rev 7.60
Date (m/d/y) ? 08/06/1984
Time (h:m:s) ? 08:31:32

R
LIST
BASIC.DR            512  DY
LINKUTIL.BU          36
RCLI.SV           38400  SD
CREATEUTIL.MC       512  D
MRDOS.OL          30720  C
COMPUCALC.DR        512  DY
NRDOS.OL          30720  C
ZRDOS.OL          31232  C
URDOS.SV          62464  SD
CLI.OL            50176  C
CLI.CM             1877  D
BASIC.SV                  BASICE:ZBASIC.SV
BASICHELP.DR        512  DY
C.DR                512  DY
DEMO$FORT4.DR       512  DY
UTIL$BU.DR          512  DY
DEMO$FORT5.DR       512  DY
FORTRAN5N.DR        512  DY
CREATEUTIL.BU       500  D
ABOOT.SV           6144  SD
DEMO$BASIC.DR       512  DY
UP.MC               270  D
FORT.DR             512  DY
CLI.ER             3584  D
LD.MC                     MACROS:LD.MC
FCLI.S1            1024  D
BASIC.AF            682  D
MD.MC                     MACROS:MD.MC
MRDOS.SV          40448  SD
LL.MC                     MACROS:LL.MC
LM.MC                     MACROS:LM.MC
LN.MC                     MACROS:LN.MC
FORTRAN5E.DR        512  DY
COBOL.DR            512  DY
COM.CM                9
UTILFILES.          231  D
NRDOS.SV          40960  SD
BOOTSYS.SV        60416  SD
LS.MC                     MACROS:LS.MC
MACROS.DR           512  DY
ICOBOLN.DR          512  DY
ZRDOS.SV          40960  SD
DGL.DR              512  DY
LICENSE.TX         5227
LINKUTIL.MC         156  D
DEMO.DR             512  DY
CLI.SV            11264  SD
EBOOT.SV           7168  SD
BYE.MC               17
DEMO$ALGOL.DR       512  DY
URDOS.OL          30720  C
BASICE.DR           512  DY
BASIC.OL                  BASICE:ZBASIC.OL
FCOM.CM               9
ALGOL.DR            512  DY
DEMO$ASM.DR         512  DY
DEMO$DGL.DR         512  DY
BASICN.DR           512  DY
ICOBOLE.DR          512  DY
UTIL.DR             512  DY
LISP.DR             512  DY
FORTH.DR            512  DY
R
```

Session Log for RDOS on SIMH Nova emulator:

```console
NOVA simulator V4.0-0 Current        git commit id: 670a3728

Filename?


NOVA RDOS Rev 7.50
Date (m/d/y) ? 08/06/1984
Time (h:m:s) ? 02:09:11

R
LIST
SYS5.LB           17216  D
ALMSPD.RB           476  D
BURST.SV          63750  SD
069400015.01       9714  D
INITIALIZE.SV     12288  SD
COM.CM               55
SEDIT.SV           9216  SD
LITMACS.SR        35527  D
MEDIT.RB           9544  D
MACXR.SV           3584  SD
EDIT.SV            7168  SD
OWNER.SV          63750  SD
FDUMP.SV          16896  SD
DO.SV              2560  SD
069400013.00      40374  D
IDEB.RB            7772  D
TBOOT.SV           1024  SD
OSID.SR            5411  D/PW
MATH.LB            8162  D
BACKUP.             978  D
CLI.SV            11264  SD
OVLDR.SV           7168  SD
CLI.ER             3584  D
ASM.SV            10240  SD
ENPAT.SV           3584  SD
NSID.SR             793  D
CLI.OL            50176  C
MCABOOT.SV         5120  SD
DSKED.SV          22528  SD
PARS.SR           54340  WD/PW
URDOSA.LB         56348  D
069400022.01      13022  D
CLI.CM              131  D
DDUMP.SV          19456  SD
URDOSB.LB          7262  D
ALMSPD.SR          8010  D
DKINIT.SV         40960  SD
PARU.SR           31607  WD/PW
DDUMP.ER           3072  D
URDOSC.LB         64134  D
DDUMP.OL           3072  C
EBOOT.SV           7168  SD
OEDIT.SV           8704  SD
N4ID.SR             792  D
DBURST.SV         63750  SD
069400020.00       1414  D
093400027.00       4762  D
RDOS.SR            1293  D
NSKID.SR           1786  D
SYS.SV            56320  SD
RCLI.SV           38400  SD
SYS.LB            20240  D
SPEED.ER           1536  D
FLOAD.SV          16384  SD
URDOSI.LB          6274  D
SYS.OL            30720  C
CBOOT.SV           1024  SD
VFU.SV             5632  SD
MAC.SV            18944  SD
INSTALL.MC           94  D
RLDR.SV            4608  SD
SYSGEN.SV         23040  SD
EDIT.RB            9192  D
LFE.SV             9216  SD
DLOAD.SV          18944  SD
URDOSO.LB         47234  D
085000022.18      40114  D
RLDR.OL           24576  C
RDOS0750.FL        7469  D
069400019.01       2846  D
ABOOT.SV           6144  SD
PATCH.SV           7168  SD
NFPID.SR           4904  D
DLOAD.OL           2560  C
MBOOT.SV           7168  SD
NBID.SR            4530  D/PW
RFPI.RB            5624
NSPEED.SV          8192  SD
NCID.SR             915  D
FPID.SR            3014  W/PW
BATCH.SV          11776  SD
N3SAC3.RB            68  D
BOOTSYS.SV        60416  SD
MICRODBOOT.SV      4608  SD
NEID.SR            2514  D
BATCH.ER           3584  D
XREF.SV            2048  SD
BATCH.OL          46592  C
R
```

Session Log for RDOS on SIMH Eclipse emulator:

```console
ECLIPSE simulator V4.0-0 Current        git commit id: 670a3728

Filename?


Mapped ECLIPSE RDOS Rev 7.50
Date (m/d/y) ? 08/06/1984
Time (h:m:s) ? 03:52:55

R
LIST
ABOOT.SV           6144  SD
SYS.SV                    @:RDOS.SV
ZRDOS.SR           1316  D
DSKED.SV          22528  SD
RLDR.SV            4608  SD
RDOS.SV           36352  SD
RDOS.LM           22844  D
EDIT.RB            9192  D
085000022.18      40114  D
BATCH.ER           3584  D
COM.CM               10
DKINIT.SV         40960  SD
ENPAT.SV           3584  SD
BACKUP.            1018  D
DLOAD.SV          18944  SD
ZRDOSA.LB         55076  D
DDUMP.SV          19456  SD
ZRDOSB.LB          7192  D
CLI.SV            11264  SD
ZRDOSC.LB         60722  D
MCABOOT.SV         5120  SD
ESAC3.RB             68  D
BTMIN.RB             68  D
LFE.SV             9216  SD
NFPID.SR           4904  D
069400013.00      40374  D
069400019.01       2846  D
ARDOS.SR           1312  D
EDIT.SV            7168  SD
BATCH.OL          46592  C
MAC.SV            18944  SD
DBURST.SV         63750  SD
ZRDOSI.LB         16694  D
RDOS0750.FL        7469  D
EBOOT.SV           7168  SD
RCLI.SV           38400  SD
NBID.SR            4530  D/PW
NSKID.SR           1786  D
NCID.SR             915  D
OWNER.SV          63750  SD
ALMSPD.RB           476  D
NEID.SR            2514  D
ARDOSA.LB         52582  D
PATCH.SV           7168  SD
ARDOSB.LB          7192  D
ZRDOSO.LB         52300  D
ARDOSC.LB         60586  D
OEDIT.SV           8704  SD
SPEED.SV           7168  SD
DDUMP.ER           3072  D
DO.SV              2560  SD
069400022.01      13022  D
CLI.ER             3584  D
OSID.SR            5411  D/PW
MACXR.SV           3584  SD
RFPI.RB            5624
ALMSPD.SR          8010  D
SYS.OL                    @:RDOS.OL
RLDR.OL           24576  C
RDOS.OL           31232  C
ARDOSI.LB         16508  D
SYSGEN.SV         23040  SD
MEDIT.RB           9544  D
MATH.LB            8162  D
INITIALIZE.SV     12288  SD
DLOAD.OL           2560  C
OVLDR.SV           7168  SD
NSID.SR             793  D
DDUMP.OL           3072  C
ARDOSO.LB         52272  D
CLI.OL            50176  C
AIDEB.RB          11122  D
CBOOT.SV           1024  SD
093400027.00       4762  D
LITMACS.SR        35527  D
INSTALL.MC           94  D
XREF.SV            2048  SD
PARS.SR           54340  WD/PW
CLI.CM              129  D
SPEED.ER           1536  D
RDOS.SG            2392
SEDIT.SV           9216  SD
BURST.SV          63750  SD
PARU.SR           31607  WD/PW
TBOOT.SV           1024  SD
BATCH.SV          11776  SD
MICRODBOOT.SV      4608  SD
069400020.00       1414  D
VFU.SV             5632  SD
FLOAD.SV          16384  SD
ABURST.SV         63750  SD
SYS.LB            23612  D
SYS5.LB           20310  D
FDUMP.SV          16896  SD
BOOTSYS.SV        60416  SD
NFFID.SR            435  WD/PW
069400015.01       9714  D
FPID.SR            3014  W/PW
ASM.SV            10240  SD
AOWNER.SV         63750  SD
MBOOT.SV           7168  SD
R
```
