# Darknet
Darkent - Object Detection

### Performances for Aquarium Data Sets

calculation mAP (mean average precision)...
128
 detections_count = 8486, unique_truth_count = 909  
class_id = 0, name = fish, ap = 53.00%   	 (TP = 234, FP = 122) 
class_id = 1, name = jellyfish, ap = 60.37%   	 (TP = 100, FP = 56) 
class_id = 2, name = penguin, ap = 30.45%   	 (TP = 36, FP = 49) 
class_id = 3, name = puffin, ap = 23.13%   	 (TP = 18, FP = 19) 
class_id = 4, name = shark, ap = 19.16%   	 (TP = 18, FP = 35) 
class_id = 5, name = starfish, ap = 50.27%   	 (TP = 14, FP = 5) 
class_id = 6, name = stingray, ap = 27.26%   	 (TP = 15, FP = 25) 

 for conf_thresh = 0.25, precision = 0.58, recall = 0.48, F1-score = 0.53 
 for conf_thresh = 0.25, TP = 435, FP = 311, FN = 474, average IoU = 37.40 % 

 IoU threshold = 50 %, used Area-Under-Curve for each unique Recall 
 mean average precision (mAP@0.50) = 0.376649, or 37.66 % 
Total Detection Time: 5 Seconds
