# rust-rocket-docker-sample

Sample rocket web app 

cargo run 

- build as binary

```
cargo build --dev 
or 
cargo build --release 
```

- deploy as container

```
docker build -t <repo/image> .

docker run -p8000:8000 -d <repo/image>
```