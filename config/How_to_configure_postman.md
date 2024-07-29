# How to Configure Postman

This guide will help you configure Postman to use the `Student_API_Collection_Task_Collection.postman_collection` file located at `api/postman/Student_API_Collection_Task_Collection.postman_collection`.

## Prerequisites

- [Postman](https://www.postman.com/downloads/) installed on your machine.
- The `Student_API_Collection_Task_Collection.postman_collection` file available in the `api/postman` directory of your repository.

## Steps to Configure Postman

### Step 1: Open Postman

Launch the Postman application on your computer.

### Step 2: Import the Collection

1. Click on the **Import** button located at the top left corner of the Postman application.

   ![Import Button](https://user-images.githubusercontent.com/43025513/126133913-e6d9eb3c-8852-4f19-8c17-9d556ec80fe7.png)

2. In the **Import** dialog, select the **Upload Files** tab.

3. Click on the **Choose Files** button and navigate to the `Student_API_Collection_Task_Collection.postman_collection` file located at `api/postman/Student_API_Collection_Task_Collection.postman_collection` in your repository.

4. Select the `Student_API_Collection_Task_Collection.postman_collection` file and click **Open**.

5. Click the **Import** button in the Import dialog.

### Step 3: Verify the Collection

1. After importing, you should see a new collection named `Student_API_Collection_Task_Collection` in the Collections tab on the left sidebar.

2. Expand the collection to see the various endpoints and requests available.

### Step 4: Set Up Environment Variables (Optional)

If your API collection uses environment variables, you need to set them up in Postman.

1. Click on the **Environment Quick Look** button (the eye icon) in the top right corner of Postman.

   ![Environment Quick Look](https://user-images.githubusercontent.com/43025513/126134171-35e4a9a2-48ac-4d3b-9f29-8439f3c6c5bb.png)

2. Click on **Add** to create a new environment.

3. Enter a name for your environment (e.g., `Student API Environment`).

4. Add the necessary variables and their values as required by your API collection.

5. Click **Add** to save the environment.

6. Select your new environment from the Environment dropdown in the top right corner.

### Step 5: Send Requests

1. Select a request from the `Student_API_Collection_Task_Collection` collection.

2. Click the **Send** button to send the request.

3. View the response in the Postman interface.

### Conclusion

You have successfully configured Postman to use the `Student_API_Collection_Task_Collection.postman_collection` file. You can now interact with your API endpoints using Postman. If you have any issues or need further assistance, refer to the Postman documentation or contact your API support team.

## Additional Resources

- [Postman Documentation](https://learning.postman.com/docs/getting-started/introduction/)
- [Postman Learning Center](https://learning.postman.com/)
