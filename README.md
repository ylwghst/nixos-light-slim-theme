# nixos-light-slim-theme
Clean and nice NixOS flavoured SLiM theme.

![preview](https://github.com/ylwghst/nixos-light-slim-theme/raw/master/preview.png)

# Use it
To use SLiM with NixOS light theme add this into configuration then rebuild.

```
services.xserver.displayManager.slim = {
   enable = true;
   theme = pkgs.fetchurl {
      url    = "https://github.com/ylwghst/nixos-light-slim-theme/archive/1.0.0.tar.gz";
      sha256 = "0cc701k920zhy54srd1qwb5rcxqp5adjhnl154z7c0276csglzw9";
    };
 };
 ```
