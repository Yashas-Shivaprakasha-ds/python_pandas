# Python_Pandas_Module


## Introduction 👋

### What is Pandas in Python?
[![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/) is the most famous python library providing fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, **real world** data analysis in Python. Additionally, it has the broader goal of becoming **the most powerful and flexible open source data analysis / manipulation tool available in any language**. It is already well on its way towards this goal.

In Pandas, the data is usually utilized to support the statistical analysis in **SciPy**, plotting functions from **Matplotlib**, and machine learning algorithms in **Scikit-learn**.


## Main Features
Here are just a few of the things that pandas does well:

  - Easy handling of [**missing data**][missing-data] (represented as `NaN`) in floating point as well as non-floating point data
  - Size mutability: columns can be [**inserted and deleted**][insertion-deletion] from DataFrame and higher dimensional objects
  - Automatic and explicit [**data alignment**][alignment]: objects can be explicitly aligned to a set of labels, or the user can simply
    ignore the labels and let `Series`, `DataFrame`, etc. automatically align the data for you in computations
  - Powerful, flexible [**group by**][groupby] functionality to perform split-apply-combine operations on data sets, for both aggregating
    and transforming data
  - Make it [**easy to convert**][conversion] ragged, differently-indexed data in other Python and NumPy data structures
    into DataFrame objects
  - Intelligent label-based [**slicing**][slicing], [**fancy indexing**][fancy-indexing], and [**subsetting**][subsetting] of
    large data sets
  - Intuitive [**merging**][merging] and [**joining**][joining] datasets
  - Flexible [**reshaping**][reshape] and [**pivoting**][pivot-table] of datasets
  - [**Hierarchical**][mi] labeling of axes (possible to have multiple labels per tick)
  - Robust IO tools for loading data from [**flat files**][flat-files] (CSV and delimited), [**Excel files**][excel], [**databases**][db],
    and saving/loading data from the ultrafast [**HDF5 format**][hdfstore]
  - [**Time series**][timeseries]-specific functionality: date range generation and frequency conversion, moving window statistics,
    moving window linear regressions, date shifting and lagging, etc.


   [missing-data]: https://pandas.pydata.org/pandas-docs/stable/missing_data.html#working-with-missing-data
   [insertion-deletion]: https://pandas.pydata.org/pandas-docs/stable/dsintro.html#column-selection-addition-deletion
   [alignment]: https://pandas.pydata.org/pandas-docs/stable/dsintro.html?highlight=alignment#intro-to-data-structures
   [groupby]: https://pandas.pydata.org/pandas-docs/stable/groupby.html#group-by-split-apply-combine
   [conversion]: https://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe
   [slicing]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#slicing-ranges
   [fancy-indexing]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#advanced-indexing-with-ix
   [subsetting]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#boolean-indexing
   [merging]: https://pandas.pydata.org/pandas-docs/stable/merging.html#database-style-dataframe-joining-merging
   [joining]: https://pandas.pydata.org/pandas-docs/stable/merging.html#joining-on-index
   [reshape]: https://pandas.pydata.org/pandas-docs/stable/reshaping.html#reshaping-and-pivot-tables
   [pivot-table]: https://pandas.pydata.org/pandas-docs/stable/reshaping.html#pivot-tables-and-cross-tabulations
   [mi]: https://pandas.pydata.org/pandas-docs/stable/indexing.html#hierarchical-indexing-multiindex
   [flat-files]: https://pandas.pydata.org/pandas-docs/stable/io.html#csv-text-files
   [excel]: https://pandas.pydata.org/pandas-docs/stable/io.html#excel-files
   [db]: https://pandas.pydata.org/pandas-docs/stable/io.html#sql-queries
   [hdfstore]: https://pandas.pydata.org/pandas-docs/stable/io.html#hdf5-pytables
   [timeseries]: https://pandas.pydata.org/pandas-docs/stable/timeseries.html#time-series-date-functionality


### Core Components of Pandas Data Structure
Pandas have two core data structure components, and all operations are based on those two objects. Organizing data in a particular way is known as a data structure. Here are the two pandas data structures:

* **Series**
* **DataFrame**


## Install Pandas Module:

Open your [![Anaconda](https://img.shields.io/badge/Anaconda-342B029.svg?&style=flate&logo=anaconda&logoColor=white)](https://www.anaconda.com/products/individual) Prompt <img alt="propmt" src="https://img.shields.io/badge/-__-000000?style=flat-square&logo=Plex&logoColor=white"> and type and run the following command (individually):

 -       pip install pandas  
 

Once Installed now we can import it inside our python code.

You can download the dataset from following link: http://bit.ly/SO-Survey-Download 

It contains two csv files:
1. survey_results_public
2. survey_results_schema
---  

## Authors ✍️

I'm Yashas and I have written this tutorial. If you think you can add/correct/edit and enhance this tutorial you are most welcome🙏
