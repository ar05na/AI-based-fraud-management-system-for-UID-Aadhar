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
clone the respository
set up the environment
download the requirements from requirements.txt
and run this through python app.py command
it will show the path........ 
upload the given sample input files and after processsing downlaod the results.xlsx file
I am integrating some images of my project to know the actual output<img width="581" alt="results 1" src="https://github.com/user-attachments/assets/55155040-e282-4f24-b449-d4374dcf28e0" />
<img width="614" alt="main page" src="https://github.com/user-attachments/assets/5bfaf5e0-2db6-4ca7-8539-757e57147be8" />





