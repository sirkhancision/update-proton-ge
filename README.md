[![Build status on GitLab CI][gitlab-ci-master-badge]][gitlab-ci-link]

[gitlab-ci-link]: https://gitlab.com/timvisee/update-proton-ge/pipelines

[gitlab-ci-master-badge]: https://gitlab.com/timvisee/update-proton-ge/badges/master/pipeline.svg

# Update Proton GloriousEggroll script (sirkhancision fork)

A script to update your [Proton GloriousEggroll][proton-ge] installation to the latest
version, so you don't have to do it yourself. Mixed with some extra functionalites found in [Termuellinator's fork of ProtonUpdater](https://github.com/Termuellinator/ProtonUpdater) + some extra teaks by your's truly.

## Usage

Please refer to the Proton GloriousEggroll installation instructions first to
make sure you meet all requirements:

<https://github.com/GloriousEggroll/proton-ge-custom#installation>

To use this script, download it first (and make it executable):

```bash
wget https://raw.githubusercontent.com/sirkhancision/update-proton-ge/master/update-proton-ge
chmod a+x ./update-proton-ge
```

Then run it to install the latest version of GloriousEggroll's Proton:

```bash
./update-proton-ge

$ Found latest version: 6.10-GE-1
$ Do you want to try to download and (re)install this release? <y/n> y
$   % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
$                                  Dload  Upload   Total   Spent    Left  Speed
$ 100   631  100   631    0     0   1091      0 --:--:-- --:--:-- --:--:--  1089
$ 100  370M  100  370M    0     0  2246k      0  0:02:48  0:02:48 --:--:-- 2288k
$ Do you want to delete intalled versions? <y/n> y
$ Installed runners:
$ 1. Proton-6.10-GE-1
$ 2. Proton-6.9-GE-2
$
$ Please choose an option to remove [1-2]:2
$ removing $HOME/.steam/steam/compatibilitytools.d/Proton-6.9-GE-2/
$ Do you really want to permanently delete this version? <y/n> y
$ Removed $HOME/.steam/steam/compatibilitytools.d/Proton-6.9-GE-2/
$ Installation complete, at: $HOME/.steam/steam/compatibilitytools.d/Proton-6.10-GE-1
```

## Dependencies

curl and bsdtar.

## License

This project is released under the MIT license.
Check out the [LICENSE](LICENSE) file for more information.

[proton-ge]: https://github.com/GloriousEggroll/proton-ge-custom
