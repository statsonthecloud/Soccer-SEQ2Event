# Seq2Event: Learning the Language of Soccer using Transformer-based Match Event Prediction
**An RNN/Transformer model architecture for predicting the next event given prior match events in soccer.**

<img width="897" alt="overview_graphic" src="https://user-images.githubusercontent.com/42736833/183763448-a0e5364f-b4dc-4088-815d-047a2ff76ddd.PNG">
<img width="881" alt="model_overview" src="https://user-images.githubusercontent.com/42736833/183763462-55251334-a952-420b-b959-38392e34ebcf.PNG">

Paper available at: [https://eprints.soton.ac.uk/458099/](https://eprints.soton.ac.uk/458099/)

Code developed initially as part of dissertation during MSc Data Science studies at the University of Southampton. Later written-up into paper and accepted at [KDD 2022](https://kdd.org/kdd2022/). Code associated with the latter tidied up, both sets of code provided (two notebooks each, four in total).

Code to import Wyscout open access match event dataset ([Nature article](https://www.nature.com/articles/s41597-019-0247-7)) is provided in the first notebook.  Code implementation of the proposed Soccer-Seq2Event model for match event prediction is provided in the second notebook.

Suggestions for future research:

* Analyse residuals further to characterise styles (it is not possible to very accurately predict the next action, but the aggregate view of what was expected vs what happened over a large sample is more telling).
* Apply to sports with stronger sequentiality, e.g. American football, rugby union, rugby league.
* Adapt to all-player tracking data.
* Perform match simulation.
