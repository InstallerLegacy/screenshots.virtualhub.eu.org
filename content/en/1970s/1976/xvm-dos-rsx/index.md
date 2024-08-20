---
title: "! XVM/DOS & ! XVM/RSX"
description: "! XVM/DOS and ! XVM/RSX were operating systems for the DEC PDP-15 computer. We can run them using the SIMH emulator."
date: 2024-04-21T09:08:56+05:30
draft: false
images: [xvm-dos.webp]
type: docs
weight: 610000
---

{{< load-photoswipe >}}

! XVM/DOS and ! XVM/RSX were operating systems for the DEC PDP-15 computer. We can run them using the SIMH emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-sm px-4 mb-1" href="https://virtualhub.eu.org/1970s/1976/xvm-dos-rsx/simh/" role="button">! XVM/DOS and XVM/RSX on SIMH</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1976/xvm-dos-rsx/xvm-dos.webp" alt="! XVM/DOS" caption="! XVM/DOS" >}}
  {{< figure src="/1970s/1976/xvm-dos-rsx/xvm-rsx.webp" alt="! XVM/RSX" caption="! XVM/RSX" >}}
{{< /gallery >}}

Session Log of ! XVM/DOS:

```console

PDP-15 simulator Open SIMH V4.1-0 Current        git commit id: ffe537a6
/home/pulkit/Documents/VirtualHub/VMs/SIMH/1970s/1976/XVM-DOS/pdp15.ini-5> a ttix 2311
%SIM-INFO: Listening on port 2311


XVM/DOS V1A000
 ENTER DATE (MM/DD/YY) - 04/26/74


PAGE MODE  128K  API ON  XVM ON  SCR

$PIP

PIP XVM V1A000

>L TT_SY

     26-APR-74
 DIRECTORY LISTING  (SCR)
 110712 FREE BLKS
      6 USER FILES
    316 USER BLKS
 BUILD  XCT       1  13-JAN-99
 BUILD  XCU      33  13-JAN-99
 CODE   SRC     105  13-JAN-99
 RSXPAT XCT       1  13-JAN-99
 RSXPAT XCU       1  13-JAN-99
 RSX    BAT     153  13-JAN-99


>^C

XVM/DOS V1A000

$

```

Session Log of ! XVM/RSX:

```console

PDP-15 simulator Open SIMH V4.1-0 Current        git commit id: ffe537a6
/home/pulkit/Documents/VirtualHub/VMs/SIMH/1970s/1976/XVM-RSX/pdp15.ini-5> a ttix 2311
%SIM-INFO: Listening on port 2311


XVM/DOS V1A000
 ENTER DATE (MM/DD/YY) - 04/26/84


PAGE MODE  128K  API ON  XVM ON  SCR

$RSX

MCR>

```
