FROM alpine:3.7

RUN apk add curl bash fortune

COPY loadgen.sh .
RUN chmod +x ./loadgen.sh

ENV HOSTPORT = 3000

CMD [ "./loadgen.sh" ]
