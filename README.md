# Thalassa Docker

This is a [docker] container definition to install [Thalassa].

![Thalassa Architecture](https://i.cloudup.com/ePiFdhNTTH-3000x3000.png)

The stack contains the following programs:

* [Node.js] v0.10.22
* [Redis] v2.6.16
* [haproxy] v1.4.0
* [mongroup] v0.4.0

And the following Thalassa components:

* [Thalassa]; Service registry, Node.js client and CLI tools
* [Crowsnest]; Dashboard
* [Aqueduct]; Zero downtime deploys on HA Proxy


[docker]: http://docker.io
[Redis]: http://redis.io
[mongroup]: https://github.com/visionmedia/node-mongroup
[haproxy]: http://haproxy.1wt.eu
[Node.js]: http://nodejs.org
[Thalassa]: https://github.com/PearsonEducation/thalassa
[Crowsnest]: https://github.com/PearsonEducation/thalassa-crowsnest
[Aqueduct]: https://github.com/PearsonEducation/thalassa-aqueduct
