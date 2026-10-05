## Fork provenance

This repository is a fork of [glennake/DirectFire_Converter](https://github.com/glennake/DirectFire_Converter). Original authorship belongs to the upstream project and its contributors; this repository does not claim first-party authorship of inherited work.

- **Local purpose:** Reference fork of the DirectFire firewall configuration conversion tool.
- **Local changes:** Before this notice, GitHub reported this fork as **identical to upstream**; this documentation notice is the local change introduced by this PR.
- **Sync model:** Snapshot/reference fork. Upstream synchronization is explicit and must not be assumed automatically.
- **License and attribution:** The inherited project is reported by GitHub as **GPL-3.0**. The existing license and attribution files remain authoritative.
- **Links and project claims:** Documentation, project status, support statements, and release/issue references below originate from the upstream project unless explicitly marked as local.

---

# DirectFire Converter

DirectFire Converter is a firewall configuration conversion tool written in Python.
Support for any firewall type will be considered based on request, demand and developer availability.

This tool generates configuration for supported elements only, that are typically input through CLI or "merged" with a full or running configuration. It does not generate full configuration files.

See the documentation for supported firewall types and details on what configuration elements are converted.

If you encounter problems when using this tool, please search open issues on GitHub and create a new issue if one does not exist.

WARNING: THIS TOOL IS IN VERY EARLY DEVELOPMENT AND MAY BE INACCURATE AND/OR UNRELIABLE, IT IS YOUR RESPONSIBILITY TO VALIDATE ALL CONFIGURATIONS BEFORE USE.

## Disclaimer

This tool will attempt to convert configurations from one firewall type to another by translating directly between the configuration syntax and format. There may be limitations, assumptions or errors made during this process. Any errors from the source configuration may be copied to the translated configuration. There are no guarantees of this tools accuracy, or the security effectiveness of any configuration output. Any translated configuration should be validated in full by the person or organisation responsible for any firewall on which it is applied, also accepting any and all liability for the use of this tool and its output. By using this tool, you agree to this disclaimer. If you provide any output from this tool to any other person or organisation, you must provide them with and they must agree to this disclaimer.

## Getting Started

https://github.com/glennake/DirectFire_Converter/wiki/Getting-Started

## Firewall Support

https://github.com/glennake/DirectFire_Converter/wiki/Firewall-Support

## Changelog

https://github.com/glennake/DirectFire_Converter/blob/master/CHANGELOG.md

## Full Documentation

https://github.com/glennake/DirectFire_Converter/wiki
