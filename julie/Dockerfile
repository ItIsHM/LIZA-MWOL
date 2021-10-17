FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ItIsHM/LIZA-MWOL /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/ItsIsHM/media

CMD ["node", "bot.js"]
