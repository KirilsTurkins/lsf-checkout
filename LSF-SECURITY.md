# LSF maintained action security fork

Based on actions/checkout v7.0.1 at 3d3c42e5aac5ba805825da76410c181273ba90b1.

The runtime dependency graph is pinned to patched package versions and the action bundles are rebuilt from that lock. The public npm registry is used for mirrored development tarballs with their original integrity retained.

Validation: Node 24.19.0 on Linux, locked installation, upstream build and the available upstream unit-test suite. Runtime OSV scan: zero findings in 24 packages. Exact bundle hashes and dependency selections are recorded in LSF-SECURITY.json.

This work was discovered while hardening CI for [Latent Service Fabric (LSF)](https://github.com/KirilsTurkins/latent-service-fabric) and is being contributed upstream. Upstream licenses and source history are retained.
