# Luban Genesis

Luban Genesis is a utility to help developer bootstrap the first stand-alone Uber environment.

## Installation

### Fast track

To bootstrap Uber environment thru Genesis with default options: 

```
curl -sSL https://raw.githubusercontent.com/lubanrb/genesis/master/bootstrap | bash
```

### Customized track

To bootstrap Uber environment thru Genesis with custom options:

```
curl -sSL https://raw.githubusercontent.com/lubanrb/genesis/master/bootstrap | bash -s stage /path/to/your/genesis.conf
```
The first argument is the stage of Uber environment, for example, development, staging, production, etc. The second argument is the path to the Genesis configuration file with custom options.

You need to save the custom options in your own Genesis configuration file.

## Genesis Configurations

Please refer to [Simple Genesis config file](genesis.simple.conf) or [Genesis config file](genesis.complete.conf) for Genesis configuration reference. Also, if custom options are needed, you can use them as config file templates. Feel free to uncomment and customize the options that you need.
