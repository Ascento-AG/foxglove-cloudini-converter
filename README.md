# foxglove-cloudini-converter

A Foxglove extension to convert `Cloudini` compressed point clouds to a standard `PointCloud2` message.

## Usage

1. Install `npm install`
2. Build the extension with `npm run package`
3. Open the extension manager
4. Drag and drop the `*.foxe` file into the extension manager

## Notes

`Cloudini` is a library for point cloud compression. See [the official repo](https://github.com/facontidavide/cloudini) for extended documentation and examples.

This extension builds upon the cloudini core functionalities to decompress messages and allow visualization in Foxglove. Since at the time of writing, mainstream does not yet integrate all the required functionality, this work is based on a [fork](https://github.com/grizzi/cloudini/tree/compression-wasm) of the original repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🚨 Important Notice

Further development on this project is limited to the priorities of Ascento AG. This work is intended mainly for internal use. We appreciate your interest, but please be aware that we do not currently plan to support external contributions or ongoing community maintenance.
