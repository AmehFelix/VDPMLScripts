# VDPMLScripts
The Python Scripts used to develop the ML algorithms used in the VDP Platform
### WebApp - MLP
The WebApp side of the pipeline. This model is the final classifier that works with our WebApp. It assigns a rating, in our case it assigns a vehicle speed rating, and then works with our webapp to create an event report consisting of this rating along with all other relevant info, such as the datapoints that triggered the event, and the vehicle info.

Also added the extra files used for pre-processing as well as the mock data used to test this pipeline
