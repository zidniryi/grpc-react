# grpc-react

## run server

- cd grpc-chat
- npm i 
- npm run start

## run fe

- cd grpc-chat-react
- npm i 
- npm run start

## run docker
- docker build -t grpc-web-react .  
- docker run -d --name grpc-web-react -p 8080:8080 -p 9901:9901 grpc-web-react
