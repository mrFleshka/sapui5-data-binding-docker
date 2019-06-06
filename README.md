# Info

SAPUI5 Data Binding practice (For SAPUI5 version: 1.65.1).

[Documentation](https://sapui5.hana.ondemand.com/#/topic/e5310932a71f42daa41f3a6143efca9c)

Used with docker (nginx proxy-pass + node server).
 
# Run

For start add network in docker (used for custom windows network with routing to virtual machine):

```bash
docker network add develope
```

Then just start docker:

```bash
docker-compose up
```

Demo site available at [data-binding.sapui5.test](http://data-binding.sapui5.test/index.html)