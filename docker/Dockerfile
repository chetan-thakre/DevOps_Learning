#Multi build images
FROM ubuntu AS base
RUN apt-get update -y && apt-get install git -y

FROM base AS src1
RUN git clone https://github.com/chetan-thakre/python_code.git 

