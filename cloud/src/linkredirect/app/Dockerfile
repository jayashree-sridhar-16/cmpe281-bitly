FROM golang:latest 
EXPOSE 3001
RUN mkdir /app 
ADD . /app/ 
WORKDIR /app 
ENV GOPATH /app
RUN cd /app ; go install linkredirect
CMD ["/app/bin/linkredirect"]
