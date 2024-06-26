---
title: "! RSTS-11 v4B"
description: "! RSTS-11 v4B was an operating system for the DEC PDP-11 computer. We can run it using the SIMH emulator."
date: 2024-04-21T09:08:56+05:30
draft: false
images: [rsts-11-v4b.webp]
type: docs
weight: 510000
---

{{< load-photoswipe >}}

! RSTS-11 v4B was an operating system for the DEC PDP-11 computer. We can run using the SIMH emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1975/rsts-11-v4b/simh/" role="button">! RSTS-11 v4B on SIMH</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1975/rsts-11-v4b/rsts-11-v4b.webp" alt="! RSTS-11 v4B" caption="! RSTS-11 v4B" >}}
{{< /gallery >}}

Session Log:

```console

PDP-11 simulator Open SIMH V4.1-0 Current        git commit id: ffe537a6
Disabling XQ

RSTS V04B-17 RSTSV4B

OPTION? START
DD-MON-YY? 21-DEC-74
HH:MM? 11:20
RSTS4B - SYSTEM PACK MOUNTED
ENABLE CRASH DUMP? Y
DISABLING INTERFACE FOR KB01:
CHAIN "INIT"
CATASTROPHIC ERROR
PROGRAM LOST-SORRY
I/O CHANNEL NOT OPEN

Ready


SYSTEM INITIALIZATION PROGRAM

END OF FILE ON DEVICE - INIT ASSUMED COMPLETE

Ready

NEW
New file name--

Ready

LENGTH
2K OF CORE USED

Ready

10 PRINT "HI THERE!"
RUN
NONAME  11:21           21-Dec-74
HI THERE!

Ready

BYE
CONFIRM: Y
SAVED ALL DISK FILES; 492 BLOCKS IN USE
JOB 1 USER 1,2 LOGGED OFF KB0 AT 21-Dec-74 11:21
SYSTEM RSTS V04B-17 RSTSV4B
RUN TIME WAS 0 SECONDS
ELAPSED TIME WAS 1 MINUTE, 24 SECONDS
GOOD MORNING



HELLO

RSTS V04B-17 RSTSV4B  JOB 1  KB0  21-Dec-74  11:22
#1,1
PASSWORD:
RSTS V4B-17 IS NOW AVAILABLE...



NEW OR OLD--
RUN [1,2]SHUTUP
AUTOMATIC SYSTEM SHUTDOWN PROGRAM

HOW MANY MINUTES UNTIL SYSTEM SHUTDOWN? 0
HOW MANY MINUTES BETWEEN WARNING MESSAGES? 0
0 MINUTE WARNING MESSAGE SENT
FURTHER LOGINS ARE NOW DISABLED
FINAL WARNING MESSAGE SENT
PASS 1 OF LOOKING FOR STILL ACTIVE JOBS
NON-SYSTEM DISKS WILL NOW BE DISMOUNTED
ALL NON-SYSTEM DISKS ARE NOW DISMOUNTED

ALL SET TO PROCEED WITH SYSTEM SHUTDOWN

PLEASE WAIT FOR THE COMPUTER TO ACTUALLY 'HALT'
WHEN IT DOES, PRESSING 'CONT' WILL BOOT BACK RSTS

HALT instruction, PC: 000056 (BR 146)

:

```
