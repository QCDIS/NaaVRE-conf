# Getting started with NaaVRE

This is a quick start guide to use the NaaVRE.


https://user-images.githubusercontent.com/9680609/175039462-4a9db9a5-2b5e-4c13-be5e-7b5ee6283f89.mp4



## Log in to NaaVRE

Go to one of the deployed NaaVREs
Click on 'Sign in'

<img src="https://user-images.githubusercontent.com/9680609/162737176-40a0f99c-914a-430e-9722-d09b9e564fb5.png" width="50%" height="50%">

## Containerize notebook cells 


Open the notebook. Next on the left click on the LifeWatch panel.

<img src="https://user-images.githubusercontent.com/9680609/162744335-eea6a0bd-14d5-4ed4-b678-c01e3b71188e.png" width="50%" height="50%">

Select a cell.

<img src="https://user-images.githubusercontent.com/9680609/162744821-fffaa346-2aa9-4e8f-9894-d54bc1928096.png" width="50%" height="50%">

On the 'Inputs and Outputs' of the Component containerizer select the types and base image as shown below. When all the types are added 
click 'CREATE'

<img src="https://user-images.githubusercontent.com/9680609/175019281-9f5ac9c7-15fb-49ac-a62c-ef121d2b4949.png" width="50%" height="50%">

You can repeat the same for all the notebook's cell.

----

## NOTE 

When you click 'CREATE' you may get the following warning:

<img src="https://user-images.githubusercontent.com/9680609/175019467-2ea32a3c-b8b3-4db8-9533-15a1146d264c.png" width="50%" height="50%">

 To solve this go delete the base image and selected it again. 

----


## Construct Workflow 

Go to 'File->New Launcher'. On the bottom section 'LifeWatch VRE' click on the 'Experiment Manager'.

<img src="https://user-images.githubusercontent.com/9680609/175019723-84b7abd6-b23d-4b4e-acd5-b2f085ad01ce.png" width="50%" height="50%">

Open the catalog with the exported cells.

<img src="https://user-images.githubusercontent.com/9680609/175020246-25367cb6-90ae-44b1-9b73-1c863f6001bf.png" width="50%" height="50%">

Select the cell you want to add in your workpiece and clik 'ADD TO WORKSPACE'

<img src="https://user-images.githubusercontent.com/9680609/175020686-1b25f571-62f9-46c8-88b5-a74697286af5.png" width="50%" height="50%">

By dragging and dropping the cells on the left, construct the workflow shown bellow. 

## Execute the workflow

When the workflow completes its execution  it should look like this:

# Publications
[Zhao, Z., Koulouzis, S., Bianchi, R., Farshidi, S., Shi, Z., Xin, R., Wang, Y., Li, N., Shi, Y., Timmermans, J. and Kissling, W.D., 2022. Notebook‐as‐a‐VRE (NaaVRE): From private notebooks to a collaborative cloud virtual research environment. Software: Practice and Experience.](https://onlinelibrary.wiley.com/doi/epdf/10.1002/spe.3098)

