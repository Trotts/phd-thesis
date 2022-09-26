# Towards Automatic Photo-Identification of Cetaceans: A Fine-Grain, Few-Shot Problem in Marine Conservation
=================================================
> A working PhD thesis to be submitted to the Department of Electrical and Electronic Engineering, Newcastle University.

## Abstract:

Understanding the health of Earth's ecosystems is imperative for the future safeguarding of our planet and its inhabitants. One of the most common tools utilised by researchers to develop their understanding of an area's health are indicator species, organisms whose abundance or absence in a system reflects overall environmental health. Cetaceans (dolphins, whales, and porpoises) are excellent indicator species given their status as top predators, allowing for the monitoring of natural and anthropogenic risks to marine environments, such as offshore wind farm development or commercial fishing activity.

Cetacean monitoring is frequently performed using capture-recapture surveys, through which researchers record the presence of individual animals to produce population estimates. Photo-identification (photo-id) is one of the main non-invasive capture-recapture methods, whereby image data containing the animals' individually identifiable prominent markings is captured. Upon survey completion this data is curated to produce a photo-id catalogue, allowing for an abundance estimate to be generated and ecosystem health to be determined. Catalogues are updated over time as more surveys are undertaken, new individuals are encountered, and prominent markings change. Photo-id catalogue curation is traditionally performed manually and can be extremely labour and cost intensive, especially for large resident populations.

This thesis details a framework for automatic photo-id catalogue matching based on unprocessed field imagery via a pipeline of computer vision models. The development of a coarse-grain dorsal fin detector and the use of post-processing techniques to aid downstream identification is first examined. Next, the creation of a photo-id catalogue for cetaceans resident in the waters of Northumberland, UK, is outlined. This catalogue is then utilised to facilitate the development of a model capable of fine-grain, few-shot catalogue matching via latent space similarity, allowing for the flagging of potentially uncatalogued individuals. At all stages the robustness of the developed techniques to spatio-temporal changes is evaluated, including their generalisability to multiple cetacean species. The automation of photo-id data curation outlined in this thesis affords researchers more time to work on application of their data, for example to inform mitigation and policy change, rather than administration.

## Author: Cameron Trotter

## Supervisors: Nick Wright, A. Stephen McGough, Per Berggren


