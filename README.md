# af [![Build Status](https://travis-ci.org/xyproto/af.svg?branch=master)](https://travis-ci.org/xyproto/af) [![Go Report Card](https://goreportcard.com/badge/github.com/xyproto/af)](https://goreportcard.com/report/github.com/xyproto/af) [![GoDoc](https://godoc.org/github.com/xyproto/af?status.svg)](https://godoc.org/github.com/xyproto/af)

Activation functions, intended for use in neural networks.

These function aliases are included:

* Sigmoid (optimized, from the [swish](https://github.com/xyproto/swish) package).
* Swish (optimized, from the [swish](https://github.com/xyproto/swish) package).
* SoftPlus (optimized, from the [swish](https://github.com/xyproto/swish) package).
* Gaussian01 (optimized, from the [swish](https://github.com/xyproto/swish) package).

These activation functions are provided:

* Sin (`math.Sin(math.Pi * x)`)
* Cos (`math.Cos(math.Pi * x)`)
* Linear (`x`)
* Inv (`-x`)
* ReLU (`x >= 0 ? x : 0`)
* Squared (`x * x`)

These `math` functions are included just for convenience:

* Abs (`math.Abs`)
* Tanh (`math.Tanh`)

Functions that take two arguments are also included:

* PReLU (`x >= 0 ? x : x * a`)

## Requirements

* Go 1.11 or later.

## General information

* License: MIT
* Version: 0.3.1
* Author: Alexander F. Rødseth &lt;xyproto@archlinux.org&gt;
