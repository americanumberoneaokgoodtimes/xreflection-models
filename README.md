# XReflection model binaries

Release assets for the [XReflection Android app](https://github.com/americanumberoneaokgoodtimes/xreflection-android).
The app downloads these on demand and verifies size and SHA-256 before use.

| File | Size | SHA-256 |
|---|---|---|
| dsrnet_256_ctx_lnfused.bin | 166846464 | 0a068d440cdaa814644012f8b387afe1cff067889d026ff9affeef9432a90d3f |
| rdnet_256_ctx.bin | 392622080 | 20d66e4cdf20e90250c86b4918388fbf9f0f0b524eaa6ce4f1215dee72afaa87 |
| real_esrgan_x4plus_w8a8_ctx.bin | 21651456 | af86a8e430a59c0fdfab43ea5b78f8dfb98dcd4fc7c4aca197c7dac30a874806 |

These are QNN context binaries compiled for Snapdragon 8 Elite (SM8850, Hexagon v81) on Qualcomm AI Hub.
They only run on that hardware. Upstream terms: DSRNet / RDNet checkpoints (XReflection, Apache-2.0),
Real-ESRGAN (BSD-3-Clause). Compiled outputs are subject to Qualcomm AI Hub terms; DSRNet includes
ImageNet-derived VGG-19 features (research use). See THIRD_PARTY_NOTICES.md in the app repo.
