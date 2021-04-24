Parkinson's Disease Prediction


	Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain. It manifests itself through a deterioration of movement, including the presence of tremors and stiffness.

	There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.

	Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. 

	Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. 

	Here machine learning algorithms are applied to a voice recording dataset to accurately diagnosis PD, whcich would be an effective screening step prior to an appointment with a clinician.

	Bascially, there are 24 number of columns to identify the PD which also contains a target column, and the target column is categorical in nature. 
	
	Here, after performing basic EDA to visualize the data, splitting has been done and subsequently the the records were injected to the ML models through various scaling processes like Standard Scaling, MinMax Scaling, etc. 
 

	Various Ensemble models and stacking classifier models were considered for predicting the target column along with ML models, and the significance of the column has been decided based on the VIF.