## How to use

```
# go to root folder of the rust project and run this
docker run --platform linux/arm -v ~/.docker_cargo_registry:/root/.cargo/registry -v $(pwd):/home/rust/src ghcr.io/melvinto/rust-cross:arm cargo build --release
```
