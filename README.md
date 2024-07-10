<div align="center">

<p align="center">
  <a href="https://www.edgee.cloud">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://cdn.edgee.cloud/img/favicon-dark.svg">
      <img src="https://cdn.edgee.cloud/img/favicon.svg" height="100" alt="Edgee">
    </picture>
    <h1 align="center">Edgee</h1>
  </a>
</p>


**The full-stack edge platform for your edge oriented applications.**

[![Edgee](https://img.shields.io/badge/edgee-open%20source-blueviolet.svg)](https://www.edgee.cloud)
[![Crates.io](https://img.shields.io/crates/v/edgee.svg?logo=rust)](https://crates.io/crates/edgee)
[![FlakeHub](https://img.shields.io/endpoint?url=https://flakehub.com/f/edgee-cloud/edgee/badge)](https://flakehub.com/flake/edgee-cloud/edgee)
[![Docker](https://img.shields.io/docker/v/edgeecloud/edgee.svg?logo=docker&label=docker&color=0db7ed)](https://hub.docker.com/r/edgeecloud/edgee)
[![Edgee](https://img.shields.io/badge/slack-edgee-blueviolet.svg?logo=slack)](https://www.edgee.cloud/slack)
[![Docs](https://img.shields.io/badge/docs-published-blue)](https://docs.edgee.cloud)

</div>

<!-- TODO: Add FAQ -->
<!-- TODO: Add Video introduction -->
## Documentation
- [Official Website](https://www.edgee.cloud)
- [Official Documentation](https://docs.edgee.cloud)

## Contact
- [Twitter](https://x.com/edgee_cloud)
- [Slack](https://www.edgee.cloud/slack)

# Usage as a flake

Add edgee to your `flake.nix`:

```nix
{
  inputs.edgee.url = "https://flakehub.com/f/edgee-cloud/edgee/*.tar.gz";

  outputs = { self, edgee }: {
    # Use in your outputs
  };
}

```

## Contributing
If you're interested in contributing to Edgee, read our [contribution guidelines](./CONTRIBUTING.md)

<!-- TODO: Add Roadmap section -->

## Reporting Security Vulnerabilities
If you've found a vulnerability or potential vulnerability in our code, please let us know at
[edgee-security](mailto:security@edgee.cloud).
