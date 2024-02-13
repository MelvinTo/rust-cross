FROM messense/rust-musl-cross:armv7-musleabihf
# fix a bug on folder, had to remove the toolchains
RUN rm -frv ~/.rustup/toolchains/*
RUN rustup update
RUN rustup toolchain install stable
RUN rustup target add --toolchain stable armv7-unknown-linux-musleabihf
RUN cargo
