FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/itsthw/NewWay /root/NewWay
WORKDIR /root/itsthw/
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
