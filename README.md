# Win7 Speech Platform Language Packs

Offline MSI copies of Microsoft Speech Platform TTS language packs, for [tts-repair](https://github.com/wpstangzhiwei/tts-repair). Documentation in [English](docs/i18n/en-US/README.md) | [简体中文](docs/i18n/zh-CN/README.md).

[GPL-3.0-only](LICENSE)

## What Is This

- Unmodified MSI files from [Microsoft Speech Platform - Runtime Languages 11](https://www.microsoft.com/en-us/download/details.aspx?id=27224)
- **TTS voices only** — SR (speech recognition) packs are not included, to keep the repository small
- Serves as the **submodule** of `tts-repair`:

```text
platforms/windows/win7/resources/Microsoft Speech Platform/Langpacks
```

## Usage

Clone the parent repo and init the submodule:

```bat
git submodule update --init -- "platforms/windows/win7/resources/Microsoft Speech Platform/Langpacks"
```

Or let `tts-repair.bat` download only the MSI for the language you ask for.

## License

[GPL-3.0-only](LICENSE) for this repository. The bundled MSI files remain copyrighted by Microsoft and are subject to Microsoft's license terms.
