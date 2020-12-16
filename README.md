# mpl_analysis

Please note the following points of interest below regarding this assignment:

1. When running the notebook, initially there is an input data section to enter values for desired Drug Regimen and Mice ID.
	a. We are asked to hardcode regimen "Capomulin" and to also pre-select a mice id, selected "s185". 
	b. This isn't part of the requirements but implemented to expand on the study for other regimens and mice id (ie. Ramicane, d251).
 
2. The last tumor volume data is taken one step further to isolate for only the mice that have the last timepoint of 45.
	a. This is to set timepoint as a control variable for making an equal comparison in the study.
	b. It wasn't explicitly stated in the requirement, but interpreted this way from an analytical point of view.

3. The notebook contains an additional method of calculating the tumor volume by growth rate (delta) instead.
	b. Delta is calculated by taking the intial tumor volume and stubtracting it from the last timepoint
	a. This isn't part of the assignment but added for educational purposes.
	c. It has been commented out to preserve it's code.

4. All charts and graphs are stored in images folder

5. Report is available in the analysis folder

