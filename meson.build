project('drawterm', 'c')

includes = include_directories('.', 'include', 'kern')

subdir('kern')
subdir('exportfs')
subdir('libsec')
subdir('libmp')
subdir('libc')
subdir('libauth')
subdir('libauthsrv')
subdir('libmemdraw')
subdir('libmemlayer')
subdir('libdraw')
subdir('libip')
subdir('gui-x11')

drawterm_libs = [
  kern_lib,
  exportfs_lib,
  sec_lib,
  mp_lib,
  c_lib,
  auth_lib,
  authsrv_lib,
  memdraw_lib,
  memlayer_lib,
  draw_lib,
  ip_lib,
  guix11_lib
]

src = '''
main.c
cpu.c
aan.c
secstore.c
latin1.c
posix-factotum.c
posix-amd64/getcallerpc.c
posix-amd64/tas.c
'''.split()

executable('drawterm', src, include_directories: includes, link_with: drawterm_libs)

