# Model Builder Samples
This repository contains Decision Optimization samples that you can use in the Model Builder user interface in:
- IBM Watson Studio and Watson Machine Learning on IBM Cloud
- IBM Cloud Pak for Data V2.5.x, V3.0.x and V3.5.x
- IBM Watson Studio Local V2.1

For details on **how to use these samples**, refer to the *Examples and Samples* section of the Decision Optimization Building models documentation for your product.



## Repository contents
The `Cloud Pak for Data v2.5.x` directory contains  `.zip` files for the samples that can be used with IBM Cloud Pak for Data V2.5.x. and IBM Watson Studio Local V2.1.

The `Cloud Pak for Data v3.0.x` directory contains `.zip` files for the samples that can be used with IBM Cloud Pak for Data V3.0.x.

The `Cloud Pak for Data v3.5.x` directory contains `.zip` files for the samples that can be used with IBM Cloud Pak for Data V3.5.x.

The `Watson Studio Public` directory contains `.zip` files for the samples that can be used with IBM Watson Studio and Watson Machine Learning on IBM Cloud.

Each sample zip file contains one or more **scenarios** which provide the Decision Optimization model (in Python, OPL or using the Modeling Assistant) as well as the data in `.csv` files. Some samples also contain visualization files.

###  To use these samples

*In Cloud Pak for Data:*

1.    Download and unzip the DO-samples from the Decision Optimization GitHub on to your computer. (Choose the relevant product and version subfolder.)

2. Create a project in Cloud Pak for Data. Select **Create an empty project**, enter a project name and click Create.

3. Click **Add to Project**.

4. Select **Decision Optimization experiment**.

5. Select the **From file** tab in the Decision Optimization experiment pane that opens.

6. Click Add file. Then browse and navigate to the Model_Builder folder and relevant product and version subfolder in the DO-samples that you downloaded. Choose your sample zip file.
    
7. Choose a **deployment space** from the drop-down menu (or create one) and click Create.
8. Click **Create**

A Decision Optimization model is created with the same name as the sample.

*In Watson Studio on IBM Cloud:*
1.    Download and unzip the DO-samples from the Decision Optimization GitHub on to your computer. (Choose the relevant product and version subfolder.)

2. Create a project in IBM Watson Studio. Select **Create an empty project**, enter a project name and click Create.

3. In the Overview tab of your project, click **add a Machine Learning service** and select an existing service instance (or create a new one) and click **Select**.
4. Click **Add to Project**.

5. Select **Decision Optimization** experiment.

6. Select the **From file** tab in the Decision Optimization experiment pane that opens.

7. Click **Add file**. Then browse and navigate to the Model_Builder folder and relevant product and version subfolder in the DO-samples that you downloaded. Choose your sample zip file.
    
8. Choose a **deployment space** from the drop-down menu (or create one) and click Create. If you haven't already associated a Machine Learning service with your project, you must first select *Add a service* to select or create one, before choosing your deployment space for your experiment.
9. Click **Create**

A Decision Optimization model is created with the same name as the sample.
