Wallet
------

- PSBTs created or updated by the wallet now carry the extended public keys
  of the descriptors they use, in the `PSBT_GLOBAL_XPUB` field defined by
  BIP 174. They are left out, along with the derivation paths, when
  `bip32derivs` is false. (#36154)
