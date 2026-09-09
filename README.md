README for the contactless-keyring package
=====================================


Introduction
------------

Wiren Board uses these keys to sign releases that are stored on https://deb.wirenboard.com.

```sh
$ gpg --no-default-keyring --keyring keyrings/contactless-keyring.gpg --list-keys
keyrings/contactless-keyring.gpg
--------------------------------
pub   rsa2048 2014-04-23 [SC]
      B750A0D6805540824F039964E4B0949FAEE07869
uid           [ unknown] Evgeny Boger <boger@contactless.ru>
sub   rsa2048 2014-04-23 [E]
      EFDC4B63F8F0D426275E59D15886DAF6D8C36D9B

pub   rsa2048 2016-12-18 [SC]
      77326BACD64B392F1014B37FBD4CEEDBAA549AA8
uid           [ unknown] wirenboard <robot@contactless.ru>
sub   rsa2048 2016-12-18 [E]
      57202478EA2C96123422650F71DFECFC0961B528
```
