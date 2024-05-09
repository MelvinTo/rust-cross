build:
	docker build --platform linux/x86_64 -t rust-cross:amd64 .

publish:
	docker tag rust-cross:amd64 ghcr.io/melvinto/rust-cross:amd64
	docker push ghcr.io/melvinto/rust-cross:amd64
