FROM alpine:3.2

RUN apk upgrade -f

RUN apk add --update musl python3 python3-doc python3-dev python3-tests py-pip && \
    rm /var/cache/apk/*
	
CMD ["python3"]