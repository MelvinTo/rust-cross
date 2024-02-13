build:
	docker build --platform linux/arm/v7 -t rust-cross:arm .

publish:
	docker tag rust-cross:arm ghcr.io/melvinto/rust-cross:arm
	docker push ghcr.io/melvinto/rust-cross:arm
