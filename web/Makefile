#!/usr/bin/env make

run_website:
	docker build -t icecream.com . && \
		docker run -p 5001:80 -d --name icecream.com --rm icecream.com

stop_website:
	docker stop icecream.com
