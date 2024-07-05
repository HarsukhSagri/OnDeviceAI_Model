# On-Device Identity Card and Driving License Field Text Extraction

This project involves generating a synthetic dataset using image augmentation techniques and sample data generation libraries such as Faker. Various YOLO models (v8s, v8n, v9t, v10n) were trained on the dataset. The project also incorporates text and object detection using Tesseract OCR and EasyOCR to extract information from documents accurately.


See the [final output](bounding_boxes&text_detection/bounding_boxes_using_prediction.ipynb) for Identity Cards(India and Korea) and [final output](bounding_boxes&text_detection/bounding_boxes_using_prediction_v9t_US.ipynb) for US Driving License of various states as an example result of the overall model, which gives a glimpse of how YOLO models detected the classes and then Tesseract OCR is used for text detection in various fields.
