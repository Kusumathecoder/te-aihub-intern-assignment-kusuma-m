# BCCD Annotation Assignment

## Project Summary
This project demonstrates a local annotation workflow using Docker and Label Studio for blood cell object detection annotation.

## Dataset Used
BCCD Blood Cell Count and Detection Dataset

Classes:
- RBC
- WBC
- Platelets

Dataset Source:
https://github.com/Shenggan/BCCD_Dataset

## Setup Steps

### Install Docker
Docker Desktop was installed on Windows.

### Run Label Studio
Command used:

docker run -it -p 8081:8080 heartexlabs/label-studio:latest

### Open Label Studio
http://localhost:8081

## Project Configuration

Project Name:
BCCD Annotation Assignment

Annotation Type:
Object Detection with Bounding Boxes

Labels Used:
- RBC
- WBC
- Platelets

## Images and Annotation
- Imported 10 images
- Annotated all images manually using bounding boxes

## Export
Exported annotations are available in:

exports/label_studio_export.json

## Screenshots
Screenshots are available in the screenshots folder.

## AI Tools Used
Used ChatGPT for:
- Docker setup guidance
- Label Studio workflow understanding
- README formatting help

## Issues Faced
- Docker port conflict on 8080
Solved by using port 8081.

- Label Studio temporary storage reset
Recreated project and continued annotation.

## Annotation Quality Plan for Large Projects
For large-scale annotation:
- Create annotation guidelines
- Use reviewer validation
- Perform random quality checks
- Use consensus review for difficult samples

## Demo Video
Google Drive link will be added in video_link.txt