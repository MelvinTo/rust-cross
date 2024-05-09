FROM messense/rust-musl-cross:x86_64-musl
# fix a bug on folder, had to remove the toolchains
RUN rm -frv ~/.rustup/toolchains/*
RUN rustup update
RUN rustup toolchain install stable
RUN rustup target add --toolchain stable x86_64-unknown-linux-musl
RUN cargo
