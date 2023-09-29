guix11_src = '''
  x11.c
  keysym2ucs-x11.c
'''.split()

x11_dep = dependency('x11')

guix11_lib = static_library('guix11', guix11_src, dependencies: [ x11_dep ], include_directories: includes)

