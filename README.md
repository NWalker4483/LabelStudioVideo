# LabelStudioVideo

This script processes video annotations exported from Label Studio
in JSON-MIN format, converting them directly into the COCO dataset format. 
The script supports interpolation of bounding boxes for intermediate frames based 
on key-frame annotations and exports these labels along with corresponding frames.

You may need to modify the ```parse_video_name``` and ```match_video_file``` to your particular dataset and data setup
