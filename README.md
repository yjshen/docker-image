
# Dockerfile home

Update and release rust-base:

```shell

docker build -t rust-base:0.2.0 -f rust.dockerfile .
docker tag rust-base:0.2.0 yijieshen/rust-base:0.2.0
docker push yijieshen/rust-base:0.2.0

```

Update and release hdfs

```shell
docker build -t hdfs26:0.2.0 -f hdfs.dockerfile .
docker tag hdfs26:0.2.0 yijieshen/hdfs26:0.2.0
docker push yijieshen/hdfs26:0.2.0
```

> Use --progress=plain in docker build for detailed, non scrolled docker output