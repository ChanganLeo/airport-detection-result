## airport_result_shp
    The file directory holds the results of the airport identification framework, and the data is a shapeFile vector file. 
    The result column expresses the description of recognition, where 1 is the new discovered airport, 0 is the known airport, and -1 is the incorrectly identified airport.
## models
    https://www.jianguoyun.com/p/DWBfi-QQlIqbCBjQ6c4D (password：o6w8m0)
    01_scene_classification.h5: the scene classification model.
        VERSION: keras: 2.1.0, tensorflow-gpu: 1.14.0, python: 3.6.8
    02_yolo_v3_runway.h5: the yoloV3 runway detecion model.
        VERSION: keras: 2.2.4, tensorflow-gpu: 1.13.1, python: 3.6.5