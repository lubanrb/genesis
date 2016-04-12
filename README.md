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
curl -sSL https://raw.githubusercontent.com/lubanrb/genesis/master/bootstrap | bash -s /path/to/your/genesis.conf
```

You need to save the custom options in your own Genesis configuration file.

## Genesis Configurations

Please refer to [Simple Genesis config file](genesis.simple.conf) or [Genesis config file](genesis.complete.conf) for Genesis configuration reference. Also, if custom options are needed, you can use them as config file templates. Feel free to uncomment and customize the options that you need.
