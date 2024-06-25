---
title: "! Unix v6"
description: "! Unix v6 was an operating system for the DEC PDP-11 computer. It was developed by Bell Labs."
date: 2024-04-23T09:08:56+05:30
draft: false
images: [unix-v6.webp]
type: docs
weight: 520000
---

{{< load-photoswipe >}}

! Unix v6 was an operating system for the DEC PDP-11 computer. It was developed by Bell Labs. It can be used on SIMH PDP-11 emulator. It was also ported to Interdata 7/32 computer, so we can use that port on SIMH Interdata 7/32 emulator.
<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1975/unix-v6/simh-pdp11/" role="button">! Unix v6 on SIMH PDP-11</a></p>
      </div>
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1975/unix-v6/simh-id32/" role="button">! Unix v6 on SIMH Interdata 7/32</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1975/unix-v6/unix-v6.webp" alt="! Unix v6" caption="! Unix v6" >}}
  {{< figure src="/1970s/1975/unix-v6/unix-v6-id32.webp" alt="! Unix v6 Interdata 7/32 port" caption="! Unix v6 Interdata 7/32 port" >}}
{{< /gallery >}}

Session Log of PDP-11 version:

```console

PDP-11 simulator Open SIMH V4.1-0 Current        git commit id: ffe537a6
Disabling XQ
/home/pulkit/Documents/VirtualHub/VMs/SIMH/1970s/1975/Unix v6/pdp11.ini-12> att dci 5555
%SIM-INFO: Listening on port 5555
@unix

login: root
# ls
bin
dev
etc
hpunix
lib
mnt
rkunix
rpunix
tmp
unix
usr
# ls /bin
ar
as
bas
cat
cc
cdb
chgrp
chmod
chown
clri
cmp
cp
date
db
dc
dcheck
dd
df
dsw
du
dump
echo
ed
exit
fc
file
goto
icheck
if
kill
ld
ln
login
ls
mail
mkdir
mv
ncheck
newgrp
nm
od
opr
passwd
pr
ps
restor
rew
rm
rmdir
sh
size
sort
strip
stty
su
sum
sync
time
tp
tty
uniq
who
write
# chdir usr
# ls
adm
bin
doc
fort
games
ken
lib
lpd
mdec
pub
source
sys
tmp
# ls pub
ascii
deverr
greek
hanoi
kbd
tabs
# cat pub/ascii
|000 nul|001 soh|002 stx|003 etx|004 eot|005 enq|006 ack|007 bel|
|010 bs |011 ht |012 nl |013 vt |014 np |015 cr |016 so |017 si |
|020 dle|021 dc1|022 dc2|023 dc3|024 dc4|025 nak|026 syn|027 etb|
|030 can|031 em |032 sub|033 esc|034 fs |035 gs |036 rs |037 us |
|040 sp |041  ! |042  " |043  # |044  $ |045  % |046  & |047  ' |
|050  ( |051  ) |052  * |053  + |054  , |055  - |056  . |057  / |
|060  0 |061  1 |062  2 |063  3 |064  4 |065  5 |066  6 |067  7 |
|070  8 |071  9 |072  : |073  ; |074  < |075  = |076  > |077  ? |
|100  @ |101  A |102  B |103  C |104  D |105  E |106  F |107  G |
|110  H |111  I |112  J |113  K |114  L |115  M |116  N |117  O |
|120  P |121  Q |122  R |123  S |124  T |125  U |126  V |127  W |
|130  X |131  Y |132  Z |133  [ |134  \ |135  ] |136  ^ |137  _ |
|140  ` |141  a |142  b |143  c |144  d |145  e |146  f |147  g |
|150  h |151  i |152  j |153  k |154  l |155  m |156  n |157  o |
|160  p |161  q |162  r |163  s |164  t |165  u |166  v |167  w |
|170  x |171  y |172  z |173  { |174  | |175  } |176  ~ |177 del|
#

```

Session Log of Interdata 7/32 version:

```console

Interdata 32b simulator Open SIMH V4.1-0 Current        git commit id: ffe537a6
/home/pulkit/Documents/VirtualHub/VMs/SIMH/1970s/1975/Unix v6 id32/id32.ini-3> d lfc tps 100
Read only argument
?unix
Memory = 182.50 K

login: root
# ls
bin
dev
etc
lib
mdl
mnt
tmp
tpboot
tuboot
uboot
unix
unix.oxon
unix.sydney
usr
# ls /bin
STTY
ar
as
cat
cc
chmod
cmp
cp
date
dd
df
dsw
du
echo
ed
exit
file
goto
if
kill
ld
ln
login
ls
mail
mkdir
mv
newgrp
nm
od
opr
passwd
pr
ps
rm
rmdir
sh
size
sort
strip
stty
su
sync
time
tty
who
write
# cat /usr/pub/ascii
|000 nul|001 soh|002 stx|003 etx|004 eot|005 enq|006 ack|007 bel|
|010 bs |011 ht |012 nl |013 vt |014 np |015 cr |016 so |017 si |
|020 dle|021 dc1|022 dc2|023 dc3|024 dc4|025 nak|026 syn|027 etb|
|030 can|031 em |032 sub|033 esc|034 fs |035 gs |036 rs |037 us |
|040 sp |041  ! |042  " |043  # |044  $ |045  % |046  & |047  ' |
|050  ( |051  ) |052  * |053  + |054  , |055  - |056  . |057  / |
|060  0 |061  1 |062  2 |063  3 |064  4 |065  5 |066  6 |067  7 |
|070  8 |071  9 |072  : |073  ; |074  < |075  = |076  > |077  ? |
|100  @ |101  A |102  B |103  C |104  D |105  E |106  F |107  G |
|110  H |111  I |112  J |113  K |114  L |115  M |116  N |117  O |
|120  P |121  Q |122  R |123  S |124  T |125  U |126  V |127  W |
|130  X |131  Y |132  Z |133  [ |134  \ |135  ] |136  ^ |137  _ |
|140  ` |141  a |142  b |143  c |144  d |145  e |146  f |147  g |
|150  h |151  i |152  j |153  k |154  l |155  m |156  n |157  o |
|160  p |161  q |162  r |163  s |164  t |165  u |166  v |167  w |
|170  x |171  y |172  z |173  { |174  | |175  } |176  ~ |177 del|
#

```
