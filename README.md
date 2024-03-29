
<!-- README.md is generated from README.Rmd. Please edit that file -->

# CLD — the Chinese Lexical Database

<!-- badges: start -->

<!-- badges: end -->

This is a wrapper around the .rda file provided at
<http://www.chineselexicaldatabase.com/index.php>

The Chinese Lexical Database, developed by Sun et al. (2018) is a
large-scale database for Mandarin Chinese, in simplified characters. The
paper can be found here:

Sun, C. C., Hendrix, P., Ma, J.Q. & Baayen, R. H. (2018). Chinese
Lexical Database (CLD): A large-scale lexical database for simplified
Mandarin Chinese. Behavior Research Methods,
<https://doi.org/10.3758/s13428-018-1038-3>.

**Please refer to Sun et al.'s (2018) work when you make use of this database.**

The CLD package contains the whole CLD version 2.1, with a few editions:

  - `Word` has been recoded as `WordSimp`
  - `C1, C2, C3, C4` have been recoded as `S1, S2, S3, S4`
  - `WordTrad` contains the traditional variants of `WordSimp`
  - Conversely, `T1, T2, T3, T4` are the traditional versions of `S1,
    S2, S3, S4`

This has been done in order to facilitate the usage in traditional
texts. Note, however, that the psycholinguistic findings of the CLD all
still relate to traditional characters.

The CLD package can be installed as follows:

## Installation

``` r
devtools::install_github("simazhi/cld/CLD") 
```
