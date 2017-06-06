# pbdr-cs

Docker configuration for the pbdR client/server. This includes the [pbdr-base](https://github.com/RBigData/pbdr-base) system.



# Setting Up the Container

Run:

```bash
sudo docker pull rbigdata/pbdr-cs
sudo docker run -i -t rbigdata/pbdr-cs
```

Alternatively, if you prefer/need to to work with the docker file directly:

1. Copy `Dockerfile` to your machine.
2. cd to the dir containing `Dockerfile`
3. `sudo docker build -t pbdr-cs .`
4. `sudo docker run -i -t pbdr-cs`



# Contact

If something goes wrong, please open an issue on the [github repository](https://github.com/RBigData/pbdr-cs).
