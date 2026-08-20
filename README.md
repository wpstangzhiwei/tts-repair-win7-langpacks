# Win7 Speech Platform language packs

Offline MSI copies for [tts-repair](https://github.com/wpstangzhiwei/tts-repair).

Source: [Microsoft Speech Platform - Runtime Languages 11](https://www.microsoft.com/en-us/download/details.aspx?id=27224)

This repository is a **submodule** of `tts-repair`:

```text
platforms/windows/win7/resources/Microsoft Speech Platform/langpacks
```

Clone the parent, then install. `tts-repair.bat` downloads only the MSI for the language you ask for.

To get every pack locally:

```bat
git submodule update --init -- platforms/windows/win7/resources/Microsoft Speech Platform/langpacks
```
