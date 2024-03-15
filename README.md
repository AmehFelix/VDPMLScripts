# VDPMLScripts
The Python Scripts used to develop the ML algorithms used in the VDP Platform
### WebApp - MLP
The WebApp side of the pipeline. This model is the final classifier that works with our WebApp. It assigns a rating, in our case it assigns a vehicle speed rating, and then works with our webapp to create an event report consisting of this rating along with all other relevant info, such as the datapoints that triggered the event, and the vehicle info.

### MobileApp - Logistic Regression algorithm
This LogReg algorithm takes csv data and produces a binary classification. It's used mostly as a flag and is step 1 in creating an event.

Also added are the extra files used for pre-processing as well as the mock data used to test this pipeline

## NOTE
Due to IP agreements, the full details of the platform and how the completed pipeline looks cannot be made public. So what I've pushed here is a snapshot of our ML pipeline while it was being developed
