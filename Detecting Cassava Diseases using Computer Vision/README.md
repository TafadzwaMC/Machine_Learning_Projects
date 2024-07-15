
 Business Overview/Problem

Novel Farms intends to ride the wave provided by the recent advent of technology. They have already taken advantage of engineering advances; now they plan to incorporate software more tightly into their farming operations. This will assist in maintaining their competitive edge in the market.

The goal is to leverage data to improve farming operations. If this is successful, the board intends to build an agriculture-based tech startup around this data-driven approach.

This startup will offer these same services to other local, smaller and/or subsistent farms both as a community service and a means of building value with and making money from competitors.

At present, the most pressing issue for Novel Farms is the recent strain of infections plaguing their cassava crops. Manually monitoring and diagnostics for signs of disease is not efficient due to scale.

This is the first test of the company’s new data-driven initiative: design a software system that can detect infected cassava crops. Once such crops are detected, they can be specifically treated by farm hands as required.

 

You, an accomplished data scientist, have been recommended to spearhead this effort. Classified data will be made available for this problem. As extra incentive to do well, success in this endeavour may very well mean a new, cushy position as Chief of Data at this prospective, new startup.

So, you know, no pressure! We are counting on you!

To be more specific, the issues Novel Farms would like to solve are:

     Crop Loss and Disease Diversity: Cassava is susceptible to various diseases, each with its symptoms and progression patterns. 

 

     Manual Detection: Current methods for disease detection rely on visual inspection by farmers, which can be subjective and prone to errors. This can easily culminate in significant crop losses, impacting food security and livelihoods. 

 

    Delayed Detection and Lack of Expertise: A lot of infections are not so obvious to manual inspection and visual evidence tends to appear late. Also, most farmers lack the expertise to identify diseases accurately, leading to delayed responses.

Rationale for the Project

    The cassava crop is a staple in many African countries, and across the world. It can make up as much as 80% of the expected yield for a commercial farm.

    As such, cassava infections are a big blow to commercial farms and the agricultural sector, affecting the food security and agro-allied industries that depend on the crop. This makes early detection a necessity. Failure to detect early may result in:
         Cassava Mosaic Disease: This disease can cause yield losses of up to 90%, making early detection critical. 
         Cassava Brown Streak Disease: It affects the quality of cassava roots and reduces their market value. 
        Cassava Bacterial Blight: Early detection can help implement measures to prevent disease spread

    More rationale for cassava disease detection include:
         Economic Impact: Reducing disease-related crop losses has a significant economic impact on farmers and communities. This will positively impact food security and operations of agro-allied industries. 
         Sustainable Agriculture: Disease prevention contributes to long-term, sustainable cassava farming practices. 
        Cost-Efficiency: As a large-scale farming enterprise, Novel Farms spends a large amount of money on hiring experts for manual disease diagnosis. This cost can be reduced, leading to cost savings.

Aim of the Project

The aims of the project are:

     Develop Disease Detection Models: Create computer vision models capable of accurately detecting various cassava diseases. 
     Model Engineering and Postprocessing: Limit the size of the model to speed up inference. 
    Model Deployment: Deploy the trained models for use by farmers.

Data Description

You have carte blanche to request whatever data you require. Based on your wealth of experience, you know you require:

     Cassava Leaf Images: A large collection of high-quality images of cassava leaves, including healthy and diseased samples. 
     Cassava Spectral Images: A large collection of high-quality spectral images of cassava crop, including healthy and diseased samples. 
    Disease Labels: Accurate labels specifying the disease type (and/or severity) for each image

Tech Stack

The Programming language of use, as in most of ML, is Python.

The Python libraries of interest for this project are:

     OpenCV: Image loading and manipulation. 
     Pandas: Data munging and manipulation. 
     PyTorch: Deep learning library. 
    Tensorflow: Deep learning framework.

Project Scope

Image Preparation and Model Development: The data is thoroughly explored in order to get a feel for its quirks such as data imbalance. The data will then be processed and appropriate deep learning models will then be built and trained on the dataset in a systematic manner.

Model Evaluation: Once the models are developed, they are evaluated using appropriate evaluation metrics and validation techniques. This involves assessing their performance, generalizability, and robustness. The best-performing model(s) are selected for further deployment or refinement, and attempts to explain why they work and what they learn are made.

Model Engineering and Postprocessing: Model engineering techniques will be applied to the trained model to boost performance. For instance, the size of the model will be reduced by applying techniques like quantization, model distillation, etcetera. This will allow for speedy inference operations.

Model Deployment: The postprocessed model is deployed for use by the team at Novel Farms.
Project Contributor
Benedict Emoekabu Project Contributor
