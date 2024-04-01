# Kdenlive

See: <https://flathub.org/apps/org.kde.kdenlive>

## Support for older NVIDIA GPUs

Support for older NVIDIA GPUs has been removed with
[PR#253](https://github.com/flathub/org.kde.kdenlive/pull/352) (see also
[PR#259](https://github.com/flathub/org.kde.kdenlive/pull/259)).

We have kept support for those older GPUs in the Beta branch.

```
$ flatpak remote-add --if-not-exists flathub-beta https://flathub.org/beta-repo/flathub-beta.flatpakrepo
$ flatpak install flathub-beta org.kde.kdenlive
```

Note that this branch will likely not get any further updates.
