# Win7 Speech Platform Language Packs

Offline MSI copies of Microsoft Speech Platform TTS language packs, for use by [tts-repair](https://github.com/wpstangzhiwei/tts-repair).

## What Is This

- Unmodified MSI files from [Microsoft Speech Platform - Runtime Languages 11](https://www.microsoft.com/en-us/download/details.aspx?id=27224)
- **TTS voices only** — SR (speech recognition) packs are not included, to keep the repository small
- Serves as the **submodule** of `tts-repair`:

```text
platforms/windows/win7/resources/Microsoft Speech Platform/Langpacks
```

## Included Packs

| Locale | Voice | File |
|---|---|---|
| ca-ES | Herena | `MSSpeech_TTS_ca-ES_Herena.msi` |
| da-DK | Helle | `MSSpeech_TTS_da-DK_Helle.msi` |
| de-DE | Hedda | `MSSpeech_TTS_de-DE_Hedda.msi` |
| en-AU | Hayley | `MSSpeech_TTS_en-AU_Hayley.msi` |
| en-CA | Heather | `MSSpeech_TTS_en-CA_Heather.msi` |
| en-GB | Hazel | `MSSpeech_TTS_en-GB_Hazel.msi` |
| en-IN | Heera | `MSSpeech_TTS_en-IN_Heera.msi` |
| en-US | Helen | `MSSpeech_TTS_en-US_Helen.msi` |
| en-US | ZiraPro | `MSSpeech_TTS_en-US_ZiraPro.msi` |
| es-ES | Helena | `MSSpeech_TTS_es-ES_Helena.msi` |
| es-MX | Hilda | `MSSpeech_TTS_es-MX_Hilda.msi` |
| fi-FI | Heidi | `MSSpeech_TTS_fi-FI_Heidi.msi` |
| fr-CA | Harmonie | `MSSpeech_TTS_fr-CA_Harmonie.msi` |
| fr-FR | Hortense | `MSSpeech_TTS_fr-FR_Hortense.msi` |
| it-IT | Lucia | `MSSpeech_TTS_it-IT_Lucia.msi` |
| ja-JP | Haruka | `MSSpeech_TTS_ja-JP_Haruka.msi` |
| ko-KR | Heami | `MSSpeech_TTS_ko-KR_Heami.msi` |
| nb-NO | Hulda | `MSSpeech_TTS_nb-NO_Hulda.msi` |
| nl-NL | Hanna | `MSSpeech_TTS_nl-NL_Hanna.msi` |
| pl-PL | Paulina | `MSSpeech_TTS_pl-PL_Paulina.msi` |
| pt-BR | Heloisa | `MSSpeech_TTS_pt-BR_Heloisa.msi` |
| pt-PT | Helia | `MSSpeech_TTS_pt-PT_Helia.msi` |
| pt-PT | Helia 16 kHz | `MSSpeech_TTS_pt-PT_Helia16k.msi` |
| ru-RU | Elena | `MSSpeech_TTS_ru-RU_Elena.msi` |
| sv-SE | Hedvig | `MSSpeech_TTS_sv-SE_Hedvig.msi` |
| zh-CN | HuiHui | `MSSpeech_TTS_zh-CN_HuiHui.msi` |
| zh-HK | HunYee | `MSSpeech_TTS_zh-HK_HunYee.msi` |
| zh-TW | HanHan | `MSSpeech_TTS_zh-TW_HanHan.msi` |

## Usage

Clone the parent repo and init the submodule:

```bat
git submodule update --init -- "platforms/windows/win7/resources/Microsoft Speech Platform/Langpacks"
```

Or let `tts-repair.bat` download only the MSI for the language you ask for — it resolves from local cache → submodule → on-demand download from this repository.

## License

[GPL-3.0-only](../../../LICENSE) for this repository. The bundled MSI files remain copyrighted by Microsoft and are subject to Microsoft's license terms.
