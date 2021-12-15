FROM fusuf/whatsasena:latest

RUN git clone https://CYBER-DIE:cyberdie777@github.com/ABID-SER-BOT/asenatest /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
