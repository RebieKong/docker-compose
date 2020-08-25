FROM elasticsearch:6.5.4
USER elasticsearch
RUN mkdir -p /usr/share/elasticsearch/plugins/ik
WORKDIR  /usr/share/elasticsearch/plugins/ik
COPY elasticsearch-analysis-ik-6.5.4.zip ./
RUN unzip elasticsearch-analysis-ik-6.5.4.zip
