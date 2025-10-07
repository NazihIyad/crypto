Usage:
  ./crypto MODE ALGORITHM TEXT [KEY]

Modes:
  e, encrypt    Encrypt the input text
  d, decrypt    Decrypt the input text

Algorithms:
  c, caesar     Caesar cipher
  v, vigenere   Vigenère cipher

Examples:
  ./crypto e c HELLO
  ./crypto d v LXFOPVEFRNHR LEMON
