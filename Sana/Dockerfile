FROM Ajx-Abu/Sana-Mwol:latest

RUN git clone https://github.com/Joshuva-ser/Alfaser /root/sana
WORKDIR /root/sana/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ajx-Abu/sana-media

CMD ["node", "bot.js"]
