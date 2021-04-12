# Montreal-Forced-Aligner

https://montreal-forced-aligner.readthedocs.io/en/latest/index.html

## Download

https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner/releases/tag/v1.0.1

```bash
tar -zxvf montreal-forced-aligner_linux.tar.gz
```

rename `./montreal-forced-aligner/lib/libpython3.6m.so.1.0` to `libpython3.6m.so`.

## Usage

```bash
./montreal-forced-aligner/bin/mfa_align   corpus_dir   dict_path   acoustic_model   output_dir
```

acoustic_model: https://montreal-forced-aligner.readthedocs.io/en/latest/pretrained_models.html

#### English

```bash
./montreal-forced-aligner/bin/mfa_align ./LJSpeech ./lexicon/librispeech-lexicon.txt english ./textgrid
```

#### Mandarin

```bash
 ./montreal-forced-aligner/bin/mfa_align ./AISHELL3 ./lexicon/pinyin-lexicon.txt mandarin.zip ./textgrid
```