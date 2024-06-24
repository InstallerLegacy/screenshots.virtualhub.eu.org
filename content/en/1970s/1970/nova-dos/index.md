---
title: "! Nova DoS"
description: "! Nova DOS, as the name suggests, was an operating system for the Nova computer."
date: 2024-06-24T09:08:56+05:30
draft: false
images: [nova-dos.webp]
type: docs
weight: 170000
---

{{< load-photoswipe >}}

! Nova DOS, as the name suggests, was an operating system for the Nova computer. We can run using the Wild Hare Nova emulator.

{{< gallery >}}
  {{< figure src="/1970s/1970/nova-dos/nova-dos.webp" alt="! Nova DOS" caption="! Nova DOS" >}}
{{< /gallery >}}

Session Log:

```console
Wild Hare Nova/Eclipse Emulator [beta 00.00.07] simulator V4.0-0 Current        git commit id: a06fa926

DOS REV 05.
HALT instruction, PC: 000116 (JMP @43)

R
LIST
COM.CM               7
EDIT.SV           4352  S
XREF.SV           2432  S
ASM.SV            8748  S
CLI.LB           20524
LFE.SV            7552  S
SYS.LB            5376
RLDR.SV           4992  S
SYS0.LB          11648
SYSGEN.SV         5376  S
PARS.SR           4568
PARU.SR           8797
BLDR.KS            448
BLDR.SR           3820
EXEC.SV           1920  SW
SYS1A.LB         12454
HELLOWORLD.SR      574
HELLOWORLD.RB      222
HELLOWORLD.SV     1152  S
SYS000.RB          282
NREL.                9
HMA.RB             150
BLDR.SV           1536  S
SYS000.SV        64256  S
HMA.SR             121
HMA.SV            1024  S
BLDR.RB            790
R

Simulation stopped, PC: 074245 (MOVL# 0,0,SZC)
sim> exit
Goodbye
```
