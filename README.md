# Easy-Interpretable-Effective-openSMILE-for-voice-deepfake-detection
This repo contains information about the features used in the article "Easy, Interpretable, Effective: openSMILE for voice deepfake detection". 
The feature set is called "eGeMAPSv02" and it is included in the OpenSmile python library.

| Index | Feature Name                               |
|-------|-------------------------------------------|
| 0     | F0semitoneFrom27.5Hz_sma3nz_amean         |
| 1     | F0semitoneFrom27.5Hz_sma3nz_stddevNorm    |
| 2     | F0semitoneFrom27.5Hz_sma3nz_percentile20.0|
| 3     | F0semitoneFrom27.5Hz_sma3nz_percentile50.0|
| 4     | F0semitoneFrom27.5Hz_sma3nz_percentile80.0|
| 5     | F0semitoneFrom27.5Hz_sma3nz_pctlrange0-2  |
| 6     | F0semitoneFrom27.5Hz_sma3nz_meanRisingSlope|
| 7     | F0semitoneFrom27.5Hz_sma3nz_stddevRisingSlope|
| 8     | F0semitoneFrom27.5Hz_sma3nz_meanFallingSlope|
| 9     | F0semitoneFrom27.5Hz_sma3nz_stddevFallingSlope|
| 10    | loudness_sma3_amean                       |
| 11    | loudness_sma3_stddevNorm                  |
| 12    | loudness_sma3_percentile20.0             |
| 13    | loudness_sma3_percentile50.0             |
| 14    | loudness_sma3_percentile80.0             |
| 15    | loudness_sma3_pctlrange0-2               |
| 16    | loudness_sma3_meanRisingSlope            |
| 17    | loudness_sma3_stddevRisingSlope          |
| 18    | loudness_sma3_meanFallingSlope           |
| 19    | loudness_sma3_stddevFallingSlope         |
| 20    | spectralFlux_sma3_amean                  |
| 21    | spectralFlux_sma3_stddevNorm             |
| 22    | mfcc1_sma3_amean                         |
| 23    | mfcc1_sma3_stddevNorm                    |
| 24    | mfcc2_sma3_amean                         |
| 25    | mfcc2_sma3_stddevNorm                    |
| 26    | mfcc3_sma3_amean                         |
| 27    | mfcc3_sma3_stddevNorm                    |
| 28    | mfcc4_sma3_amean                         |
| 29    | mfcc4_sma3_stddevNorm                    |
| 30    | jitterLocal_sma3nz_amean                 |
| 31    | jitterLocal_sma3nz_stddevNorm            |
| 32    | shimmerLocaldB_sma3nz_amean              |
| 33    | shimmerLocaldB_sma3nz_stddevNorm         |
| 34    | HNRdBACF_sma3nz_amean                    |
| 35    | HNRdBACF_sma3nz_stddevNorm               |
| 36    | logRelF0-H1-H2_sma3nz_amean              |
| 37    | logRelF0-H1-H2_sma3nz_stddevNorm         |
| 38    | logRelF0-H1-A3_sma3nz_amean              |
| 39    | logRelF0-H1-A3_sma3nz_stddevNorm         |
| 40    | F1frequency_sma3nz_amean                 |
| 41    | F1frequency_sma3nz_stddevNorm            |
| 42    | F1bandwidth_sma3nz_amean                 |
| 43    | F1bandwidth_sma3nz_stddevNorm            |
| 44    | F1amplitudeLogRelF0_sma3nz_amean         |
| 45    | F1amplitudeLogRelF0_sma3nz_stddevNorm    |
| 46    | F2frequency_sma3nz_amean                 |
| 47    | F2frequency_sma3nz_stddevNorm            |
| 48    | F2bandwidth_sma3nz_amean                 |
| 49    | F2bandwidth_sma3nz_stddevNorm             |
| 50    | F2amplitudeLogRelF0_sma3nz_amean          |
| 51    | F2amplitudeLogRelF0_sma3nz_stddevNorm     |
| 52    | F3frequency_sma3nz_amean                  |
| 53    | F3frequency_sma3nz_stddevNorm             |
| 54    | F3bandwidth_sma3nz_amean                  |
| 55    | F3bandwidth_sma3nz_stddevNorm             |
| 56    | F3amplitudeLogRelF0_sma3nz_amean          |
| 57    | F3amplitudeLogRelF0_sma3nz_stddevNorm     |
| 58    | alphaRatioV_sma3nz_amean                  |
| 59    | alphaRatioV_sma3nz_stddevNorm             |
| 60    | hammarbergIndexV_sma3nz_amean             |
| 61    | hammarbergIndexV_sma3nz_stddevNorm        |
| 62    | slopeV0-500_sma3nz_amean                  |
| 63    | slopeV0-500_sma3nz_stddevNorm             |
| 64    | slopeV500-1500_sma3nz_amean               |
| 65    | slopeV500-1500_sma3nz_stddevNorm          |
| 66    | spectralFluxV_sma3nz_amean                |
| 67    | spectralFluxV_sma3nz_stddevNorm           |
| 68    | mfcc1V_sma3nz_amean                       |
| 69    | mfcc1V_sma3nz_stddevNorm                  |
| 70    | mfcc2V_sma3nz_amean                       |
| 71    | mfcc2V_sma3nz_stddevNorm                  |
| 72    | mfcc3V_sma3nz_amean                       |
| 73    | mfcc3V_sma3nz_stddevNorm                  |
| 74    | mfcc4V_sma3nz_amean                       |
| 75    | mfcc4V_sma3nz_stddevNorm                  |
| 76    | alphaRatioUV_sma3nz_amean                 |
| 77    | hammarbergIndexUV_sma3nz_amean            |
| 78    | slopeUV0-500_sma3nz_amean                 |
| 79    | slopeUV500-1500_sma3nz_amean              |
| 80    | spectralFluxUV_sma3nz_amean               |
| 81    | loudnessPeaksPerSec                       |
| 82    | VoicedSegmentsPerSec                      |
| 83    | MeanVoicedSegmentLengthSec                |
| 84    | StddevVoicedSegmentLengthSec              |
| 85    | MeanUnvoicedSegmentLength                 |
| 86    | StddevUnvoicedSegmentLength               |
| 87    | equivalentSoundLevel_dBp                  |

