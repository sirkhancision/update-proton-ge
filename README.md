[![Build status on GitLab CI][gitlab-ci-master-badge]][gitlab-ci-link]

[gitlab-ci-link]: https://gitlab.com/timvisee/update-proton-ge/pipelines
[gitlab-ci-master-badge]: https://gitlab.com/timvisee/update-proton-ge/badges/master/pipeline.svg

# Update Proton GloriousEggroll script (sirkhancision fork)
A script to update your [Proton GloriousEggroll][proton-ge] installation to the latest
version, so you don't have to do it yourself. Mixed with some extra functionalites found in [Termuellinator's fork of ProtonUpdater](https://github.com/Termuellinator/ProtonUpdater) + some extra teaks by your's truly.

## Usage
Please refer to the Proton GloriousEggroll installation instructions first to
make sure you meet all requirements:

https://github.com/GloriousEggroll/proton-ge-custom#installation

To use this script, download it first (and make it executable):

```bash
wget https://raw.githubusercontent.com/sirkhancision/update-proton-ge/master/update-proton-ge
chmod a+x ./update-proton-ge
```

Then run it to install the latest version of GloriousEggroll's Proton:

```bash
./update-proton-ge

$ Found latest version: 5.9-GE-8-ST
$ Do you want to try to download and (re)install this release? <y/n>
# it downloads the release with curl and extracts it with bsdtar
# etc...
```

## Dependencies

curl and bsdtar.

## License
This project is released under the MIT license.
Check out the [LICENSE](LICENSE) file for more information.

[proton-ge]: https://github.com/GloriousEggroll/proton-ge-custom
