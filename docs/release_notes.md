# Release notes

## Nightly

### Features

*   Add `in_memory` option to cache small dataset in RAM.
*   Better sharding, shuffling and sub-split
*   It is now possible to add arbitrary metadata to `tfds.core.DatasetInfo`
    which will be stored/restored with the dataset. See `tfds.core.Metadata`.
*   Better proxy support, possibility to add certificate
*   Add `decoders` kwargs to override the default feature decoding
    ([guide](https://github.com/tensorflow/datasets/tree/master/docs/decode.md)).
*   Add `duke_ultrasound` dataset of ultrasound phantoms and invivo liver images
    from the [MimickNet paper](https://arxiv.org/abs/1908.05782)
*   Add Dmlab dataset from the
    [VTAB benchmark](https://arxiv.org/abs/1910.04867).
