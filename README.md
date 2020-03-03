# Secure Hash Algorithm in C
## [ian.mcloughlin@gmit.ie](mailto:ian.mcloughlin@gmit.ie)

Reads from a file:

```bash
sha256 $ make sha256
cc     sha256.c   -o sha256
sha256 $ touch emptyfile
sha256 $ ./sha256 emptyfile 
e3b0c44298fc1c149afbf4c8996fb92427ae41e4649b934ca495991b7852b855
```