FROM ghost:alpine

RUN npm i ghost-storage-adapter-s3
RUN mkdir -p ./content/adapters/storage
RUN cp -r ./node_modules/ghost-storage-adapter-s3 ./content/adapters/storage/s3

COPY ./themes/packages/solo ./content/themes/solo
