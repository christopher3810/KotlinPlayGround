FROM mongo:latest

# under default user settings

ENV MONGO_INITDB_ROOT_USERNAME=mongo 
ENV MONGO_INITDB_ROOT_PASSWORD=12345
ENV MONGO_INITDB_DATABASE=testmongo

COPY ./data /data/db

EXPOSE 27017

CMD ["mongod", "--auth"]

# build command
# docker build -t kotlin_mongo:0.0.1 .

# container run
# docker run -d -p 27017:27017 --name kotlin_mongo kotlin_mongo:0.0.1
# 포트번호나 컨ㅔ이너명은 알ㅏ서 변ㅕㅇ 할  것.