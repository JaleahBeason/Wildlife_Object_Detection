# Wildlife Object Detection 🦌

A computer vision project using YOLOv8 trained to detect and 
classify 35 wildlife species in real-world images.

## Dataset
- Source: [Roboflow Universe — Wildlife Monitoring Dataset](https://universe.roboflow.com/wildlife-monitoring-6xfso/wildlife-h0udb/dataset/1)
- 35 species including bison, deer, panda, tiger, zebra, 
raccoon, wolf, snake, and more
- Pre-labeled dataset with bounding box annotations

## Model
- Architecture: YOLOv8
- Training environment: Google Colab
- Language: Python / Jupyter Notebook

## Results
| Metric | Score |
|--------|-------|
| Precision | 0.391 |
| Recall | 0.335 |
| mAP@0.5 | 0.412 |
| mAP@0.5:0.95 | 0.286 |

Model performance reflects the complexity of detecting 35 
visually diverse species across varied real-world environments.

## Project Files
| File | Description |
|------|-------------|
| `Wildlife_Model.ipynb` | Main notebook — training, evaluation, results |
| `Wildlife_Report.docx` | Full written project report |
| `wildlife presentation.pptx` | Project presentation slides |

## Skills Demonstrated
- Computer vision and object detection
- Machine learning model training and evaluation
- Python, Jupyter Notebook, YOLOv8
- Dataset preparation via Roboflow
- Performance analysis using confusion matrix and mAP metrics
