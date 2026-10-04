# sysfiles
My Linux system files, manageable with GNU Stow:

```sh
./rootstow */  # stow all packages
./rootstow nvidia arch-linux  # stow specific packages
```

`rootstow` is just a convenience for running `sudo stow --target=/
--no-folding $@`

