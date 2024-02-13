---
title: "! Unix v5"
description: "! Unix v5 was an operating system for the DEC PDP-11 computer. It was developed by Bell Labs."
date: 2023-02-13T09:08:56+05:30
draft: false
images: [unix-v5-2.webp]
type: docs
weight: 410000
---

{{< load-photoswipe >}}

! Unix v5 was an operating system for the DEC PDP-11 computer. It was developed by Bell Labs. It can be used on SIMH PDP-11 emulator.

<section class="section section-sm">
  <div class="container">
    <div class="row justify-content-center text-center">
      <div class="col-lg-5">
        <p><a class="btn btn-primary btn-md px-4 mb-1" href="https://virtualhub.eu.org/1970s/1974/unix-v5/simh/" role="button">! Unix v5 on SIMH</a></p>
      </div>
    </div>
  </div>
</section>

{{< gallery >}}
  {{< figure src="/1970s/1974/unix-v5/unix-v5-1.webp" alt="Unix v5 boot and list of files in /" caption="Unix v5 boot and list of files in /" >}}
  {{< figure src="/1970s/1974/unix-v5/unix-v5-2.webp" alt="Unix v5: Using cat to print ASCII chart" caption="Unix v5: Using cat to print ASCII chart" >}}
{{< /gallery >}}

Session Log:

```console
PDP-11 simulator Open SIMH V4.1-0 Current        git commit id: 1a1396d0
Disabling XQ
@unix

login: root
# ls
bin
dev
etc
lib
mnt
tmp
unix
usr
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
# ls /bin
ar
as
bas
cat
cc
cdb
check
chmod
chown
clri
cmp
cp
date
db
dc
dd
df
dsw
du
dump
echo
ed
exit
fc
goto
if
kill
ld
ln
login
lpr
ls
mail
mkdir
mv
nm
od
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
# ls /usr/bin
ac
cal
comm
cref
crpost
diff
fed
find
form
grep
mesg
nice
nohup
passwd
pfe
prof
pwd
roff
sa
sleep
sno
split
tee
tr
typo
upost
wc
yacc
#
```
