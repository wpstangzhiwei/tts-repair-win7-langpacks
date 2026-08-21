# Win7 语音平台语言包

Microsoft Speech Platform TTS 语言包的离线 MSI 副本，供 [tts-repair](https://github.com/wpstangzhiwei/tts-repair) 使用。

## 项目说明

- MSI 文件来自官方 [Microsoft Speech Platform - Runtime Languages 11](https://www.microsoft.com/en-us/download/details.aspx?id=27224)，未做任何修改
- **仅包含 TTS（语音合成）**——不含 SR（语音识别）包，以控制仓库体积
- 本仓库是 `tts-repair` 的 **子模块**：

```text
platforms/windows/win7/resources/Microsoft Speech Platform/Langpacks
```

## 包含的语言包

| 语言 | 语音 | 文件 |
|---|---|---|
| ca-ES（加泰罗尼亚语） | Herena | `MSSpeech_TTS_ca-ES_Herena.msi` |
| da-DK（丹麦语） | Helle | `MSSpeech_TTS_da-DK_Helle.msi` |
| de-DE（德语） | Hedda | `MSSpeech_TTS_de-DE_Hedda.msi` |
| en-AU（英语·澳） | Hayley | `MSSpeech_TTS_en-AU_Hayley.msi` |
| en-CA（英语·加） | Heather | `MSSpeech_TTS_en-CA_Heather.msi` |
| en-GB（英语·英） | Hazel | `MSSpeech_TTS_en-GB_Hazel.msi` |
| en-IN（英语·印） | Heera | `MSSpeech_TTS_en-IN_Heera.msi` |
| en-US（英语·美） | Helen | `MSSpeech_TTS_en-US_Helen.msi` |
| en-US（英语·美） | ZiraPro | `MSSpeech_TTS_en-US_ZiraPro.msi` |
| es-ES（西班牙语） | Helena | `MSSpeech_TTS_es-ES_Helena.msi` |
| es-MX（西班牙语·墨） | Hilda | `MSSpeech_TTS_es-MX_Hilda.msi` |
| fi-FI（芬兰语） | Heidi | `MSSpeech_TTS_fi-FI_Heidi.msi` |
| fr-CA（法语·加） | Harmonie | `MSSpeech_TTS_fr-CA_Harmonie.msi` |
| fr-FR（法语·法） | Hortense | `MSSpeech_TTS_fr-FR_Hortense.msi` |
| it-IT（意大利语） | Lucia | `MSSpeech_TTS_it-IT_Lucia.msi` |
| ja-JP（日语） | Haruka | `MSSpeech_TTS_ja-JP_Haruka.msi` |
| ko-KR（韩语） | Heami | `MSSpeech_TTS_ko-KR_Heami.msi` |
| nb-NO（挪威语） | Hulda | `MSSpeech_TTS_nb-NO_Hulda.msi` |
| nl-NL（荷兰语） | Hanna | `MSSpeech_TTS_nl-NL_Hanna.msi` |
| pl-PL（波兰语） | Paulina | `MSSpeech_TTS_pl-PL_Paulina.msi` |
| pt-BR（葡萄牙语·巴） | Heloisa | `MSSpeech_TTS_pt-BR_Heloisa.msi` |
| pt-PT（葡萄牙语） | Helia | `MSSpeech_TTS_pt-PT_Helia.msi` |
| pt-PT（葡萄牙语） | Helia 16 kHz | `MSSpeech_TTS_pt-PT_Helia16k.msi` |
| ru-RU（俄语） | Elena | `MSSpeech_TTS_ru-RU_Elena.msi` |
| sv-SE（瑞典语） | Hedvig | `MSSpeech_TTS_sv-SE_Hedvig.msi` |
| zh-CN（简体中文） | HuiHui | `MSSpeech_TTS_zh-CN_HuiHui.msi` |
| zh-HK（繁体中文·港） | HunYee | `MSSpeech_TTS_zh-HK_HunYee.msi` |
| zh-TW（繁体中文·台） | HanHan | `MSSpeech_TTS_zh-TW_HanHan.msi` |

## 使用方法

克隆父仓库并初始化子模块：

```bat
git submodule update --init -- "platforms/windows/win7/resources/Microsoft Speech Platform/Langpacks"
```

或者由 `tts-repair.bat` 按需下载：脚本按「本地缓存 → 子模块 → 从本仓库按需下载」的顺序解析所需 MSI。

## 许可证

本仓库采用 [GPL-3.0-only](../../../LICENSE)。  
内置的 MSI 文件版权归 Microsoft 所有，受微软许可条款约束。
