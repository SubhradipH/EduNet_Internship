# EduNet_Internship
Steps to create the Machine learning project
Step 1 :- Log into the IBM cloud with gmail.
Step 2 :- after logging in we are at the dashboard page form there we need to move the resource list.
step 3 :- In the resource list if there are any previous projects we need to delete it before creating a new project.
step 4 :- after deleting the resources we need to move to the search bar and search for (Watsonx.ai studio) service and click on it.
step 5 :- after clicking on Watsonx.ai studio) service we are redirected to another page to create a studio and we need to create it by clicking on the create button.
step 6 :- after that there is a launch in button we need to click it after clicking on it we are redirected to another page named (Build and manage ml models) there we need to select provision watsonx.ai runtime and click on next button.
step 7 : ater doing the step 6 we are redirected to anothe page where we need to create a runtime by clicking on the create button.
step 8 :- after step 7 we are redirected to a page where we select new project and click on next button.
step 9 :- after step 7 we are the create a project page where we give the details of the project like its name and add a storage space by cliking on the add button. When we click on add button we are redirected to the cloud object storage page where we need to select free plan and click on the create button .
step 10 :- after clicking on the create button we are againg redirected back to the creat procject page where we can see the storge space we we are unable to see it we need to refresh it and click on the create button to create a project space.
step 11 :- after step 10 we need to go to manage tab in the project space and associate service after clicking on it we need to select watsonx.ai Runtime and click on associte this will associte the services with the project.

step 12 :- we need to move to overview and  Click on “Build machine learning models automatically” and Enter the experiment name and click on Create.
step 13 :- Add the downloaded data set (predictive_maintenance.csv) with the help of 
Browse option select the data set and click on Open.
step 14 :- Data set is loaded. In create a time series analysis? You can choose No 
option.
step 15 :- Choose prediction column for me it was (Failure Type).
step 16 :-  after choosing prediction column we now click on the Run experiment. The  Auto AI experiment will start running and we can change the view by clicking on swap view.
step 17 :- Pipelines are building. The pipelines are arranged in a leader board manner where the best performing model is at the top. In my case it was (pipeline 4).
step 18 :- Now we can save this model. Click on the Save as and  Choose Model asset and click on Create the mode saved successfully and click on view in project.
step 19 :- Click on promote to space on arrow this will create the new deployment space. 
step 20 :- We give the deployment space name and select watsonx.ai Runtime service , 
click on Create . It will start preparing the deployment space. The space gets ready , close the dialog box and click on the promote. It will promote the space and after the we click on deployment space.
step 21 :- Click on the Asset name and click on the New deployment. We need to select deployment type and give the deployment name. Click on the Create. The model gets deployed.
step 22 :- Now we can click on Test to predict with new values. We need to enter the new values and click on predict. It will show the Prediction results .
Example :- I used these values for prediction --
UDI	Product ID	Type	Air temperature [K]	Process temperature [K]	Rotational speed [rpm]	Torque [Nm]	Tool wear [min]	Target
8609	L55788	L	297.4	308.4	1369	50.6	220	1	
The model predected it (Overstrain Failure) which is absolutly correct .

These are all the steps required to create the project .

THANK YOU.....
