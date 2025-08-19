ike@ike-X99E:~/Descargas/fenrir-main/bootloader$ python3 -m venv lkpatcher-env
source lkpatcher-env/bin/activate
(lkpatcher-env) ike@ike-X99E:~/Descargas/fenrir-main/bootloader$ pip install git+https://github.com/R0rt1z2/lkpatcher
Collecting git+https://github.com/R0rt1z2/lkpatcher
  Cloning https://github.com/R0rt1z2/lkpatcher to /tmp/pip-req-build-s564vuhq
  Running command git clone --filter=blob:none --quiet https://github.com/R0rt1z2/lkpatcher /tmp/pip-req-build-s564vuhq
  Resolved https://github.com/R0rt1z2/lkpatcher to commit d12bb9a616afd376151fb329e9c6193330b94cd9
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting liblk@ git+https://github.com/R0rt1z2/liblk@master (from lkpatcher==4.0.0)
  Cloning https://github.com/R0rt1z2/liblk (to revision master) to /tmp/pip-install-gi6fcnyj/liblk_15b4c6a8f9f74c10a1d4dda6bf5cbe0a
  Running command git clone --filter=blob:none --quiet https://github.com/R0rt1z2/liblk /tmp/pip-install-gi6fcnyj/liblk_15b4c6a8f9f74c10a1d4dda6bf5cbe0a
  Resolved https://github.com/R0rt1z2/liblk to commit f58fd75f4e52eb8b1c8eaec8c2d5a93cfef6ef71
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Building wheels for collected packages: lkpatcher, liblk
  Building wheel for lkpatcher (pyproject.toml) ... done
  Created wheel for lkpatcher: filename=lkpatcher-4.0.0-py3-none-any.whl size=28120 sha256=451fadb18f629148277d3d59015e045d23592d278535604e542a83608a3a7f60
  Stored in directory: /tmp/pip-ephem-wheel-cache-4uca1alh/wheels/67/83/3e/a2452bcf33505b3bc083b298e81af6d937574fa1f907a0e48f
  Building wheel for liblk (pyproject.toml) ... done
  Created wheel for liblk: filename=liblk-2.1.0-py3-none-any.whl size=39159 sha256=948c87142d5d8d14e00f393d0bdb583c47d1825d82790c5942ce06070e746910
  Stored in directory: /tmp/pip-ephem-wheel-cache-4uca1alh/wheels/92/d5/45/e996e4bbe3894b99c8f2821af9f92ff811ca540c5a0428cf8b
Successfully built lkpatcher liblk
Installing collected packages: liblk, lkpatcher
Successfully installed liblk-2.1.0 lkpatcher-4.0.0
(lkpatcher-env) ike@ike-X99E:~/Descargas/fenrir-main/bootloader$
---

(lkpatcher-env) ike@ike-X99E:~/Descargas/fenrir-main/bootloader$ python3 -m lkpatcher lk.img -d lk
[INFO] MediaTek bootloader (LK) patcher - version: 4.0.0 by R0rt1z2
[INFO] Successfully loaded 6 patches in 4 categories
[INFO] Loaded image from lk.img with 5 partitions
========================================
Partition Name  : lk
Data Size       : 990320 bytes
Addressing Mode : -1
Memory Address  : 0xffffffff
Header Size     : 512 bytes
Header Version  : 1
Image Type      : 0x00000000
Image List End  : False
Alignment       : 16 bytes
Data Size       : 0 bytes
Memory Address  : 0x00000000
========================================
[INFO] Successfully dumped partition lk to lk_lk.bin
(lkpatcher-env) ike@ike-X99E:~/Descargas/fenrir-main/bootloader$ 
(lkpatcher-env) ike@ike-X99E:~/Descargas/fenrir-main/bootloader$ ls -la lk_lk.bin
-rw-rw-r-- 1 ike ike 990320 ago 19 16:16 lk_lk.bin
(lkpatcher-env) ike@ike-X99E:~/Descargas/fenrir-main/bootloader$ 
