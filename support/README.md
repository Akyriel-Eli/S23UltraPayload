# Support feed schema

`targets-v3.json` maintains entries for shared exploit and KernelSU payloads for the Samsung Galaxy S23 Ultra (`SM-S918B`).

Automatic selection matches the exact device model (`SM-S918B`) and kernel version (`5.15.189`).

Each entry contains:
- `payloadId` and `displayName`
- `models`: `["SM-S918B"]`
- `kernelVersions`: `["5.15.189"]`
- `buildDisplays`, `fingerprints`, `kernelReleases`, and `kernelVersionInfos`
- `flavor`: `kernelsu` or `kernelsu-next`
- `requiresFreshP0Session`: `true`
- `exploit` and `kernelsu` download specifications with size and SHA256 checksums
