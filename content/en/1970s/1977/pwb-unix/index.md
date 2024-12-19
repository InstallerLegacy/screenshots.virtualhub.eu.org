---
title: "! PWB Unix"
description: "! PWB Unix, as the name suggests, was an Unix system for the PDP-11 computer."
date: 2024-12-18T09:08:56+05:30
draft: false
images: [pwb-unix.webp]
type: docs
weight: 710000
---

{{< load-photoswipe >}}

! PWB Unix, as the name suggests, was an Unix system for the PDP-11 computer. We can run using the SIMH emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1977/pwb-unix/simh" role="button">! PWB Unix on SIMH</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1977/pwb-unix/pwb-unix.webp" alt="! PWB Unix" caption="! PWB Unix" >}}
{{< /gallery >}}

Session Log:

```console
Unix system sirius (11/23)
Available user memory is 103 KW

login: root
Password:
Welcome to PWB/UNIX
# date
Sun Mar  7 18:39:22 CET 2021
# cat /etc/rc
rm -f /etc/mnttab
echo "ra0a /" | /etc/setmnt
/etc/mount /dev/ra0b /usr
/etc/mount /dev/ra0d /usr/local
/etc/cron
# uname
sirius
# ls
bin
dev
etc
lib
mnt
sys
tmp
u
unix
unix.old
usr
#
```
