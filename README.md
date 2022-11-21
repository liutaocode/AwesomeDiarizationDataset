# Awesome Speaker Diarization Dataset

In this repo, we conclude some speaker diarization dataset resource links, especially when data and labels are separated and not from the same place.

## Audio-only datasets

|  Dataset |Hours|Speakers| Overlap(%)  | Languages  |  Data |  Label  | Fees  |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|  CallHome \(LDC2001S97) |  17 | 2-6  |  16.52 |  English | [Data](https://catalog.ldc.upenn.edu/LDC2001S97)  |  [Splits](https://github.com/BUTSpeechFIT/VBx/tree/master/data/CALLHOME/lists) [Label](https://github.com/BUTSpeechFIT/VBx/tree/master/data/CALLHOME/rttms/all) | $500  |
|  DIHARD 2 |  46 | 2-14  | 44.4  |  Multi |  [Data](https://catalog.ldc.upenn.edu/LDC2022S06) |  [Label](https://catalog.ldc.upenn.edu/LDC2022S06) | $300  |
| VoxConverse  |  64 |  1-21 |  3.28 |  Multi |  [Data](https://github.com/joonson/voxconverse) |  [Label](https://github.com/joonson/voxconverse) |  Free |
| CSSD  |  180 |  2 |  0 | Chinese  | [Data](https://magichub.com/datasets/magicdata-ramc/)  |  [Label](https://github.com/MagicHub-io/MagicData-RAMC) | Free  |
| Simu-2spk  |  2434 |  2 |  34.14 | Multi  | ...  |  [Label](https://github.com/hitachi-speech/EEND) | $33,000  |

**Notes**:
* ``CallHome`` datasets have plenty of versions. Academia often calls ``LDC2001S97`` as CallHome for short.
* ``CallHome`` part1 and part2 are not officially spliting and the spliting can be found on [URL](https://github.com/BUTSpeechFIT/VBx/tree/master/data/CALLHOME/lists).
* ``VoxConverse`` does not release its visual part, so we temporarily consider ``VoxConverse`` an audio-only dataset.
* We can not find ``DIHARD3`` on the LDC website, so we do not analyze it here.
* ``Simu-2spk`` is a simulated telephone speech diarization dataset from Switchboard and SRE datasets, often trained in EEND. 
   Simulated data is expensive ($33,000) and consist of the following datasets.
> LDC98S75,LDC99S79,LDC2002S06,LDC2001S13,LDC2004S07,LDC2006S44,LDC2011S01,LDC2011S04,LDC2011S09,LDC2011S10,LDC2012S01,LDC2011S05, and LDC2011S08.

## Audio-visual datasets

|  Dataset |Hours|Speakers| Overlap(%)  | Languages  |  Data |  Label  | Fees  |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| AMI  |  100 | 3-5  | 13.37  |  English |  [Data](https://groups.inf.ed.ac.uk/ami/corpus/) |  [Label](https://github.com/BUTSpeechFIT/AMI-diarization-setup) |  Free |
|  AVA-AVD |  29 | 2-24  |  4.4 |  Multi | [Data](https://github.com/cvdfoundation/ava-dataset) | [Label](https://github.com/zcxu-eric/AVA-AVD)   |   Free|
|  MSDWild | 80  | 2-10  |  14.01 |  Multi | [Data](https://github.com/X-LANCE/MSDWILD)  | [Label](https://github.com/X-LANCE/MSDWILD)   | Free  |
|  MISP |  127 |  2-6 |  25.7 | Chinese  | [Data](https://mispchallenge.github.io/mispchallenge2022)  |  [Label](https://github.com/mispchallenge/misp2022_baseline/tree/main/track1_AVSD/scp_dir) | Free  |

**Notes**:
* MISP2022 are currently calculated on train set.
* Other datasets are calculated on all available sets, e,g. train, dev and test.

``Update:`` You can visualize those datasets via [URL](https://github.com/liutaocode/DiarizationVisualization).

If you find other usefull datasets, feel free to propose a `PR`.
