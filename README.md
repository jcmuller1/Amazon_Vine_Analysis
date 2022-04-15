# Amazon Vine Analysis

## Overview

The purpose of this analysis was to determine whether product reviews from the Amazon Vine program are positively biased compared to unpaid reviews. This was accomplished by performing an ETL using PySpark and analyzing the resulting data using Pandas.

## Results

![image1](results.PNG)

- 90 Vine reviews
    - 44 (48.88%) 5* Vine reviews
- 37,385 non-Vine reviews
    - 14,626 (39.12%) 5* non-Vine reviews

## Summary

From this limited analysis, it appears as though there is a slight positive bias in reviews that come from the Vine program. However, the sample sizes of the Vine and non-Vine reviews are multiple orders of magnitude different, so this may not be a fair comparison. An additional analysis that could test the veracity of the 5* reviews would be to break this analysis down by individual product. If Vine reviews are consistently more positive than non-Vine reviews on a product-by-product basis, it would serve as further evidence that Vine reviews are positively biased.
