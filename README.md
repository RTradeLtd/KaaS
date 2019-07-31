# kaas (Krab As A Service)

[![Build Status](https://travis-ci.com/RTradeLtd/kaas.svg?branch=master)](https://travis-ci.com/RTradeLtd/kaas)

`kaas` is intended to make it easy to use the krab keystore within projects that
have multiple readers and writers for ipfs keystores. Due to the usage of badger,
we can only have a single process that serves as a reader+writer, or multiple
processes performing read-only tasks. 

## Multi-Language

[![](https://img.shields.io/badge/Lang-English-blue.svg)](README.md)  [![jaywcjlove/sb](https://jaywcjlove.github.io/sb/lang/chinese.svg)](README-zh.md)
