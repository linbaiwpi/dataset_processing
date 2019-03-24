# dataset_processing
python functions for dataset processing

1. CSV to XML
Used for LISA traffic sign dataset to VOC format .xml file
example:
in LISA .csv:

Filename | Annotation tag | Upper left corner X | Upper left corner Y | Lower right corner X | Lower right corner Y | Occluded | On another road | Origin file | Origin frame number | Origin track | Origin track frame number
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
stop_1330545910.avi_image0.png | stop | 862 | 104 | 916 | 158 | 0 | 0 | aiua120214-0/DataLog02142012_external_camera.avi | 2667 | stop_1330545910.avi | 2
stop_1330545910.avi_image0.png | speedLimitUrdbl | 425 | 197 | 438 | 213 | 0 | 0 | aiua120214-0/DataLog02142012_external_camera.avi | 2667 | stop_1330545910.avi | 2

the VOC .xml output is:
[generated .xml file](./image/xml_example.jpg)

