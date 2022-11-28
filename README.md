## Deep Learning: American Sign Language Detection
<img style='align:center' src="https://github.com/fathur-rs/sign_languange_detection/blob/main/preview.png" width="800"/>

## Intro
American Sign Language (ASL) is a sign language that has the same linguistic properties as spoken language, with a different grammar from English. ASL is expressed by hand and facial movements. It is the primary language widely spoken by deaf and hard of hearing North Americans.

## Data Used
The data used is primary data that uses the open-cv library to capture photos of hands based on shapes that symbolize the letters of the American sign language. cvzone library is used to map the skeleton structure of the fingers to make it easier for the model to distinguish characteristics between letters which can improve the accuracy of the model. The label consists of the letters A-Z which is represented by number notation (A=1, B=2, ...) except for the letters J and Z due to the need for finger motion to indicate these letters.
[Sign Language Dataset](https://drive.google.com/drive/folders/1hn_DGhWFwiArVYTug0lL6VUswfVSyCi-?usp=share_link)
