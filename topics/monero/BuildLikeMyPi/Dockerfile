FROM debian:buster-slim

RUN apt update \
  && apt-get install -y git build-essential cmake automake libtool autoconf wget \
  && git clone https://github.com/xmrig/xmrig.git \
  && mkdir xmrig/build && cd xmrig/scripts \
  && ./build_deps.sh && cd ../build \
  && cmake .. -DXMRIG_DEPS=scripts/deps \
  && make -j$(nproc)

COPY ./start.sh /

ENV CN=docker1

CMD "/start.sh"

