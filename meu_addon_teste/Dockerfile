FROM alpine:3.18

RUN apk add --no-cache bash

COPY run.sh /run.sh
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
