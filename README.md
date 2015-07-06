# jupyter
Vagrant file to setup a virtualbox running some tools 
- ipython (jupyter) with different kernels: Python2, Python3, NodeJS, iTorch, R, Bash, Go
- Additionally to the mentioned languages there is Ruby
- Node-Red
- MySQL and Cassandra Database
- elasticSearch, MongoDB, Redis and etcd
- RabbitMQ and Mosquitto
- Fluentd and Kibana 4 (Log analysis)
- GitLab Repo Server (for project teams sharing locally data)
- Hugo (static Web Page creator)

Some ipython modules are already running quite well with the Python2 Kernel (bokeh, vispy, SimpleSoap, GraphViz, mpld3...)

Scope:
Mainly for experimenting / learning / training. Should be useful as well to gather and analyze data from different sources.
Can be setup as a central ad-hoc project team entry point for developing rapid scripting solutions (just start and use).
Or can be used for learning programming with Python / Database / Messaging

Status:
Not everything is running smoothely, there is some more work needed:
- to get additional node modules for Node-Red up and running (e.g. MySQL)
- Some kernels are still not running correct (Go, iTorch)
- Some ipython modules might crash the kernel

Occasionally some more tools will be added, goal will be to have kind of WebGL for live updating charts up and running
