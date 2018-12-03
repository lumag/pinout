<!--
---
name: Secure96
class: board
type: Mezzanine
description: Security DevKit for 96Boards
url: https://www.96boards.org/product/secure96/
github: https://github.com/96boards/documentation/tree/master/mezzanine/secure96
schematic: https://github.com/96boards/documentation/raw/master/mezzanine/secure96/files/secure96-schematics.pdf
buy: https://amzn.to/2qWN1CC
image: 'secure96.jpg'
pincount: 40
power:
  '37':
ground:
  '1':
  '2':
  '39':
  '40':
pin:
  '3':
    mode: uart
  '5':
    mode: uart
  '7':
    mode: uart
  '9':
    mode: uart
  '15':
    mode: i2c
  '17':
    mode: i2c
  '8':
    mode: spi
  '10':
    mode: spi
  '12':
    mode: spi
  '14':
    mode: spi
  '24':
    mode: gpio
  '26':
    mode: gpio

-->

# Secure96

This mezzanine board is intended for security development on 96Boards and features the Infineon SLB9670, Atmel ATSHA204A, and the Atmel ATECC508A chip sets.

With 128Kb of onboard storage, a PC TPM/embedded TPM chip, and a FT230XS-R UART connector for debug, it is an ideal addition to your 96Boards tool box.

# Features:

- SoC
  - Infineon SLB9670
  - Atmel ATSHA204A
  - Atmel ATECC508A
- Certifications
  - CC EAL4+
- Sub Application
  - PC TPM/embedded TPM
- Storage
  - 128KB onboard Flash
- Symmetric Cryptography
  - AES/HMAC/SHA-1/SHA-256
- Asymmetric Cryptography
  - ECC/ECC BN-256/ECC NIST
  - P256/ECC256/ECDH/RSA1024/RSA2048
- Connectors
  - FT230XS-R UART debug
- Expansion Interface
  - 40 Pin Low-speed expansion
- Digital Output (V)
  - 1.8V
- Analog Input (V)
  - 0V-1.8V
- Size
  - 60x30mm

# Buy Now
- [Amazon](https://amzn.to/2qWN1CC)
