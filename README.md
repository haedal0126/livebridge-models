# LiveBridge speech model downloads

Versioned mirrors of the unchanged speech recognition model files used by LiveBridge.
This repository distributes model files and their notices. The application source and server translation models are not included.

## Download

[Speech models release](https://github.com/haedal0126/livebridge-models/releases/tag/speech-models-20261024)

Download only the model needed for your recognition language; all16 files are not required for one installation.
SenseVoiceSmall INT8 is shared by English, Chinese, Korean and Japanese in LiveBridge. Other supported input languages use the corresponding Vosk archive.
The model bytes are identical to their original versions; changing the download source does not change recognition quality.

## Integrity and source attribution

The release includes `model-manifest.json`, `SHA256SUMS.txt`, full license texts and original/conversion author notices.
The manifest records the original source URL, exact byte count and SHA-256 of every model.
Vosk SHA-256 values are observed checksums from official HTTPS downloads, not upstream signatures.
Keep the supplied license and notice files when redistributing these assets.

| Model | Download size | License |
| --- | ---: | --- |
| SenseVoiceSmall; sherpa-onnx-sense-voice-zh-en-ja-ko-yue-2024-07-17 | 239.2MB | FunASR Model Open Source License Agreement 1.1 |
| vosk-model-small-es-0.42 | 39.8MB | Apache-2.0 |
| vosk-model-small-fr-0.22 | 42.2MB | Apache-2.0 |
| vosk-model-small-de-0.15 | 46.5MB | Apache-2.0 |
| vosk-model-small-ru-0.22 | 46.2MB | Apache-2.0 |
| vosk-model-small-vn-0.4 | 33.7MB | Apache-2.0 |
| vosk-model-small-pt-0.3 | 32.5MB | Apache-2.0 |
| vosk-model-small-it-0.22 | 49.7MB | Apache-2.0 |
| vosk-model-small-nl-0.22 | 40.4MB | Apache-2.0 |
| vosk-model-small-tr-0.3 | 36.9MB | Apache-2.0 |
| vosk-model-small-hi-0.22 | 44.5MB | Apache-2.0 |
| vosk-model-small-pl-0.22 | 53.0MB | Apache-2.0 |
| vosk-model-small-cs-0.4-rhasspy | 46.1MB | MIT |
| vosk-model-small-uk-v3-nano | 77.6MB | Apache-2.0 |
| vosk-model-small-fa-0.42 | 53.4MB | Apache-2.0 |
| vosk-model-small-gu-0.42 | 108.1MB | Apache-2.0 |

## Download reliability

Public release assets can be downloaded without a GitHub account. Regional speed and availability vary.
Applications should verify model hashes, support interrupted-download recovery, and retain the original upstream source as a fallback.
Existing app versions keep their configured download URLs until an app update adds this mirror.

## Licenses

- SenseVoiceSmall: FunASR Model Open Source License Agreement1.1. Original model: FunAudioLLM / Alibaba Group. ONNX conversion: Fangjun Kuang / k2-fsa sherpa-onnx.
- Vosk models: Apache-2.0, except Czech Rhasspy (MIT, Copyright(c)2020 Michael Hansen).
- Original copyright, model names, license terms and authorship are retained. LiveBridge does not claim authorship of these models.
