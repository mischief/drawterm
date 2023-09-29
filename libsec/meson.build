sec_src = '''
  aes.c
  aesni.c
  aesCBC.c
  aes_gcm.c
  poly1305.c
  chacha.c
  chachablock.c
  ccpoly.c
  des.c
  des3CBC.c
  desmodes.c
  ecc.c
  jacobian.c
  secp256k1.c
  secp256r1.c
  secp384r1.c
  curve25519.c
  curve25519_dh.c
  genrandom.c
  fastrand.c
  nfastrand.c
  prng.c
  hmac.c
  hkdf.c
  pbkdf2.c
  rsaalloc.c
  rsadecrypt.c
  rsaencrypt.c
  dh.c
  rc4.c
  md5.c
  md5block.c
  sha1.c
  sha2_128.c
  sha2_64.c
  sha1block.c
  sha2block128.c
  sha2block64.c
  tlshand.c
  x509.c
  tsmemcmp.c
'''.split()

sec_lib = static_library('sec', sec_src, include_directories: includes)

