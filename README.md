qiitr - R Binding for Qiita API
==========================

*This package is in a very early state and is experimental. You've been warned!*

## About Qiita

About Qiita: http://qiita.com/about
API Document: http://qiita.com/api/v2/docs

## Installation

```r
devtools::install_github("yutannihilation/qiitr")
```

## Usage

```r
q <- Qiita$new(token = "abcdefghijk")
q$get_comment(comment_id = "test")
```
