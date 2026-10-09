# Developcu Homebrew Apps

Homebrew casks maintained by Developcu.

## Brighter

Native menu bar HDR brightness utility for a compatible built-in XDR display.

```sh
brew install --cask developcu/apps/brighter
```

Requires Apple silicon and macOS 14 or later. HDR boost requires a compatible built-in XDR display, such as Liquid Retina XDR on a 14-inch or 16-inch Apple silicon MacBook Pro. External displays and SDR-only displays are not supported.

The cask installs the Developer ID signed, notarized direct release from [developcu/brighter](https://github.com/developcu/brighter/releases). See the [source and documentation](https://github.com/developcu/brighter) and [support](https://brighter-support.pages.dev/).

## Update or uninstall

```sh
brew update
brew upgrade --cask developcu/apps/brighter
brew uninstall --cask developcu/apps/brighter
```

If a manually installed Brighter.app already exists in Applications, quit it and move it elsewhere before installing the cask.

## Maintenance

Casks/brighter.rb is mirrored from the application repository. For a new version, publish the verified notarized release, update version and checksum in both repositories, audit the cask and verify a real installation. Do not replace published release assets with different bytes at the same URL.
