FROM fusuf/whatsasena:latest

RUN git clone https://github.com/rasanjanapiumal99/RPS_WA /root/RPS_WA/
WORKDIR /root/RPS_WA/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
