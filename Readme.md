This repo contains the Annotated and unannotated version of nayuki/Bitcoin-CryptoGraphy-Library(Excluding tests)

Annotated version is on branch signedness_library, Unannotated version is on master.

It is better to compile files indivisually as there are errors in files.

Commands-

```
cd Bitcoin-Cryptography-Library/java
javac -processor signedness io/nayuki/bitcoin/crypto/"Filename".java
```

In this case study I learnt that signedness checker is weak in some classes and needs enhancements such as:-

1.)java.lang.System- arraycopy() function
2.)java.util.Arrays - fill() function
3.)java.lang.String- toCharArray() function
3.)Non equality comparisons of unsigned values
4.)Issue came repeatedly like Issue #2482.


When you will run the test file using signedness checker you will get many errors(I have not wriiten some in the doumnetation as there are many) of-

1.)System.arraycopy()

2.)Arrays.fill()

3.)Non equality comparisons of unsigned values
