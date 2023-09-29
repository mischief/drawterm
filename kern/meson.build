kern_src = '''
  alloc.c
  allocb.c
  chan.c
  data.c
  dev.c
  devaudio.c
  devaudio-unix.c
  devcmd.c
  devcons.c
  devdraw.c
  devenv.c
  devfs-posix.c
  devip.c
  devip-posix.c
  devkbd.c
  devlfd-posix.c
  devmnt.c
  devmouse.c
  devpipe.c
  devroot.c
  devssl.c
  devtls.c
  devtab.c
  error.c
  parse.c
  pgrp.c
  procinit.c
  rwlock.c
  sleep.c
  stub.c
  sysfile.c
  qio.c
  qlock.c
  term.c
  waserror.c
  posix.c
'''.split()

kern_lib = static_library('kern', kern_src, include_directories: includes)

