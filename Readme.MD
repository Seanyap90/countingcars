# Car counting

## Suggested file directory setup for Google Drive

### For Part 1:

Google Drive folder (give it a name)

│   CV_Traffic_LTA.ipynb   

└───master-plan-2014-planning-area-boundary-no-sea-shp

└───car_image_2019_Jan

└───car_image_2020_Jan


You can download the SHP file from https://data.gov.sg/dataset/master-plan-2014-planning-area-boundary-no-sea

### For Part 3:

Google Drive folder (give it a name)

│   CV_Traffic_LTA.ipynb

|   cv2.cpython-36m-x86_64-linux-gnu.so

└───master-plan-2014-planning-area-boundary-no-sea-shp

└───car_image_2019_Jan

└───car_image_2020_Jan

## Code Flow
1. Collect metadata from a user-defined period and a specific camera
3. Extract images from the URL of the metadata collected
4. Use yolov4 model to count cars from every image extracted

Concurrency is used to speed up API calls and car counting.
