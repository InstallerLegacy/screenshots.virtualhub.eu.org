---
title: "! CAPS-8"
description: "! CAPS-8 was an operating system for the PDP-8 computer. We can run it on SIMH PDP-8 emulator."
date: 2024-04-11T09:08:56+05:30
draft: false
images: [caps-8.webp]
type: docs
weight: 330000
---

{{< load-photoswipe >}}

! CAPS-8 was an operating system for the PDP-8 computer. We can run it on SIMH PDP-8 emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1973/caps-8/simh/" role="button">! CAPS-8 on SIMH</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1973/caps-8/caps-8.webp" alt="! CAPS-8" caption="! CAPS-8" >}}
{{< /gallery >}}

Session Log:

```console
PDP-8 simulator Open SIMH V4.1-0 Current        git commit id: e444c674
/home/pulkit/Documents/VirtualHub/VMs/SIMH/1970s/1973/CAPS-8/pdp8.ini-3> att ct0 caps8.tu60
%SIM-INFO: CT0: Tape Image 'caps8.tu60' scanned as SIMH format

.DIR

C2BOOT.BIN            V1
MONTOR.BIN            V2
SYSCOP.BIN            V2
EDIT  .BIN            V1
BASIC .BIN            V1
PALC  .BIN            V2
UTIL  .BIN            V1
BOOT  .BIN            V3
CODT  .PA

.

```
