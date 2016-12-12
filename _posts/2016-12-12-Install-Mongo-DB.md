Follow [this tutorial](https://docs.mongodb.com/v3.2/tutorial/install-mongodb-on-ubuntu/).

If an error occurs regarding /dada/db when running `mongod`, then do:
```
sudo mkdir -p /data/db;
sudo chown -R $USER:$USER /data/db;
```

Then run the service:
```
sudo service mongod start
```

That's all :)
