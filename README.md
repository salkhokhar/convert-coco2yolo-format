# convert-coco2yolo-format
This scripts converts bbox from coco json to yolo txt format even for specific categories.


# Usage

`python COCO2YOLO.py -j coco.json -o path_to_dir`
### Or download [Release](https://github.com/salkhokhar/convert-coco2yolo-format.git) and run
`COCO2YOLO.exe -j coco.json -o path_to_dir`

# To test the conversion you can run test.py
`python test.py -i img.jpg -t converted_to_yolo.txt`
