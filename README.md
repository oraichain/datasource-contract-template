# {{ project-name }}

{% comment %}

```bash

# update rustup version >= 1.48.0
rustup update stable
rustup default stable-x86_64-unknown-linux-gnu

# needs cargo-generate --features vendored-openssl
cargo install --git https://github.com/cargo-generate/cargo-generate.git --features vendored-openssl

## generate the template
cargo generate --git https://github.com/oraichain/datasource-contract-template.git --name PROJECT_NAME
```

{% endcomment %}
