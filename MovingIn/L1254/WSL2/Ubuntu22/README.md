# Don't use Forticlient

This intermittently screws up the downloads (what a surprise).

# Juliaup on WSL : Works (with correct curl)


# Juliaup On WSL : Fails

Due to anaconda curl, use /usr/bin/curl and it is fine.

(base) astephen@L1254:Ubuntu22$ curl -fsSL https://install.julialang.org | sh

info: downloading installer
Warning: Not enforcing strong cipher suites for TLS, this is potentially less secure
Warning: Not enforcing TLS v1.2, this is potentially less secure
curl: (35) Recv failure: Connection reset by peer
juliaup: command failed: downloader https://julialang-s3.julialang.org/juliaup/bin/juliainstaller-1.17.19-x86_64-unknown-linux-musl /tmp/tmp.ZmxC2twXcH/juliainstaller x86_64-unknown-linux-musl

