# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

In particular:

1. Any updates to pre-existing files shall entail a major version bump.
2. The inclusion of a new language, without changes to other pre-existing data, shall only entail a minor version bump.

It follows from the above that benchmark scores across different releases of FLORES+ with the same major version number are comparable.

## [2.0-alpha.2] – 2024-01-19

### Changed

- Updated `ckb_Arab` to replace usage of the non-standard `ك` character and improve the translation quality. Many thanks to @Sarchia for pointing out the issues with the original FLORES-200 data.

## [2.0-alpha.1] – 2023-12-14

### Changed

- Relabeled `zho_Hans` to `cmn_Hans` after confirming the data is in Standard Beijing Mandarin.
- Relabeled `zho_Hant` to `cmn_Hant` after confirming the data is in Taiwanese Mandarin.
- Relabeled `tgl_Latn` to `fil_Latn` after confirming the data is in Filipino.
- Relabeled `tzm_Tfng` to `zgh_Tfng` after additional quality assessment revealed the data was in Standard Moroccan Tamazight. Many thanks to @MedAymenF for pointing out the issues with the original FLORES-200 data.

## [2.0-alpha.0] – 2023-11-30

### Added

- Added `nqo_Nkoo` from <https://github.com/common-parallel-corpora/common-parallel-corpora>.
- Added the `dev` splits for `brx_Deva`, `dgo_Deva`, `mni_Mtei`, `snd_Deva`, `gom_Deva` from <https://github.com/ai4bharat/IndicTrans2>. The `devtest` splits are not yet available.

### Changed

- Updated `lij_Latn` after additional quality assessment. Data has undergone minor spelling and syntactic fixes.

## [1.0] - 2023-10-24

Initial release. This is the exact same data that was released under the name `FLORES-200` by [NLLB Team et al. (2022)](https://arxiv.org/abs/2207.04672). It can be downloaded from <https://tinyurl.com/flores200dataset>.