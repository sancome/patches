patches for jlars's script, fix bugs for Openwrt AA and Trunk version
==============
What it is
----------
 * openwrt_shairport.patch
    - http://www.loetzimmer.de/patches/
    - some init- and config scripts to auto-start shairport on OpenWRT
    - combined with openwrt_libao.patch below, allows for EsounD and
      Shairport running on the same device simultaneously - Shairport
      outputting its sound via EsounD
    - IPv4 only patch included
    - (the shairport package is maintained at:
	  src-git jlars git://github.com/jlars/packages.git;master)

 * shairport_deps_trunk.diff
    - ftp://ftp.custom-openwrt-builds.info/patches/shairport_deps_trunk.diff
