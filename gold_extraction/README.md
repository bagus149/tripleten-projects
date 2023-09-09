## Project Description:
Data is indexed by the date and time of acquisition (the date feature). Regarding time, parameters that are close together are generally similar. Some parameters are not available because their measurement and/or calculation are done long afterward. That's why some features present in the training set may not be in the test set. The test set also does not include the target variable. The source dataset includes both the training and test sets with all their features.

## Dataset:
Proses Teknologi:
- _Rougher feed_ - Raw material for the flotation process.
- _Rougher additions_ - Reagents for flotation: Xanthate, Sulphate, Depressant.
  - _Xanthate_ - flotation reagent or activator.
  - _Sulphate_ - sodium sulphide, specific to this process.
  - _Depressant_ - sodium silicate.
- _Rougher process_ - Flotation.
- _Rougher tails_ - Residue product.
- _Float banks_ - Flotation units.
- _Cleaner process_ - Purification.
- _Rougher Au_ - Rougher gold concentrate.
- _Final Au_ - Final gold concentrate.

Parameters from the available stages:
- _air amount_ - air volume.
- _fluid levels_
- _feed size_ - particle size of the feed.
- _feed rate_

# Libraries:
- _pandas_
- _matplotlib_
- _sklearn_
