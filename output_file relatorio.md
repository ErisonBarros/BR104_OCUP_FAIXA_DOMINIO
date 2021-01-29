Toggle navigation

[Pandas Profiling Report](#top)

-   [Overview](#overview)
-   [Variables](#variables)
-   [Interactions](#interactions)
-   [Correlations](#correlations)
-   [Missing values](#missing)
-   [Sample](#sample)
-   [Duplicate rows](#duplicate)

Overview {.page-header}
========

-   [Overview](#overview-dataset_overview)
-   [Warnings 18](#overview-warnings)
-   [Reproduction](#overview-reproduction)

Dataset statistics

Number of variables

14

Number of observations

1237

Missing cells

0

Missing cells (%)

0.0%

Duplicate rows

1092

Duplicate rows (%)

88.3%

Total size in memory

135.4 KiB

Average record size in memory

112.1 B

Variable types

Categorical

2

Numeric

12

Warnings

Dataset has 1092 (88.3%) duplicate rows

Duplicates

[`IVS_2010`](#pp_var_2450130568744160628) is highly correlated with
`IVS_REN_10`

High correlation

[`IVS_REN_10`](#pp_var_-5735602607516626982) is highly correlated with
`IVS_2010`

High correlation

[`MASC`](#pp_var_-3948885775096133942) is highly correlated with `FEM`
and 2 other fields

High correlation

[`FEM`](#pp_var_-7506143049214754468) is highly correlated with `MASC`
and 2 other fields

High correlation

[`POP`](#pp_var_-7372829269756263552) is highly correlated with `MASC`
and 2 other fields

High correlation

[`DOM_OCU`](#pp_var_-7168620102553212536) is highly correlated with
`MASC` and 2 other fields

High correlation

[`area`](#pp_var_-8361136465124458213) is highly correlated with
`perimeter` and 1 other fields

High correlation

[`perimeter`](#pp_var_7984242158796509600) is highly correlated with
`area` and 1 other fields

High correlation

[`URB_RURAL`](#pp_var_2087948875789277904) is highly correlated with
`area` and 1 other fields

High correlation

[`Dens_Dom`](#pp_var_-7020207267621250373) is highly correlated with
`Dens_hab`

High correlation

[`Dens_hab`](#pp_var_1479436506857224264) is highly correlated with
`Dens_Dom`

High correlation

[`MASC`](#pp_var_-3948885775096133942) has 40 (3.2%) zeros

Zeros

[`FEM`](#pp_var_-7506143049214754468) has 44 (3.6%) zeros

Zeros

[`POP`](#pp_var_-7372829269756263552) has 40 (3.2%) zeros

Zeros

[`DOM_OCU`](#pp_var_-7168620102553212536) has 40 (3.2%) zeros

Zeros

[`Dens_Dom`](#pp_var_-7020207267621250373) has 440 (35.6%) zeros

Zeros

[`Dens_hab`](#pp_var_1479436506857224264) has 40 (3.2%) zeros

Zeros

Reproduction

Analysis started

2021-01-29 03:41:08.846244

Analysis finished

2021-01-29 03:41:34.302615

Duration

25.46 seconds

Software version

[pandas-profiling
v2.10.0](https://github.com/pandas-profiling/pandas-profiling)

Download configuration

[config.yaml](data:text/plain;charset=utf-8,plot%3A%0A%20%20%20%20histogram%3A%0A%20%20%20%20%20%20%20%20bins%3A%208%0A%20%20%20%20%20%20%20%20x_axis_labels%3A%20yes%0A%20%20%20%20%20%20%20%20max_bins%3A%20250%0A%20%20%20%20image_format%3A%20svg%0A%20%20%20%20dpi%3A%20800%0A%20%20%20%20scatter_threshold%3A%201000%0A%20%20%20%20correlation%3A%0A%20%20%20%20%20%20%20%20cmap%3A%20RdBu%0A%20%20%20%20%20%20%20%20bad%3A%20%27%23000000%27%0A%20%20%20%20missing%3A%0A%20%20%20%20%20%20%20%20cmap%3A%20RdBu%0A%20%20%20%20%20%20%20%20force_labels%3A%20yes%0A%20%20%20%20pie%3A%0A%20%20%20%20%20%20%20%20max_unique%3A%2010%0Atitle%3A%20Pandas%20Profiling%20Report%0Ahtml%3A%0A%20%20%20%20style%3A%0A%20%20%20%20%20%20%20%20full_width%3A%20yes%0A%20%20%20%20%20%20%20%20theme%3A%20None%0A%20%20%20%20%20%20%20%20logo%3A%20%27%27%0A%20%20%20%20%20%20%20%20primary_color%3A%20%27%23337ab7%27%0A%20%20%20%20minify_html%3A%20yes%0A%20%20%20%20use_local_assets%3A%20yes%0A%20%20%20%20inline%3A%20yes%0A%20%20%20%20navbar_show%3A%20yes%0A%20%20%20%20file_name%3A%20None%0Adataset%3A%0A%20%20%20%20description%3A%20%27%27%0A%20%20%20%20creator%3A%20%27%27%0A%20%20%20%20author%3A%20%27%27%0A%20%20%20%20copyright_holder%3A%20%27%27%0A%20%20%20%20copyright_year%3A%20%27%27%0A%20%20%20%20url%3A%20%27%27%0Avariables%3A%0A%20%20%20%20descriptions%3A%20%7B%7D%0Ashow_variable_description%3A%20yes%0Apool_size%3A%200%0Aprogress_bar%3A%20yes%0Avars%3A%0A%20%20%20%20num%3A%0A%20%20%20%20%20%20%20%20quantiles%3A%0A%20%20%20%20%20%20%20%20-%200.05%0A%20%20%20%20%20%20%20%20-%200.25%0A%20%20%20%20%20%20%20%20-%200.5%0A%20%20%20%20%20%20%20%20-%200.75%0A%20%20%20%20%20%20%20%20-%200.95%0A%20%20%20%20%20%20%20%20skewness_threshold%3A%2020%0A%20%20%20%20%20%20%20%20low_categorical_threshold%3A%205%0A%20%20%20%20%20%20%20%20chi_squared_threshold%3A%200.999%0A%20%20%20%20cat%3A%0A%20%20%20%20%20%20%20%20length%3A%20yes%0A%20%20%20%20%20%20%20%20characters%3A%20yes%0A%20%20%20%20%20%20%20%20words%3A%20yes%0A%20%20%20%20%20%20%20%20cardinality_threshold%3A%2050%0A%20%20%20%20%20%20%20%20n_obs%3A%205%0A%20%20%20%20%20%20%20%20chi_squared_threshold%3A%200.999%0A%20%20%20%20%20%20%20%20coerce_str_to_date%3A%20no%0A%20%20%20%20%20%20%20%20redact%3A%20no%0A%20%20%20%20bool%3A%0A%20%20%20%20%20%20%20%20n_obs%3A%203%0A%20%20%20%20%20%20%20%20mappings%3A%0A%20%20%20%20%20%20%20%20-%20%5Bt%2C%20f%5D%0A%20%20%20%20%20%20%20%20-%20%5B%27yes%27%2C%20%27no%27%5D%0A%20%20%20%20%20%20%20%20-%20%5By%2C%20n%5D%0A%20%20%20%20%20%20%20%20-%20%5B%27true%27%2C%20%27false%27%5D%0A%20%20%20%20file%3A%0A%20%20%20%20%20%20%20%20active%3A%20no%0A%20%20%20%20image%3A%0A%20%20%20%20%20%20%20%20active%3A%20no%0A%20%20%20%20%20%20%20%20exif%3A%20yes%0A%20%20%20%20%20%20%20%20hash%3A%20yes%0A%20%20%20%20path%3A%0A%20%20%20%20%20%20%20%20active%3A%20no%0A%20%20%20%20url%3A%0A%20%20%20%20%20%20%20%20active%3A%20no%0Asort%3A%20None%0Amissing_diagrams%3A%0A%20%20%20%20bar%3A%20yes%0A%20%20%20%20matrix%3A%20yes%0A%20%20%20%20heatmap%3A%20yes%0A%20%20%20%20dendrogram%3A%20yes%0Acorrelations%3A%0A%20%20%20%20pearson%3A%0A%20%20%20%20%20%20%20%20calculate%3A%20yes%0A%20%20%20%20%20%20%20%20warn_high_correlations%3A%20yes%0A%20%20%20%20%20%20%20%20threshold%3A%200.9%0A%20%20%20%20spearman%3A%0A%20%20%20%20%20%20%20%20calculate%3A%20yes%0A%20%20%20%20%20%20%20%20warn_high_correlations%3A%20no%0A%20%20%20%20%20%20%20%20threshold%3A%200.9%0A%20%20%20%20kendall%3A%0A%20%20%20%20%20%20%20%20calculate%3A%20yes%0A%20%20%20%20%20%20%20%20warn_high_correlations%3A%20no%0A%20%20%20%20%20%20%20%20threshold%3A%200.9%0A%20%20%20%20phi_k%3A%0A%20%20%20%20%20%20%20%20calculate%3A%20yes%0A%20%20%20%20%20%20%20%20warn_high_correlations%3A%20no%0A%20%20%20%20%20%20%20%20threshold%3A%200.9%0A%20%20%20%20cramers%3A%0A%20%20%20%20%20%20%20%20calculate%3A%20yes%0A%20%20%20%20%20%20%20%20warn_high_correlations%3A%20yes%0A%20%20%20%20%20%20%20%20threshold%3A%200.9%0Ainteractions%3A%0A%20%20%20%20targets%3A%20%5B%5D%0A%20%20%20%20continuous%3A%20yes%0Acategorical_maximum_correlation_distinct%3A%20100%0An_obs_unique%3A%205%0An_extreme_obs%3A%205%0An_freq_table_max%3A%2010%0Amemory_deep%3A%20no%0Aduplicates%3A%0A%20%20%20%20head%3A%2010%0Asamples%3A%0A%20%20%20%20head%3A%2010%0A%20%20%20%20tail%3A%2010%0A%20%20%20%20random%3A%200%0Areject_variables%3A%20yes%0Anotebook%3A%0A%20%20%20%20iframe%3A%0A%20%20%20%20%20%20%20%20height%3A%20800px%0A%20%20%20%20%20%20%20%20width%3A%20100%25%0A%20%20%20%20%20%20%20%20attribute%3A%20srcdoc%0A)

Variables {.page-header}
=========

[Ocup\_2010](#pp_var_-7653147865142812820)\
Categorical

Distinct

2

Distinct (%)

0.2%

Missing

0

Missing (%)

0.0%

Memory size

9.8 KiB

1

808 

0

429 

Toggle details

-   [Overview](#-7653147865142812820bottom--7653147865142812820overview)
-   [Categories](#-7653147865142812820bottom--7653147865142812820string)
-   [Words](#-7653147865142812820bottom--7653147865142812820word)
-   [Characters](#-7653147865142812820bottom--7653147865142812820characters)

Length

Max length

1

Median length

1

Mean length

1

Min length

1

Characters and Unicode

Total characters

1237

Distinct characters

2

Distinct categories

1
[?](https://en.wikipedia.org/wiki/Unicode_character_property#General_Category "Unicode categories (click for more information)")

Distinct scripts

1
[?](https://en.wikipedia.org/wiki/Script_(Unicode)#List_of_scripts_in_Unicode "Unicode scripts (click for more information)")

Distinct blocks

1
[?](https://en.wikipedia.org/wiki/Unicode_block "Unicode blocks (click for more information)")

The Unicode Standard assigns character properties to each code point,
which can be used to analyse textual variables.

Unique

Unique

0 ?

Unique (%)

0.0%

Sample

1st row

0

2nd row

0

3rd row

0

4th row

0

5th row

0

Value

Count

Frequency (%)

1

808

65.3%

0

429

34.7%

Histogram of lengths of the category

Value

Count

Frequency (%)

1

808

65.3%

0

429

34.7%

-   [Characters](#-7653147865142812820unicode--7653147865142812820characters)
-   [Categories](#-7653147865142812820unicode--7653147865142812820categories)
-   [Scripts](#-7653147865142812820unicode--7653147865142812820scripts)
-   [Blocks](#-7653147865142812820unicode--7653147865142812820blocks)

#### Most occurring characters

Value

Count

Frequency (%)

1

808

65.3%

0

429

34.7%

#### Most occurring categories

Value

Count

Frequency (%)

Decimal Number

1237

100.0%

#### Most frequent character per category

Value

Count

Frequency (%)

1

808

65.3%

0

429

34.7%

#### Most occurring scripts

Value

Count

Frequency (%)

Common

1237

100.0%

#### Most frequent character per script

Value

Count

Frequency (%)

1

808

65.3%

0

429

34.7%

#### Most occurring blocks

Value

Count

Frequency (%)

ASCII

1237

100.0%

#### Most frequent character per block

Value

Count

Frequency (%)

1

808

65.3%

0

429

34.7%

[IVS\_2010](#pp_var_2450130568744160628)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\

Distinct

7

Distinct (%)

0.6%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

0.3602247373

Minimum

0.31

Maximum

0.536

Zeros

0

Zeros (%)

0.0%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#2450130568744160628bottom-2450130568744160628statistics)
-   [Histogram](#2450130568744160628bottom-2450130568744160628histogram)
-   [Common
    values](#2450130568744160628bottom-2450130568744160628common_values)
-   [Extreme
    values](#2450130568744160628bottom-2450130568744160628extreme_values)

Quantile statistics

Minimum

0.31

5-th percentile

0.31

Q1

0.31

median

0.31

Q3

0.435

95-th percentile

0.484

Maximum

0.536

Range

0.226

Interquartile range (IQR)

0.125

Descriptive statistics

Standard deviation

0.0616858069

Coefficient of variation (CV)

0.171242562

Kurtosis

-0.5259216255

Mean

0.3602247373

Median Absolute Deviation (MAD)

0

Skewness

0.8709291587

Sum

445.598

Variance

0.003805138773

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=7)

Value

Count

Frequency (%)

0.31

646

52.2%

0.435

197

 

15.9%

0.362

182

 

14.7%

0.484

92

 

7.4%

0.385

85

 

6.9%

0.438

23

 

1.9%

0.536

12

 

1.0%

-   [Minimum 5
    values](#2450130568744160628extreme_values-2450130568744160628firstn)
-   [Maximum 5
    values](#2450130568744160628extreme_values-2450130568744160628lastn)

Value

Count

Frequency (%)

0.31

646

52.2%

0.362

182

 

14.7%

0.385

85

 

6.9%

0.435

197

 

15.9%

0.438

23

 

1.9%

Value

Count

Frequency (%)

0.536

12

 

1.0%

0.484

92

7.4%

0.438

23

 

1.9%

0.435

197

15.9%

0.385

85

6.9%

[IVS\_INF\_10](#pp_var_1445439645535022219)\
Real number (ℝ~≥0~)

Distinct

7

Distinct (%)

0.6%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

0.1465658852

Minimum

0.105

Maximum

0.381

Zeros

0

Zeros (%)

0.0%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#1445439645535022219bottom-1445439645535022219statistics)
-   [Histogram](#1445439645535022219bottom-1445439645535022219histogram)
-   [Common
    values](#1445439645535022219bottom-1445439645535022219common_values)
-   [Extreme
    values](#1445439645535022219bottom-1445439645535022219extreme_values)

Quantile statistics

Minimum

0.105

5-th percentile

0.105

Q1

0.105

median

0.105

Q3

0.209

95-th percentile

0.255

Maximum

0.381

Range

0.276

Interquartile range (IQR)

0.104

Descriptive statistics

Standard deviation

0.06033772187

Coefficient of variation (CV)

0.4116764401

Kurtosis

0.6008386036

Mean

0.1465658852

Median Absolute Deviation (MAD)

0

Skewness

1.185055336

Sum

181.302

Variance

0.00364064068

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=7)

Value

Count

Frequency (%)

0.105

646

52.2%

0.209

197

 

15.9%

0.112

182

 

14.7%

0.235

92

 

7.4%

0.255

85

 

6.9%

0.176

23

 

1.9%

0.381

12

 

1.0%

-   [Minimum 5
    values](#1445439645535022219extreme_values-1445439645535022219firstn)
-   [Maximum 5
    values](#1445439645535022219extreme_values-1445439645535022219lastn)

Value

Count

Frequency (%)

0.105

646

52.2%

0.112

182

 

14.7%

0.176

23

 

1.9%

0.209

197

 

15.9%

0.235

92

 

7.4%

Value

Count

Frequency (%)

0.381

12

 

1.0%

0.255

85

6.9%

0.235

92

7.4%

0.209

197

15.9%

0.176

23

 

1.9%

[IVS\_CPH\_10](#pp_var_-5677879621508223274)\
Real number (ℝ~≥0~)

Distinct

7

Distinct (%)

0.6%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

0.5170517381

Minimum

0.467

Maximum

0.603

Zeros

0

Zeros (%)

0.0%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-5677879621508223274bottom--5677879621508223274statistics)
-   [Histogram](#-5677879621508223274bottom--5677879621508223274histogram)
-   [Common
    values](#-5677879621508223274bottom--5677879621508223274common_values)
-   [Extreme
    values](#-5677879621508223274bottom--5677879621508223274extreme_values)

Quantile statistics

Minimum

0.467

5-th percentile

0.467

Q1

0.467

median

0.467

Q3

0.576

95-th percentile

0.595

Maximum

0.603

Range

0.136

Interquartile range (IQR)

0.109

Descriptive statistics

Standard deviation

0.05698853493

Coefficient of variation (CV)

0.1102182446

Kurtosis

-1.786892214

Mean

0.5170517381

Median Absolute Deviation (MAD)

0

Skewness

0.3636587349

Sum

639.593

Variance

0.003247693114

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=7)

Value

Count

Frequency (%)

0.467

646

52.2%

0.576

197

 

15.9%

0.595

182

 

14.7%

0.579

92

 

7.4%

0.495

85

 

6.9%

0.59

23

 

1.9%

0.603

12

 

1.0%

-   [Minimum 5
    values](#-5677879621508223274extreme_values--5677879621508223274firstn)
-   [Maximum 5
    values](#-5677879621508223274extreme_values--5677879621508223274lastn)

Value

Count

Frequency (%)

0.467

646

52.2%

0.495

85

 

6.9%

0.576

197

 

15.9%

0.579

92

 

7.4%

0.59

23

 

1.9%

Value

Count

Frequency (%)

0.603

12

 

1.0%

0.595

182

14.7%

0.59

23

 

1.9%

0.579

92

7.4%

0.576

197

15.9%

[IVS\_REN\_10](#pp_var_-5735602607516626982)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\

Distinct

7

Distinct (%)

0.6%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

0.4166693614

Minimum

0.357

Maximum

0.637

Zeros

0

Zeros (%)

0.0%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-5735602607516626982bottom--5735602607516626982statistics)
-   [Histogram](#-5735602607516626982bottom--5735602607516626982histogram)
-   [Common
    values](#-5735602607516626982bottom--5735602607516626982common_values)
-   [Extreme
    values](#-5735602607516626982bottom--5735602607516626982extreme_values)

Quantile statistics

Minimum

0.357

5-th percentile

0.357

Q1

0.357

median

0.357

Q3

0.521

95-th percentile

0.637

Maximum

0.637

Range

0.28

Interquartile range (IQR)

0.164

Descriptive statistics

Standard deviation

0.09032930481

Coefficient of variation (CV)

0.2167889295

Kurtosis

0.3817008174

Mean

0.4166693614

Median Absolute Deviation (MAD)

0

Skewness

1.339804865

Sum

515.42

Variance

0.008159383308

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=7)

Value

Count

Frequency (%)

0.357

646

52.2%

0.521

197

 

15.9%

0.379

182

 

14.7%

0.637

92

 

7.4%

0.406

85

 

6.9%

0.547

23

 

1.9%

0.624

12

 

1.0%

-   [Minimum 5
    values](#-5735602607516626982extreme_values--5735602607516626982firstn)
-   [Maximum 5
    values](#-5735602607516626982extreme_values--5735602607516626982lastn)

Value

Count

Frequency (%)

0.357

646

52.2%

0.379

182

 

14.7%

0.406

85

 

6.9%

0.521

197

 

15.9%

0.547

23

 

1.9%

Value

Count

Frequency (%)

0.637

92

7.4%

0.624

12

 

1.0%

0.547

23

 

1.9%

0.521

197

15.9%

0.406

85

6.9%

[MASC](#pp_var_-3948885775096133942)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\
`ZEROS`\

Distinct

89

Distinct (%)

7.2%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

158.3791431

Minimum

0

Maximum

950

Zeros

40

Zeros (%)

3.2%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-3948885775096133942bottom--3948885775096133942statistics)
-   [Histogram](#-3948885775096133942bottom--3948885775096133942histogram)
-   [Common
    values](#-3948885775096133942bottom--3948885775096133942common_values)
-   [Extreme
    values](#-3948885775096133942bottom--3948885775096133942extreme_values)

Quantile statistics

Minimum

0

5-th percentile

3

Q1

47

median

128

Q3

225

95-th percentile

329

Maximum

950

Range

950

Interquartile range (IQR)

178

Descriptive statistics

Standard deviation

162.7664735

Coefficient of variation (CV)

1.027701441

Kurtosis

11.40354589

Mean

158.3791431

Median Absolute Deviation (MAD)

87

Skewness

2.850508253

Sum

195915

Variance

26492.9249

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=8)

Value

Count

Frequency (%)

258

64

 

5.2%

138

61

 

4.9%

114

49

 

4.0%

0

40

 

3.2%

170

39

 

3.2%

207

35

 

2.8%

147

32

 

2.6%

128

31

 

2.5%

950

31

 

2.5%

283

31

 

2.5%

Other values (79)

824

66.6%

-   [Minimum 5
    values](#-3948885775096133942extreme_values--3948885775096133942firstn)
-   [Maximum 5
    values](#-3948885775096133942extreme_values--3948885775096133942lastn)

Value

Count

Frequency (%)

0

40

3.2%

1

4

 

0.3%

2

17

1.4%

3

21

1.7%

4

16

 

1.3%

Value

Count

Frequency (%)

950

31

2.5%

358

17

1.4%

338

12

 

1.0%

329

28

2.3%

328

22

1.8%

[FEM](#pp_var_-7506143049214754468)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\
`ZEROS`\

Distinct

91

Distinct (%)

7.4%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

178.8229588

Minimum

0

Maximum

985

Zeros

44

Zeros (%)

3.6%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-7506143049214754468bottom--7506143049214754468statistics)
-   [Histogram](#-7506143049214754468bottom--7506143049214754468histogram)
-   [Common
    values](#-7506143049214754468bottom--7506143049214754468common_values)
-   [Extreme
    values](#-7506143049214754468bottom--7506143049214754468extreme_values)

Quantile statistics

Minimum

0

5-th percentile

2

Q1

52

median

138

Q3

265

95-th percentile

396

Maximum

985

Range

985

Interquartile range (IQR)

213

Descriptive statistics

Standard deviation

175.0384106

Coefficient of variation (CV)

0.9788363404

Kurtosis

8.750252436

Mean

178.8229588

Median Absolute Deviation (MAD)

96

Skewness

2.432589893

Sum

221204

Variance

30638.44517

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=8)

Value

Count

Frequency (%)

296

64

 

5.2%

138

52

 

4.2%

0

44

 

3.6%

178

39

 

3.2%

182

38

 

3.1%

228

35

 

2.8%

170

32

 

2.6%

308

31

 

2.5%

140

31

 

2.5%

985

31

 

2.5%

Other values (81)

840

67.9%

-   [Minimum 5
    values](#-7506143049214754468extreme_values--7506143049214754468firstn)
-   [Maximum 5
    values](#-7506143049214754468extreme_values--7506143049214754468lastn)

Value

Count

Frequency (%)

0

44

3.6%

1

13

 

1.1%

2

6

 

0.5%

3

18

1.5%

4

14

 

1.1%

Value

Count

Frequency (%)

985

31

2.5%

400

12

 

1.0%

397

17

1.4%

396

27

2.2%

378

22

1.8%

[POP](#pp_var_-7372829269756263552)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\
`ZEROS`\

Distinct

100

Distinct (%)

8.1%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

337.2021019

Minimum

0

Maximum

1935

Zeros

40

Zeros (%)

3.2%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-7372829269756263552bottom--7372829269756263552statistics)
-   [Histogram](#-7372829269756263552bottom--7372829269756263552histogram)
-   [Common
    values](#-7372829269756263552bottom--7372829269756263552common_values)
-   [Extreme
    values](#-7372829269756263552bottom--7372829269756263552extreme_values)

Quantile statistics

Minimum

0

5-th percentile

5

Q1

99

median

260

Q3

495

95-th percentile

711

Maximum

1935

Range

1935

Interquartile range (IQR)

396

Descriptive statistics

Standard deviation

337.3408572

Coefficient of variation (CV)

1.00041149

Kurtosis

10.03673834

Mean

337.2021019

Median Absolute Deviation (MAD)

181

Skewness

2.636230117

Sum

417119

Variance

113798.8539

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=8)

Value

Count

Frequency (%)

554

64

 

5.2%

320

56

 

4.5%

215

49

 

4.0%

252

49

 

4.0%

0

40

 

3.2%

348

39

 

3.2%

435

35

 

2.8%

317

32

 

2.6%

591

31

 

2.5%

268

31

 

2.5%

Other values (90)

811

65.6%

-   [Minimum 5
    values](#-7372829269756263552extreme_values--7372829269756263552firstn)
-   [Maximum 5
    values](#-7372829269756263552extreme_values--7372829269756263552lastn)

Value

Count

Frequency (%)

0

40

3.2%

1

4

 

0.3%

3

13

 

1.1%

4

3

 

0.2%

5

4

 

0.3%

Value

Count

Frequency (%)

1935

31

2.5%

755

17

1.4%

738

12

 

1.0%

711

27

2.2%

706

22

1.8%

[DOM\_OCU](#pp_var_-7168620102553212536)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\
`ZEROS`\

Distinct

78

Distinct (%)

6.3%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

94.48827809

Minimum

0

Maximum

552

Zeros

40

Zeros (%)

3.2%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-7168620102553212536bottom--7168620102553212536statistics)
-   [Histogram](#-7168620102553212536bottom--7168620102553212536histogram)
-   [Common
    values](#-7168620102553212536bottom--7168620102553212536common_values)
-   [Extreme
    values](#-7168620102553212536bottom--7168620102553212536extreme_values)

Quantile statistics

Minimum

0

5-th percentile

1

Q1

26

median

75

Q3

137

95-th percentile

203

Maximum

552

Range

552

Interquartile range (IQR)

111

Descriptive statistics

Standard deviation

96.1753854

Coefficient of variation (CV)

1.017855202

Kurtosis

10.24206169

Mean

94.48827809

Median Absolute Deviation (MAD)

52

Skewness

2.668039073

Sum

116882

Variance

9249.704757

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=8)

Value

Count

Frequency (%)

168

64

 

5.2%

75

49

 

4.0%

0

40

 

3.2%

100

39

 

3.2%

1

38

 

3.1%

80

38

 

3.1%

87

37

 

3.0%

132

35

 

2.8%

145

31

 

2.5%

82

31

 

2.5%

Other values (68)

835

67.5%

-   [Minimum 5
    values](#-7168620102553212536extreme_values--7168620102553212536firstn)
-   [Maximum 5
    values](#-7168620102553212536extreme_values--7168620102553212536lastn)

Value

Count

Frequency (%)

0

40

3.2%

1

38

3.1%

2

20

1.6%

3

18

1.5%

4

12

 

1.0%

Value

Count

Frequency (%)

552

31

2.5%

204

17

1.4%

203

22

1.8%

200

27

2.2%

199

12

 

1.0%

[area](#pp_var_-8361136465124458213)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\

Distinct

144

Distinct (%)

11.6%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

270238.3907

Minimum

40071.84875

Maximum

1002134.316

Zeros

0

Zeros (%)

0.0%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-8361136465124458213bottom--8361136465124458213statistics)
-   [Histogram](#-8361136465124458213bottom--8361136465124458213histogram)
-   [Common
    values](#-8361136465124458213bottom--8361136465124458213common_values)
-   [Extreme
    values](#-8361136465124458213bottom--8361136465124458213extreme_values)

Quantile statistics

Minimum

40071.84875

5-th percentile

40072.15161

Q1

40074.81189

median

40075.04517

Q3

40085.81372

95-th percentile

1002092.473

Maximum

1002134.316

Range

962062.4677

Interquartile range (IQR)

11.00183105

Descriptive statistics

Standard deviation

410543.0688

Coefficient of variation (CV)

1.51918855

Kurtosis

-0.5035733545

Mean

270238.3907

Median Absolute Deviation (MAD)

2.879638672

Skewness

1.223618957

Sum

334284889.3

Variance

1.685456113 × 10^11^

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=8)

Value

Count

Frequency (%)

40080.54285

64

 

5.2%

40072.15161

49

 

4.0%

40080.68677

39

 

3.2%

40074.95715

38

 

3.1%

40075.01538

35

 

2.8%

40074.94751

32

 

2.6%

1001847.063

31

 

2.5%

40077.01318

31

 

2.5%

1001994.239

31

 

2.5%

40072.29919

30

 

2.4%

Other values (134)

857

69.3%

-   [Minimum 5
    values](#-8361136465124458213extreme_values--8361136465124458213firstn)
-   [Maximum 5
    values](#-8361136465124458213extreme_values--8361136465124458213lastn)

Value

Count

Frequency (%)

40071.84875

1

 

0.1%

40071.87329

2

 

0.2%

40072.00989

11

0.9%

40072.02722

1

 

0.1%

40072.03333

19

1.5%

Value

Count

Frequency (%)

1002134.316

9

 

0.7%

1002129.26

24

1.9%

1002119.52

2

 

0.2%

1002112.066

1

 

0.1%

1002110.929

1

 

0.1%

[perimeter](#pp_var_7984242158796509600)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\

Distinct

144

Distinct (%)

11.6%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

1567.361838

Minimum

800.7884176

Maximum

4004.584675

Zeros

0

Zeros (%)

0.0%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#7984242158796509600bottom-7984242158796509600statistics)
-   [Histogram](#7984242158796509600bottom-7984242158796509600histogram)
-   [Common
    values](#7984242158796509600bottom-7984242158796509600common_values)
-   [Extreme
    values](#7984242158796509600bottom-7984242158796509600extreme_values)

Quantile statistics

Minimum

800.7884176

5-th percentile

800.7913629

Q1

800.8158141

median

800.8182115

Q3

800.9215971

95-th percentile

4004.504431

Maximum

4004.584675

Range

3203.796258

Interquartile range (IQR)

0.1057829836

Descriptive statistics

Standard deviation

1367.274108

Coefficient of variation (CV)

0.8723410731

Kurtosis

-0.5035735213

Mean

1567.361838

Median Absolute Deviation (MAD)

0.02673125689

Skewness

1.223618914

Sum

1938826.594

Variance

1869438.486

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=8)

Value

Count

Frequency (%)

800.8697137

64

 

5.2%

800.7913629

49

 

4.0%

800.8711313

39

 

3.2%

800.8172217

38

 

3.1%

800.8179584

35

 

2.8%

800.8171713

32

 

2.6%

800.8423494

31

 

2.5%

4004.026548

31

 

2.5%

4004.314205

31

 

2.5%

800.7928178

30

 

2.4%

Other values (134)

857

69.3%

-   [Minimum 5
    values](#7984242158796509600extreme_values-7984242158796509600firstn)
-   [Maximum 5
    values](#7984242158796509600extreme_values-7984242158796509600lastn)

Value

Count

Frequency (%)

800.7884176

1

 

0.1%

800.7886419

2

 

0.2%

800.7899897

11

0.9%

800.7901192

1

 

0.1%

800.7902002

19

1.5%

Value

Count

Frequency (%)

4004.584675

9

 

0.7%

4004.576857

24

1.9%

4004.553936

2

 

0.2%

4004.542472

1

 

0.1%

4004.54077

1

 

0.1%

[URB\_RURAL](#pp_var_2087948875789277904)\
Categorical

`HIGH CORRELATION`\

Distinct

2

Distinct (%)

0.2%

Missing

0

Missing (%)

0.0%

Memory size

9.8 KiB

1

941 

0

296 

Toggle details

-   [Overview](#2087948875789277904bottom-2087948875789277904overview)
-   [Categories](#2087948875789277904bottom-2087948875789277904string)
-   [Words](#2087948875789277904bottom-2087948875789277904word)
-   [Characters](#2087948875789277904bottom-2087948875789277904characters)

Length

Max length

1

Median length

1

Mean length

1

Min length

1

Characters and Unicode

Total characters

1237

Distinct characters

2

Distinct categories

1
[?](https://en.wikipedia.org/wiki/Unicode_character_property#General_Category "Unicode categories (click for more information)")

Distinct scripts

1
[?](https://en.wikipedia.org/wiki/Script_(Unicode)#List_of_scripts_in_Unicode "Unicode scripts (click for more information)")

Distinct blocks

1
[?](https://en.wikipedia.org/wiki/Unicode_block "Unicode blocks (click for more information)")

The Unicode Standard assigns character properties to each code point,
which can be used to analyse textual variables.

Unique

Unique

0 ?

Unique (%)

0.0%

Sample

1st row

1

2nd row

1

3rd row

1

4th row

1

5th row

1

Value

Count

Frequency (%)

1

941

76.1%

0

296

 

23.9%

Histogram of lengths of the category

Value

Count

Frequency (%)

1

941

76.1%

0

296

 

23.9%

-   [Characters](#2087948875789277904unicode-2087948875789277904characters)
-   [Categories](#2087948875789277904unicode-2087948875789277904categories)
-   [Scripts](#2087948875789277904unicode-2087948875789277904scripts)
-   [Blocks](#2087948875789277904unicode-2087948875789277904blocks)

#### Most occurring characters

Value

Count

Frequency (%)

1

941

76.1%

0

296

 

23.9%

#### Most occurring categories

Value

Count

Frequency (%)

Decimal Number

1237

100.0%

#### Most frequent character per category

Value

Count

Frequency (%)

1

941

76.1%

0

296

 

23.9%

#### Most occurring scripts

Value

Count

Frequency (%)

Common

1237

100.0%

#### Most frequent character per script

Value

Count

Frequency (%)

1

941

76.1%

0

296

 

23.9%

#### Most occurring blocks

Value

Count

Frequency (%)

ASCII

1237

100.0%

#### Most frequent character per block

Value

Count

Frequency (%)

1

941

76.1%

0

296

 

23.9%

[Dens\_Dom](#pp_var_-7020207267621250373)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\
`ZEROS`\

Distinct

6

Distinct (%)

0.5%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

0.001728375101

Minimum

0

Maximum

0.005

Zeros

440

Zeros (%)

35.6%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#-7020207267621250373bottom--7020207267621250373statistics)
-   [Histogram](#-7020207267621250373bottom--7020207267621250373histogram)
-   [Common
    values](#-7020207267621250373bottom--7020207267621250373common_values)
-   [Extreme
    values](#-7020207267621250373bottom--7020207267621250373extreme_values)

Quantile statistics

Minimum

0

5-th percentile

0

Q1

0

median

0.002

Q3

0.003

95-th percentile

0.005

Maximum

0.005

Range

0.005

Interquartile range (IQR)

0.003

Descriptive statistics

Standard deviation

0.001662146143

Coefficient of variation (CV)

0.9616813746

Kurtosis

-0.8569973151

Mean

0.001728375101

Median Absolute Deviation (MAD)

0.002

Skewness

0.5684827957

Sum

2.138

Variance

2.762729801 × 10^6^

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=6)

Value

Count

Frequency (%)

0

440

35.6%

0.002

306

24.7%

0.001

146

 

11.8%

0.004

125

 

10.1%

0.003

110

 

8.9%

0.005

110

 

8.9%

-   [Minimum 5
    values](#-7020207267621250373extreme_values--7020207267621250373firstn)
-   [Maximum 5
    values](#-7020207267621250373extreme_values--7020207267621250373lastn)

Value

Count

Frequency (%)

0

440

35.6%

0.001

146

 

11.8%

0.002

306

24.7%

0.003

110

 

8.9%

0.004

125

 

10.1%

Value

Count

Frequency (%)

0.005

110

 

8.9%

0.004

125

10.1%

0.003

110

 

8.9%

0.002

306

24.7%

0.001

146

11.8%

[Dens\_hab](#pp_var_1479436506857224264)\
Real number (ℝ~≥0~)

`HIGH CORRELATION`\
`ZEROS`\

Distinct

124

Distinct (%)

10.0%

Missing

0

Missing (%)

0.0%

Infinite

0

Infinite (%)

0.0%

Mean

0.006086562618

Minimum

0

Maximum

0.01883971406

Zeros

40

Zeros (%)

3.2%

Memory size

9.8 KiB

Toggle details

-   [Statistics](#1479436506857224264bottom-1479436506857224264statistics)
-   [Histogram](#1479436506857224264bottom-1479436506857224264histogram)
-   [Common
    values](#1479436506857224264bottom-1479436506857224264common_values)
-   [Extreme
    values](#1479436506857224264bottom-1479436506857224264extreme_values)

Quantile statistics

Minimum

0

5-th percentile

2.195905554 × 10^5^

Q1

0.0005228866384

median

0.005365302324

Q3

0.009731768111

95-th percentile

0.01761695235

Maximum

0.01883971406

Range

0.01883971406

Interquartile range (IQR)

0.009208881473

Descriptive statistics

Standard deviation

0.005811442849

Coefficient of variation (CV)

0.9547988271

Kurtosis

-0.7230218254

Mean

0.006086562618

Median Absolute Deviation (MAD)

0.004842415686

Skewness

0.6823117744

Sum

7.529077958

Variance

3.377286798 × 10^5^

Monotocity

Not monotonic

**Histogram with fixed size bins** (bins=8)

Value

Count

Frequency (%)

0.01382216808

64

 

5.2%

0.006288656582

49

 

4.0%

0

40

 

3.2%

0.008682485957

39

 

3.2%

0.00798503661

38

 

3.1%

0.01085464337

35

 

2.8%

0.007910178795

32

 

2.6%

0.0005898237508

31

 

2.5%

0.001931432523

31

 

2.5%

0.00668712508

31

 

2.5%

Other values (114)

847

68.5%

-   [Minimum 5
    values](#1479436506857224264extreme_values-1479436506857224264firstn)
-   [Maximum 5
    values](#1479436506857224264extreme_values-1479436506857224264lastn)

Value

Count

Frequency (%)

0

40

3.2%

9.98118972 × 10^7^

2

 

0.2%

2.994613106 × 10^6^

3

 

0.2%

7.98480544 × 10^6^

1

 

0.1%

9.981296241 × 10^6^

4

 

0.3%

Value

Count

Frequency (%)

0.01883971406

17

1.4%

0.0184155705

12

1.0%

0.0177418051

27

2.2%

0.01761695235

22

1.8%

0.01759199515

28

2.3%

Interactions {.page-header}
============

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

IVS\_2010 IVS\_INF\_10 IVS\_CPH\_10 IVS\_REN\_10 MASC FEM POP DOM\_OCU
area perimeter Dens\_Dom Dens\_hab

Correlations {.page-header}
============

Toggle correlation descriptions

-   [Pearson's r](#correlations_tab-pearson)
-   [Spearman's ρ](#correlations_tab-spearman)
-   [Kendall's τ](#correlations_tab-kendall)
-   [Phik (φk)](#correlations_tab-phi_k)
-   [Cramér's V (φc)](#correlations_tab-cramers)

### Pearson's r

The Pearson's correlation coefficient (*r*) is a measure of linear
correlation between two variables. It's value lies between -1 and +1, -1
indicating total negative linear correlation, 0 indicating no linear
correlation and 1 indicating total positive linear correlation.
Furthermore, *r* is invariant under separate changes in location and
scale of the two variables, implying that for a linear function the
angle to the x-axis does not affect *r*.\
\
To calculate *r* for two variables *X* and *Y*, one divides the
covariance of *X* and *Y* by the product of their standard deviations.

### Spearman's ρ

The Spearman's rank correlation coefficient (*ρ*) is a measure of
monotonic correlation between two variables, and is therefore better in
catching nonlinear monotonic correlations than Pearson's *r*. It's value
lies between -1 and +1, -1 indicating total negative monotonic
correlation, 0 indicating no monotonic correlation and 1 indicating
total positive monotonic correlation.\
\
To calculate *ρ* for two variables *X* and *Y*, one divides the
covariance of the rank variables of *X* and *Y* by the product of their
standard deviations.

### Kendall's τ

Similarly to Spearman's rank correlation coefficient, the Kendall rank
correlation coefficient (*τ*) measures ordinal association between two
variables. It's value lies between -1 and +1, -1 indicating total
negative correlation, 0 indicating no correlation and 1 indicating total
positive correlation. \
\
To calculate *τ* for two variables *X* and *Y*, one determines the
number of concordant and discordant pairs of observations. *τ* is given
by the number of concordant pairs minus the discordant pairs divided by
the total number of pairs.

### Phik (φk)

Phik (φk) is a new and practical correlation coefficient that works
consistently between categorical, ordinal and interval variables,
captures non-linear dependency and reverts to the Pearson correlation
coefficient in case of a bivariate normal input distribution. There is
extensive documentation available
[here](https://phik.readthedocs.io/en/latest/index.html).

### Cramér's V (φc)

Cramér's V is an association measure for nominal random variables. The
coefficient ranges from 0 to 1, with 0 indicating independence and 1
indicating perfect association. The empirical estimators used for
Cramér's V have been proved to be biased, even for large samples. We use
a bias-corrected measure that has been proposed by Bergsma in 2013 that
can be found [here](http://stats.lse.ac.uk/bergsma/pdf/cramerV3.pdf).

Missing values {.page-header}
==============

-   [Count](#missing-bar)
-   [Matrix](#missing-matrix)

A simple visualization of nullity by column.

Nullity matrix is a data-dense display which lets you quickly visually
pick out patterns in data completion.

Sample {.page-header}
======

First rows {.indent}
----------

Ocup\_2010

IVS\_2010

IVS\_INF\_10

IVS\_CPH\_10

IVS\_REN\_10

MASC

FEM

POP

DOM\_OCU

area

perimeter

URB\_RURAL

Dens\_Dom

Dens\_hab

0

0

0.385

0.255

0.495

0.406

79

81

160

48

40085.928467

800.922815

1

0.001

0.003991

1

0

0.385

0.255

0.495

0.406

79

81

160

48

40085.928467

800.922815

1

0.001

0.003991

2

0

0.385

0.255

0.495

0.406

79

81

160

48

40085.928467

800.922815

1

0.001

0.003991

3

0

0.385

0.255

0.495

0.406

79

81

160

48

40085.928467

800.922815

1

0.001

0.003991

4

0

0.385

0.255

0.495

0.406

79

81

160

48

40085.928467

800.922815

1

0.001

0.003991

5

0

0.385

0.255

0.495

0.406

79

81

160

48

40085.928467

800.922815

1

0.001

0.003991

6

0

0.385

0.255

0.495

0.406

79

81

160

48

40085.928467

800.922815

1

0.001

0.003991

7

0

0.385

0.255

0.495

0.406

50

45

95

25

40085.940796

800.922917

1

0.001

0.002370

8

0

0.385

0.255

0.495

0.406

50

45

95

25

40085.940796

800.922917

1

0.001

0.002370

9

0

0.385

0.255

0.495

0.406

0

0

0

0

40085.788696

800.921393

1

0.000

0.000000

Last rows {.indent}
---------

Ocup\_2010

IVS\_2010

IVS\_INF\_10

IVS\_CPH\_10

IVS\_REN\_10

MASC

FEM

POP

DOM\_OCU

area

perimeter

URB\_RURAL

Dens\_Dom

Dens\_hab

1227

1

0.435

0.209

0.576

0.521

35

42

77

18

1.001806e+06

4003.963098

0

0.0

0.000077

1228

1

0.435

0.209

0.576

0.521

35

42

77

18

1.001806e+06

4003.963098

0

0.0

0.000077

1229

1

0.435

0.209

0.576

0.521

35

42

77

18

1.001806e+06

4003.963098

0

0.0

0.000077

1230

1

0.435

0.209

0.576

0.521

35

42

77

18

1.001806e+06

4003.963098

0

0.0

0.000077

1231

1

0.435

0.209

0.576

0.521

35

42

77

18

1.001806e+06

4003.963098

0

0.0

0.000077

1232

1

0.438

0.176

0.590

0.547

0

0

0

0

1.001783e+06

4003.919750

0

0.0

0.000000

1233

1

0.435

0.209

0.576

0.521

33

36

69

17

1.001784e+06

4003.921569

0

0.0

0.000069

1234

1

0.435

0.209

0.576

0.521

33

36

69

17

1.001784e+06

4003.921569

0

0.0

0.000069

1235

1

0.435

0.209

0.576

0.521

33

36

69

17

1.001784e+06

4003.921569

0

0.0

0.000069

1236

1

0.435

0.209

0.576

0.521

33

36

69

17

1.001784e+06

4003.921569

0

0.0

0.000069

Duplicate rows {.page-header}
==============

Most frequent {.indent}
-------------

Ocup\_2010

IVS\_2010

IVS\_INF\_10

IVS\_CPH\_10

IVS\_REN\_10

MASC

FEM

POP

DOM\_OCU

area

perimeter

URB\_RURAL

Dens\_Dom

Dens\_hab

count

28

0

0.362

0.112

0.595

0.379

258

296

554

168

4.008054e+04

800.869714

1

0.004

0.013822

64

95

1

0.435

0.209

0.576

0.521

114

138

252

75

4.007215e+04

800.791363

1

0.002

0.006289

49

27

0

0.362

0.112

0.595

0.379

170

178

348

100

4.008069e+04

800.871131

1

0.002

0.008682

39

62

1

0.310

0.105

0.467

0.357

138

182

320

80

4.007496e+04

800.817222

1

0.002

0.007985

38

66

1

0.310

0.105

0.467

0.357

207

228

435

132

4.007502e+04

800.817958

1

0.003

0.010855

35

63

1

0.310

0.105

0.467

0.357

147

170

317

87

4.007495e+04

800.817171

1

0.002

0.007910

32

17

0

0.310

0.105

0.467

0.357

283

308

591

145

1.001994e+06

4004.314205

0

0.000

0.000590

31

18

0

0.310

0.105

0.467

0.357

950

985

1935

552

1.001847e+06

4004.026548

0

0.001

0.001931

31

107

1

0.484

0.235

0.579

0.637

128

140

268

82

4.007701e+04

800.842349

1

0.002

0.006687

31

91

1

0.435

0.209

0.576

0.521

96

119

215

69

4.007230e+04

800.792818

1

0.002

0.005365

30

Report generated with
[pandas-profiling](https://github.com/pandas-profiling/pandas-profiling).
