FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/wdsaviya/Saviya-Md /root/wdsaviya
WORKDIR /root/wdsaviya/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
