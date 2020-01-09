# CHIIR 2020
Supplementary materials used in analysis for CHIIR 2020 publication "Towards Search Strategies for Better Privacy and Information"




# Citing work and datasets
- Annotations can be found in [this folder](https://github.com/stevenzim/chiir-2020/tree/master/Annotations)
    - *URL_TRACKER_DATA.csv* contains the number of 3rd party trackers for each URL.  This dataset also includes where the tracking data was retreived.   Details for WhoTracks.me dataset are described further below.
    - *annotations_metadata.csv* contains a unique id, URL visited, the search task number (as provided by Pogacar et al. ITCIR 2017), Cochrane medical question, correct answer to question
    - *annotations_new.csv* contains the annotations from each annotator and the final annotation after each annotator worked together to come to agreement.   The ID in here matches the ID in *URL_TRACKER_DATA.csv*
    - *annotations_against_previous_studies.csv* contains annotations against previous studies (Pogacard et al. ITCIR 2017 and Zimmerman et al. CHIIR 2019).  File contains same fields as *annotations_new.csv*  plus the annotation from previous studies.  This data was used to test agreement between annotators and previous research.
- For our publication and usage of the annotations, please use the following bibtex entry for citation.

```
@inproceedings{Zimmerman2020Towards,
 author = {Zimmerman, Steven and Thorpe, Alistair and Chamberlain, Jon and Kruschwitz, Udo},
 title = {Towards Search Strategies for Better Privacy and Information},
 booktitle = {Proceedings of the 2020 Conference on Human Information Interaction and Retrieval},
 series = {CHIIR '20},
 year = {2020},
 location = {Vancouver, BC, Canada},
 pages = {TBD}
} 
```

## For the [WhoTracks.me](https://whotracks.me/) 10,000 website 3rd party tracking dataset.
- Data used for analysis can be found in [this folder](https://github.com/stevenzim/chiir-2020/tree/master/WhoTracks.me)
- [WhoTracks.me](https://whotracks.me/) is collaborative project with teams at Cliqz and Ghostery. 
- This dataset was made available for our research via an endpoint provided by Cliqz and Ghostery.
- Please cite the paper ["WhoTracks.Me: Shedding light on the opaque world of online tracking"](https://arxiv.org/abs/1804.08959).
- Usage of this dataset for future research is allowed under the following license:  

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This dataset is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a> and is attributed to <a  href="https://whotracks.me/">https://whotracks.me/</a>.



