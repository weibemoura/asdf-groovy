# asdf-groovy

[![Build Status](https://github.com/weibemoura/asdf-groovy/actions/workflows/asdf.yml/badge.svg)](https://github.com/weibemoura/asdf-groovy/actions)

[Groovy](http://groovy-lang.org/) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager


## Install

```shell
asdf plugin-add groovy https://github.com/weibemoura/asdf-groovy.git
```

## Requirements

#### Java

Java is required. It can be installed using the asdf java plugin.

### JAVA_HOME

The plugin requires `JAVA_HOME` to be exported. For your convenience, it exports it for you using `asdf` but if you use the `JAVA_HOME` export feature of `asdf-java` or export it yourself, you can disable this functionality by:  
```shell
export ASDF_GROOVY_DISABLE_JAVA_HOME_EXPORT=true
```

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Groovy.
