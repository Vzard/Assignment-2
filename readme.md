### Operationalize the ML Pipeline

LINK: https://youtu.be/2S1YA5B61tc 

### Project Scope and Overview

The goal is to continue the exercise from previous module to operationalize the ML Model to ensure consumer access. Like any service (say API) this will have an endpoint. The dataset as previous case will use the bank marketing set. The outcome is to provide a pipeline and pipeline endpoint. 
The process involves key steps  – creating a model, deploying, and pipeline setup. This is part of module 2 assignment
Project flow (Architecture)
Step 1 : Authentication steps : Create a Service principal (exhibit 1)
Step 2: Auto ML experiment: This is same as previous module, (exhibit set 2 A,B, C)
Step 3 : Logging using AppInsight (exhibit set 3)
Step 4: Swagger (Exhibit set  4)
Step 5: Consume Model (Exhibit 5)
Step 6: Create, Publish Pipeline Consume Pipeline. (Exhibit set 7)



## Service Principal creation (Exhibit 1)

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image001.png)![images](https://github.com/Vzard/Assignment-2/blob/main/images/image002.png)


## Service Principal creation (Exhibit 1)

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image003.png)
 

## Auto ML setup (Exhibit 2-A) -Data Set

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image005.png)
    
# ML Job completed (Exhibit 2B)

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image007.png)

# Exhibit 2C Best Model

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image009.png)

# AppInsight Exhibit 3 A

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image011.png)
2022-06-10T22:15:16,191731800+00:00 - gunicorn/run 
2022-06-10T22:15:16,198623300+00:00 | gunicorn/run | 
2022-06-10T22:15:16,199986800+00:00 | gunicorn/run | ###############################################

# Exhibit 3B
 
![images](https://github.com/Vzard/Assignment-2/blob/main/images/image013.png)



## Swagger 

#  Exhibits 4.1

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image015.png)

# 4.2- Request 

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image017.png)

# 4.3 Response 

![images](https://github.com/Vzard/Assignment-2/blob/main/images/image019.png)



Exhibit 5 Consumer Model (endpoints.py)
        
                                                                                                                                                                 
Exhibit Set 6 :Pipeline 

 
# Pipeline endpoint
 

https://centralus.api.azureml.ms/pipelines/v1.0/subscriptions/16bc73b5-82be-47f2-b5ab-f2373344794c/resourceGroups/kalakkad-ddl/providers/Microsoft.MachineLearningServices/workspaces/epe-venkat-aiml/PipelineRuns/PipelineEndpointSubmit/Id/f08b580f-3d1d-4acb-9d72-abffdd118c4e
Bankmarketing dataset with AutoML module
 

 

Run widget steps
 
Scheduled run  


Next Steps
1.	Learn to do this operationalizing across more programs and complex programs
(image recognition , NLP)
2.	Employ Blob container storages for input and output
3.	Automated runs (scheduled run) say every week 9P the ML program will be called to 
Use new data
