# prometheus_grafana_traefik_authelia

credits to: 

https://traefik.io/blog/traefik-2-tls-101-23b4fbee81f1/

https://github.com/vegasbrianc/docker-traefik-prometheus

https://github.com/stefanprodan/dockprom

https://www.authelia.com/docs/deployment/supported-proxies/traefik2.x.html


I created this repository for newbies like myself, with basic understanding of docker. 

I wanted to have some kind of authentication in front of prometheus/grafana. That's how traefik and authelia came to the picture. Now, the problem with these two, for me was that I couldn't find a solution which worked out of the box. However I found a lot of forums, explaining the need for one.
So I figured, if I managed to put this together might as well share it, and save some headaches for others. I think the struggle for the most was around certs, and https for traefik and authelia middleware. Which is pretty easily solveable, once you start reading documentation.

Ui.: If you know, certs and PKI my solution is not for you.  