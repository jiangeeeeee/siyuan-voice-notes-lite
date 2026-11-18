# Third-party notices

## Distribution flavors (0.8.0)

Lite contains business JavaScript/CSS, documentation and the bundled noble cryptographic verifier. It does not contain or download offline speech models or inference runtimes.

Full additionally redistributes the existing sherpa-onnx/SenseVoiceSmall INT8/Silero VAD and speaker-analysis resources. Their notices are retained in `offline/licenses/`, including the separate **FunASR Model License 1.1**. Do not assume that every model is licensed under the source code's Apache license. The original model inventory is `offline/models.json`.

The second independent ASR is **Qwen3-ASR-0.6B**, revision `5eb144179a02acc5e5ba31e748d22b0cf3e303b0`, from <https://huggingface.co/Qwen/Qwen3-ASR-0.6B>. Its Apache-2.0 text is `offline/licenses/QWEN3-ASR-LICENSE.txt`; per-file provenance and hashes are in `offline/qwen-model/provenance.json`. The upstream inference implementation is <https://github.com/QwenLM/Qwen3-ASR>.

The Windows x64 Full runtime contains CPython 3.12.10, qwen-asr 0.0.6, CPU PyTorch 2.6.0 and pinned transitive packages. `offline/runtime-manifest.json` inventories every shipped file, package version and discovered license paths. The embedded Python LICENSE and package `.dist-info` license/NOTICE files remain in the runtime. This distribution retains upstream package contents rather than stripping their notices. `scripts/requirements-runtime.txt` records versions; the Full archive contains the actual runtime and does not require pip at installation time.

Public test recordings are taken from <https://huggingface.co/csukuangfj/sherpa-onnx-sense-voice-zh-en-ja-ko-yue-2024-07-17/tree/main/test_wavs>. They are not installed as user recordings or included in the release ZIP. QA screenshot/GIF content uses synthetic meeting notes and test audio.

Seven runtime packages omitted standalone license texts in their installed wheel metadata. Supplemental upstream texts, pinned source URLs and hashes are included under `offline/licenses/`: Cython, dynet38, ffmpy, gradio_client, qwen-omni-utils, soynlp and tokenizers. `runtime-supplement.json` identifies exact PyPI source archives; `runtime-upstream-licenses.json` identifies repository revisions. Some repository texts are from a pinned current revision rather than the package release tag; this distinction is recorded and must be reviewed before public distribution.

**soynlp 0.0.493 is LGPL-3.0.** Its unmodified Python library source remains separately importable in the runtime. The exact PyPI source archive, upstream copyright/LGPL notice and GPL-3.0 text are included under `offline/licenses/`. Users may inspect, modify and replace this library under its license. It is not statically incorporated into plugin JavaScript. The notices inventory does not assert that every transitive dependency uses a permissive license.

Model availability and this inventory are not a legal review of a future commercial redistribution. Preserve the included notices and review the applicable model terms before publication. No publication was performed in this round.

The activation verifier bundles @noble/curves 1.9.7 and its pinned @noble/hashes dependency. Existing offline-engine/model notices remain under offline/licenses/.


## @noble/curves

The MIT License (MIT)

Copyright (c) 2022 Paul Miller (https://paulmillr.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## @noble/hashes

The MIT License (MIT)

Copyright (c) 2022 Paul Miller (https://paulmillr.com)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## Mediabunny 1.66.0

Audio clip reading and writing uses the unmodified Mediabunny library, distributed under the Mozilla Public License 2.0. [Corresponding source](https://github.com/Vanilagy/mediabunny/tree/v1.66.0) · [License](https://www.mozilla.org/MPL/2.0/).
