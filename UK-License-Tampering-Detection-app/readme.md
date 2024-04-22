<a name="readme-top"></a>

<div align="center">

# __Uk Fake Licence Detector __



Visit the <a href="uk-fake-licence-detector-c1cf308019d6.herokuapp.com">Web Application</a> deployed on render

</div>

## __About__
<p align="justify">
This is a simple application to detect tampering of Pan Cards using <a href="https://en.wikipedia.org/wiki/Structural_similarity#:~:text=The%20structural%20similarity%20index%20measure,the%20similarity%20between%20two%20images.">Structural Similarity Index Measure (SSIM)</a>. It is used to measure similarity of two images. A Pan Card is tampered if it's SSIM value with original Pan Card template is low.

Step to run application:
Step 1:	Create the copy of the project.
Step 2: Open command prompt and change your current path 
to folder where you can find 'app.py' file.
Step 3: Create environment by command given below-
conda create -name <environment name>
Step 4: Activate environment by command as follows-
conda activate <environment name>
Step 5: Use command below to install required dependencies-
python -m pip install -r requirements.txt
Step 6: Run application by command;
python app.py
You will get url copy it and paste in browser.
Step 7: You have sample_data folder where you can get images to test.
