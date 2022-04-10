FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Itsme-soman/KICHU-SER /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN heroku nodejs-yarn-buildpack
RUN git clone https://github.com/Itsme-soman/medias

CMD ["node", "bot.js"]
