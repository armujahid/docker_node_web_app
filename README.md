Build your own image:
`docker build . -t <your username>/docker-node-web-app`
`docker run -p 8081:8080 -d <your username>/docker-node-web-app`

OR

Pull already created image:
`docker run -p 8081:8080 -d armujahid/docker-node-web-app`


App should be accessible at http://localhost:8081/