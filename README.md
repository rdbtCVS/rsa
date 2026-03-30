# rsa

The rat that was added by the leakers was removed. original rsa has no rat.

`rsa` is an addon for [`rsm`](https://github.com/rs-mod/rsm).

```bash
git clone https://github.com/rs-mod/rsa.git
cd rsa
git submodule update --init --recursive
cd rsm && ./gradlew --no-daemon remapJar && cd ..
./gradlew build
```
