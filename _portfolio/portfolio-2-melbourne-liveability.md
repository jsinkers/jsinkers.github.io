---
title: "Melbourne liveability"
excerpt: "Development of a cloud-deployed system to explore liveability indicators in Melbourne<br/><img src='/images/melbourne-liveability.png'>"
collection: portfolio
---

Group project for Cluster and Cloud Computing, 2022

![Melbourne Liveability](/images/melbourne-liveability.png)

As a team of 5, we implemented a web-app deployed on the cloud to explore liveability in Melbourne, presenting data on maps and charts. We explored social engagement and opportunity liveability indicators using a combination of government datasets and tweets that we harvested. We deployed 4 VMs on the Melbourne Research Cloud using Ansible, with a 3-node CouchDB cluster.

- [source](https://github.com/jsinkers/comp90024-assignment-2)
- [site demo video](https://youtu.be/_TJ7u7xXZpU)
- [Ansible deployment video](https://youtu.be/s9CQWb1iy7U)

## Architecture

![Architecture](/images/ccc-architecture.png)

## Technology

- Ansible: used for deployment of VMs on the Melbourne Research Cloud, creation of volumes and security groups, installation of dependencies
- Docker: used for CouchDB instances and twitter harvesters
- Svelte: front-end framework making use of MapBox and D3.js to present interactive charts and maps
- Python: used for tweet harvesting (stream and search Twitter APIs) and sentiment analysis using VaderSentiment
- Flask: used to implement ReST API
- Gunicorn: application server for Flask API
- Nginx: web server
- CouchDB: NoSQL database used in a 3-node cluster
