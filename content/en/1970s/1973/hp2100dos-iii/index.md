---
title: "! HP 2100 DOS-III"
description: "! HP 2100 DOS-III, as the name suggests, was an operating system for the HP 2100 computer."
date: 2024-04-21T09:08:56+05:30
draft: false
images: [hp2100dos-iii.webp]
type: docs
weight: 340000
---

{{< load-photoswipe >}}

! HP 2100 DOS-III, as the name suggests, was an operating system for the HP 2100 computer. We can run using the SIMH emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1973/hp2100dos-iii/simh/" role="button">! HP 2100 DOS-III on SIMH</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1973/hp2100dos-iii/hp2100dos-iii.webp" alt="! HP 2100 DOS-III" caption="! HP 2100 DOS-III" >}}
{{< /gallery >}}

Session Log:

```console

HP 2100 simulator V3.12-2 Release 32

Programmed halt, T: 102077 (HLT 77), P: 02020 (CLC 0,C)

INPUT :DATE,XXXXXXXXXX,H,M

@:DATE,10JULY1975
SUBCHAN=1
LBL=SYS01
@
:JOB
JOB       10JULY1975 TIME=0000 MIN. 06.5 SECS.
@
:LIST,U,1


NAME TYPE  SCTRS  DISC ORG   PROG LIMITS   B.P. LIMITS   ENTRY FWAM   PB
SUBCHAN=1
BFILE UM   00003  T001 000   20000 20404   01000 01000   20000 20404
CFILE UM   00011  T001 003   20000 22253   01000 01060   20000 22253
$FILS BD   00050  T001 014
BASIC UM   00103  T002 016   21464 52137   01000 01635   21543 23624
BYE   US   00001  T004 023   52137 52237   01635 01635   52143 52237
LENGT US   00001  T004 024   52137 52224   01635 01635   52144 52224
TIME  US   00001  T004 025   52137 52232   01635 01635   52144 52232
DELET US   00001  T004 026   52137 52267   01635 01635   52146 52267
RENUM US   00004  T004 027   52137 53001   01635 01635   52165 53001
NAME  US   00001  T004 031   52137 52307   01635 01635   52151 52307
GETB  US   00002  T004 032   52137 52404   01635 01635   52161 52404
CATAL US   00002  T004 034   52137 52454   01635 01635   52163 52454
KILL  US   00002  T004 036   52137 52522   01635 01635   52164 52522
SAVE  US   00002  T004 038   52137 52452   01635 01635   52170 52452
CSAVE US   00003  T004 040   52137 52560   01635 01635   52201 52560
APPEN US   00002  T004 043   52137 52504   01635 01635   52162 52504
CHAIN US   00002  T004 045   52137 52474   01635 01635   52176 52474
OPEN  US   00003  T004 047   52137 52605   01635 01635   52173 52605
FILES US   00003  T005 002   52137 52732   01635 01635   52174 52732
ASSIG US   00002  T005 005   52137 52373   01635 01635   52153 52373
@

```
