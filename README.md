TITLE:AI-Based fraud management system for UID Aadhar



Step 1:
In the frontend accept the zip file(contain aadhar images)and excel file(contains actual data)
process the zip files using classification,detection,ocr and extract text from  images
(Implement the classification model,detection model with YOLO use the datasets mentioned in folders classification_model,detection_model
Extract text from detection objects with the help of Easy ocr)

step 2:
Here comes the matching logic and scoring between extracted data and the actual input from excel 
Use the file matching_logic.docx to create the matching files

step 3:
Front end and Backend integration (apply matching logic and calculate matching score and store them to results excel file)

Step 4:
visualizing the results(pie chat,bar chart,....etc)


![flowchart (1)](https://github.com/user-attachments/assets/a4cd6edd-008e-4023-9ccc-02ac8280b139)


How TO RUN THIS:
1)clone the respository

2)set up the environment

3)download the requirements from requirements.txt
and run this through python app.py command
it will show the path........ 

4)upload the given sample input files and after processsing downlaod the results.xlsx file

I am integrating some images of my project to know the actual output

<img width="614" alt="main page" src="https://github.com/user-attachments/assets/1ee5c6f6-c600-4bda-a441-b35b25f12913" />
<img width="581" alt="results 1" src="https://github.com/user-attachments/assets/1480421c-00d2-4c31-abb0-db82bfef97b0" />






