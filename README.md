The platform AI contains information from 100 companies in its public knowledge base. Of these, 30 companies have PDG data, while 70 companies have data from other types of sensors. 
Among the 30 companies with PDG data, 3 have models in place, 
and among the 70 companies with other sensor data, 1 has a model for monitoring compressors. To support these 3 companies with PDG models, separate local knowledge bases have been created for each. 
For simplicity in the experiment, Company A's private knowledge base is derived from the paper "A New Automated Workflow for Well Monitoring Using Permanent Pressure and Rate Measurements",
Company B's private knowledge base is based on "Pressure Transient Analysis as an Element of Permanent Reservoir Monitoring",
and Company C's private knowledge base comes from "Advancing Deep Learn-ing to Improve Upstream Petroleum Monitoring" .
The synthetic data supports the platform's fundamental operational processes.

To run the data-sharing-platform with AI, you need to 
1. install the packages in the requirements.txt
2. add API from LLMs in the file of "oilgas.py" 
3. streamlit run oilgas.py
