#!/usr/bin/env make

run_website:
	docker build -t icecream.in . && \
		docker run -p 5000:80 -d --name icecream.in --rm icecream.in

stop_website:
	docker stop icecream.in
