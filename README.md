# p2p-instancemanager

This application enables control of virtual compute instances.

## Build

This project depends upon `p2p-build` being setup with `ant` and `ant-contrib`. [See instructions](http://barnyard.github.io/p2p-build)

### Dependencies

The following projects should be siblings to this project and had 'publish' targets run on them.

- [p2p-networkmanager](http://barnyard.github.io/p2p-networkmanager)

### Compiling

Add a properties file with your configuration you'd like in the `properties` directory.

    ant

