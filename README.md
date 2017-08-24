# What is this?

This is a job to be run on a server which runs nvidia-smi, reads the
output and re-exports it via prometheus.

This allows you to keep track of your GPU usage.

# Building

```
cabal build
```

# If you want to test it out inside Docker container, follow the below steps:

```
$nvidia-docker pull ajeetraina/nvidia-exporter
```

# Development

Need: hpack to generate the cabal file from package.yaml
