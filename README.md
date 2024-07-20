# Implementaion of a Web Server using Multi-threading

This repository contains three implementaions of a web server

1. Single Threaded Web Server
2. Multi Threaded Web Server
3. Web Server using Thread Pool

I have also tested the servers using JMeter, the Single Threaded server was fine till 6000 request in 60 sec, but the deviation was too high on 60000 requests/min. The Multithreaded server showed less deviation on 60000 req/min. The thread Pool implementation was the most optimal one as it had a less deviation even on 600000 req/min.
