ARG ELK_VERSION

# https://github.com/elastic/elasticsearch-docker
FROM elasticsearch:${ELK_VERSION}

RUN elasticsearch-plugin install -b http://120.55.166.227:8000/elasticsearch-analysis-ik-7.4.1.zip
#RUN elasticsearch-plugin install -b https://github.com/medcl/elasticsearch-analysis-pinyin/releases/download/v7.4.1/elasticsearch-analysis-pinyin-7.4.1.zip


# Add your elasticsearch plugins setup here
# Example: RUN elasticsearch-plugin install analysis-icu
