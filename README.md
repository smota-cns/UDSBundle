# UDSBundle

A starter UDS Bundle that includes the air gap deployment of [K3s](https://k3s.io/) and [Big Bang](https://github.com/defenseunicorns/uds-package-dubbd).

## Quick Start

1. Install [UDS CLI]() in target infrastructure
2. Deploy UDS Bundle

   Option 1 (with internet connection)

   ```
   **RUN AS ROOT**
   uds deploy oci://ghcr.io/smota-cns/packages/atoms:0.0.1-amd64
   ```

   Option 2 (partial internet connection)

   ```
   uds pull oci://ghcr.io/smota-cns/packages/atoms:0.0.1-amd64 # Requires internet connection
   **RUN AS ROOT**
   uds deploy uds-bundle-atoms-amd64-0.0.1.tar.zst # No internet connection required
   ```
