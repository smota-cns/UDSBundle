# UDSBundle

A starter UDS Bundle that includes the air gap deployment of [K3s](https://k3s.io/) and [Big Bang](https://github.com/defenseunicorns/uds-package-dubbd).

## Quick Start

1. Install [UDS CLI]() in target infrastructure
2. Deploy UDS Bundle

   Option 1 (with internet connection)

   ```
   **RUN AS ROOT**
   uds deploy oci://,,,
   ```

   Option 2 (partial internet connection)

   ```
   uds pull oci://... # Requires internet connection
   **RUN AS ROOT**
   uds deploy ...tar.gz # No internet connection required
   ```
