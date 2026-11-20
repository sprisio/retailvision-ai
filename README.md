# RetailVision AI – AI-Powered Retail Inventory Intelligence System

RetailVision AI is an AI-based prototype designed to help supermarkets gain insights into their inventory using **Computer Vision and Large Language Models (LLMs)**.

The project aims to combine real-time object detection with AI-powered data analysis to identify inventory patterns, highlight potential overstock situations, and generate intelligent restocking recommendations.

## Problem Statement

Small and medium-sized supermarkets often struggle with inventory management, leading to overstocking, product shortages, and unnecessary financial losses.

RetailVision AI aims to address these challenges by combining visual object detection with intelligent inventory analysis.

## Key Features

- **Object Detection:** Detect objects in images and videos using YOLO11.
- **Visual Analytics:** Display detected objects with bounding boxes and confidence scores.
- **Object Counting:** Generate class-wise detection counts.
- **Inventory Analysis (Planned):** Analyse product sales and stock data.
- **AI-Generated Reports (Planned):** Use an LLM to generate inventory summaries and restocking suggestions.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| YOLO11 | Object detection |
| OpenCV | Image and video processing |
| PyTorch | Deep learning framework |
| Streamlit | Interactive dashboard |
| Pandas | Data processing |
| Ollama | Local LLM integration (planned) |

## Project Workflow

1. Upload an image or video for object detection.
2. YOLO11 processes the visual input and detects objects.
3. View detection results, confidence scores, and object counts.
4. Provide structured inventory and sales data.
5. An LLM analyses the supplied data and generates inventory insights (planned).



## Future Enhancements

- Integration with local LLMs using Ollama.
- Automated monthly inventory summaries.
- Identification of fast-moving and slow-moving products.
- Overstock detection and restocking recommendations.
- Supermarket-specific product detection using custom-trained models.
- Integration with real-world inventory and POS systems.

## Limitations

- The initial YOLO model detects general object categories rather than individual supermarket SKUs.
- Camera-based object detection does not confirm whether a product was purchased.
- Inventory recommendations depend on the quality of the supplied sales and stock data.
- LLM-based inventory analysis is planned for a future development phase.



---

**Project Name:** RetailVision AI  
**Category:** Artificial Intelligence | Computer Vision | Generative AI  
**Status:** Prototype / Under Development
