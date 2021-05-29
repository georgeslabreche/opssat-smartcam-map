# OPS-SAT SmartCam Map
Mapping the groundtrack locations of the [OPS-SAT spacecraft](https://opssat1.esoc.esa.int/) when images were acquired. The map is hosted as a GitHub Page, [here](https://georgeslabreche.github.io/opssat-smartcam-map/). All OPS-SAT images were acquired by the spacecraft's [SmartCam](https://github.com/georgeslabreche/opssat-smartcam) and credited to ESA.

## Adding new thumbnails
1. Upload the thumbnails image files as well as the .csv and .log files to their dedicated folders inside the `data` directory.
2. Update the `CAMERA_START_TIMESTAMPS` array in **index.html** to contain the timestamp of the .csv filenames that contain the metadata of the thumbnails to be added.

Note that the .log files are not used in any way. They are just included for record-keeping.

## Running locally
The map can be loaded locally without uploading the thumbnails to the repository's `data` directory. However, the .csv metadata files still need to be uploaded. This is a known issue: [Issue \#1](https://github.com/georgeslabreche/opssat-smartcam-map/issues/1).
