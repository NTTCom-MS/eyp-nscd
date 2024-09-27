# nscd

#### Table of Contents

1. [Overview](#overview)
2. [Module Description](#module-description)
3. [Setup](#setup)
    * [What nscd affects](#what-nscd-affects)
    * [Setup requirements](#setup-requirements)
    * [Beginning with nscd](#beginning-with-nscd)
4. [Usage](#usage)
5. [Reference](#reference)
5. [Limitations](#limitations)
6. [Development](#development)

## Overview

Installs nscd package.

This documentation has reviewed up to version 1.0.0.

## Setup

### What nscd affects

* package nscd
* service nscd.

## Usage

```puppet
class { 'nscd': }
```

## Limitations
* Redhat and derivatives: 7 release.
* Others: unsuported.
