# Towards Automatic Photo-Identification of Cetaceans: A Fine-Grained, Few-Shot Problem in Marine Ecology

My PhD thesis submitted to the Department of Electrical and Electronic Engineering, Newcastle University. Awarded June 2023.

This repo is based heavily on the PhD thesis template from [kks32](https://github.com/kks32/phd-thesis-template).

## Abstract:

Understanding the health of Earth's ecosystems is imperative for the future safeguarding of our planet and its inhabitants. One of the most common tools utilised by researchers to develop their understanding of an area's health is indicator species, organisms whose abundance or absence in a system reflects overall environmental health. Cetaceans such as dolphins, porpoises, and odontocetes (toothed whales) are excellent indicator species given their status as top predators, allowing for the monitoring of risks to marine environments, such as offshore wind farm development or commercial fishing activity.

Cetacean monitoring is frequently performed using capture-recapture surveys, through which researchers record the presence of individual animals to produce population estimates. Photo-identification (photo-id) is one of the main non-invasive capture-recapture methods, whereby image data containing the animals' individually identifiable prominent markings are captured. Upon survey completion these data are curated to produce a photo-id catalogue, allowing for an abundance estimate to be generated and ecosystem health to be determined. Catalogues are updated over time as more surveys are undertaken, new individuals are encountered, and prominent markings change. Photo-id catalogue curation is traditionally performed manually and can be extremely labour and cost intensive, especially for large resident populations.

This thesis details a framework for automatic photo-id catalogue matching based on unprocessed field imagery via a pipeline of computer vision models. The creation of a photo-id catalogue containing cetaceans resident in the waters of Northumberland, UK, is first outlined. The development of a coarse-grained dorsal fin detector and the use of post-processing techniques to aid downstream identification is then examined. Next, the created photo-id catalogue is utilised to facilitate the development of a model capable of fine-grained, few-shot catalogue matching via latent space similarity, allowing for the flagging of potentially uncatalogued individuals. At all stages, the developed techniques' robustness to spatio-temporal changes is evaluated, including their generalisability to multiple cetacean species. The automation of photo-id data curation outlined in this thesis affords researchers more time to work on application of their data, for example to inform mitigation and policy change, rather than administration.

## Author: 

Cameron Trotter

## Supervisors: 

Nick Wright, A. Stephen McGough, Per Berggren


