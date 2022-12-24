# HIA302 Individual Project
International Medical University, HIA302 - Health Data Collection and Preparation, Individual Project (Ming)\
The present repository has collected all required items and work done for the project.\
Project outputs are performed with Jupyter Notebook.
# General Information:
1. horse-colic.txt and horse-colic.names.txt contain background data necessary for project outputs.\
Of note, some labels are too long in character length to be transferred directly to dataset. Hence, those are selected and shortened for dataset usage, as listed below:
   - hospital number - hosp_no
   - rectal temperature - rect_temp
   - respiratory rate - resp_rate
   - temperature of extremities - ex_temp
   - peripheral pulse - pr_pulse
   - mucouc membranes - muc_mb
   - capillary refill time - crt
   - peristalsis - prss
   - abdominal distension - abd_dist
   - nasogastric tube - ns_tube
   - nasogastric reflux - ns_flux
   - nasogastric reflux PH - ns_flux_PH
   - rectal examination (feces) - rect_exF
   - packed cell volume - pcv
   - total protein - tp
   - abdominocentesis appearance - abd_app
   - abdominocentesis total protein - abd_tp
   - surgical lesion - les_surg
   - site of lesion - les_site
   - type of lesion - les_type
   - subtype of lesion - les_sType
   - specific code for lesion - les_code

2. There are a total of 4 csv files:
   - horse-colic-one.csv - converted from horse-colic.txt with first method
   - horse-colic-two.csv - converted from horse-colic.txt with second method
   - horse-colic-with-NaN.csv - dataset with NaN values replaced from '?'
   - horse-colic-with-title.csv - dataset with established shortened column names

3. Question A-J.ipynb and Question K-L.ipynb contain outputs and answers in response to Part 2.
