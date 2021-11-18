FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Millie-011/ARYA-STARK /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
