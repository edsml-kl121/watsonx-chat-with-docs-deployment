1. Go to prompt lab and `add documents` Create a vector index in watsonx ai.
![alt text](images/image.png)

2. Choose a model until you are satisfied and try chatting with the documents.

![alt text](images/image-1.png)

3. Please save as `Deployment notebook`. If you haven't created a deployment space please do so before going to this step.

![alt text](images/image-2.png)

![alt text](images/image-3.png)

4. Edit the notebook and replace with your `api-key`
![alt text](images/image-4.png)

5. You should see your AI Service is successfuly deployed. and the Model inference is working properly. You can try run `API_TEST.ipynb` notebook to use it in your own custom application or follow step 6 onwards to integrate this with watsonx-assistant.
![alt text](images/image-5.png)

6. Firstly create your assistant. Then go to settings. Ensure you select `English`

![alt text](images/image-7.png)

7. Please upload the action json file
![alt text](images/image-6.png)

8. You will see action being uploaded
![alt text](images/image-8.png)

9. Go to integration, we will need to add in an extension to get rid of the error.

![alt text](images/image-9.png)

![alt text](images/image-10.png)
![alt text](images/image-11.png)

10. Click on `add`
![alt text](images/image-12.png)

11. Fill in as follows and add your api key in.

![alt text](images/image-13.png)

12. If you go back to actions you will see it is green now 😀

![alt text](images/image-14.png)

13. Please add in your `deployment_id`

![alt text](images/<Screenshot 2568-05-19 at 13.48.18.png>)


14. Try chat with the docs and Enjoy!
![alt text](images/image-15.png)