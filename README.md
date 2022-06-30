# Did Sov Reproduction

## Running

> Note: if you're on an ARM mac, run `docker build -t did-sov-prefix-demo -f Dockerfile.arm .` as the build step.

1. Git clone this repo
2. `docker build -t did-sov-prefix-demo .`
3. `docker run -it --rm -e LEGACY_DID_SOV_PREFIX=false did-sov-prefix-demo`
4. Scan the QR code and see whether a credential offer is received after creating the connection.

You can set `LEGACY_DID_SOV_PREFIX=false` to test it with the legacy did sov prefix
