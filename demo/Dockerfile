FROM node:14
WORKDIR /home/node/app/
COPY ./package*.json /home/node/app/
RUN npm install
COPY . .
EXPOSE 3333
CMD ["npm", "start"]

# FROM node:14
# ENV APP_ROOT /src

# # RUN mkdir ${APP_ROOT}
# WORKDIR /usr/src/app/
# # ADD . ${APP_ROOT}
# COPY ./package*.json /usr/src/app/
# RUN yarn install
# RUN yarn run build

# EXPOSE 3000
