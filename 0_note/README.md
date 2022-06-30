
```
cd openssl/demos/sslecho
LD_LIBRARY_PATH=../../ ./sslecho  s
LD_LIBRARY_PATH=../../ ./sslecho c localhost

或者

LD_LIBRARY_PATH=. ./apps/openssl s_client -connect 127.0.0.1:4433
```