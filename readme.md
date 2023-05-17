# NodeJS DuckDB for Amazon Linux 2

The npm packaged `duckdb` does not work on AL2 because AL2 is ancient and does not have an updated glibc. This repo is literally just a copy of the release files from https://github.com/tobilg/duckdb-nodejs-layer, and is used to help me npm install into AL2. 

The repo will be periodically updated with the latest release, feel free to use it, but it's intended to be used in my own projects only - I won't be providing support