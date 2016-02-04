READ ME: 
- For the dataset Fishing, the training data for cv=j is Fishing[Fishing$fold !=j,] and the test data is Fishing[Fishing$fold == j,].
- For the travel mode daa set training data for cv = j is TravelMode data from 
	package AER with the fold_indicator!=j and the test data is that with fold_indicator ==j provided here.
	Only the individual id and fold_indicator is provided here. 
- For simulation study - I (one that uses modified function from Friedman 1991), there is a training data ("traindata.csv")
	with attribute 'fold' indicating which fold it is used for. Same for the test data (testdata.csv)
- Waveform recognition. Same as preceeding bullet. 

	