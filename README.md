# Linphone

## Install CI builds

1. Go to the [CI workflow](https://github.com/IuxtaPortam/org.linphone.linphone/actions/workflows/CI.yml).
2. Select the last (or any other specific run).
3. Under `Artifacts` find your architecture, `aarch64` or `x86_64`.
4. Click the download button next to it.


```
unzip *.flatpak.zip
flatpak  --user install --bundle  *.flatpak
```

## Using on GNOME desktop

For full functionality on GNOME desktop, like system tray integration and notifications support do the following.

1. Open either `Extension Manager` or `Extensions` app.
2. Under `User-Installed Extensions` activate the `AppIndicator and KStatusNotifierItem Support`.

