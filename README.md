# Centering Community in Language Preservation - Building Speech Transcription for Khroskyabs

## Abstract
Automatic Speech Recognition can be a valuable tool for work in preserving Endangered Languages. Members of a village on the Tibetan Plateau where the endangered language Khroskyabs is spoken have been working with a linguist from their community on language preservation efforts. Machine Learning and Artificial Intelligence tools can support language preservation. When the preservation work is done by those outside the community, they must use the technology with great care to maintain the respect that the community and language deserve. In this project, we demonstrate an example of how to prioritize an ethical framework to allow linguists to accomplish language preservation goals.

## Introduction
Khroskyabs /ʈʂʰo scæv/ is a language spoken by approximately 6,000 to 10,000 Tibetans on the Tibetan Plateau. It is a highly agglutinative and predominantly oral language with significant lexical borrowing from both Amdo Tibetan and Sichuan Mandarin (Taylor-Adams & Lhawa, 2021). These characteristics make Khroskyabs vulnerable to linguistic erosion, underscoring the importance of developing tools to aid in its preservation and revitalization.

## Background and Methods
Community members have been leading efforts to preserve Khroskyabs. A team member has been making audio recordings for over 15 years during their career as a linguist.
A popular preservation method is transcription of audio recordings. Even for a linguist familiar with Khroskyabs, it can take up to an hour to transcribe one minute of recorded audio.
We chose to support the community by working to develop an Automatic Speech Recognition (ASR) System. An ASR system uses Artificial Intelligence or Machine Learning to process human speech into readable text. An efficient ASR System can significantly speed up the transcription process, leaving more time for linguists to spend with the community. We used Praat (Boersma & Weenink, n.d.) for human text alignment, Montreal Forced Aligner (McAuliffe et al., 2017) for Machine Learning text alignment, and Elpis (Foley et al., 2018) for automatic transcription.

## Centering Community
Using machine learning and AI to preserve the Khroskyabs language is a new and relatively unexplored area. There is no published material on how to manage the process for Khroskyabs. In this project, we demonstrate how implementing ethical AI principles at the conception stage of an ASR project can provide a structure to continue to guide the team during the Construction, Use, and Evaluation phases of the project. 
We followed the Ethical Principles for Language Resources and Language Technology (Kamocki & Witt, 2022) taxonomy prioritizing “Privacy, Property, Equality, Transparency and Freedom.” Establishing clear guidelines and obtaining team agreement allowed us to produce quality work that aligned with our personal and academic values while respecting the wishes and contributions from the community.
All software used in our workflow was run locally by team members or on a departmental server, allowing us to retain full data security and maintain data privacy. All computer-generated outputs were distinguished from human-made analyses, and we transparently identified the data source. Our team member personally informs villagers about the progress of preservation work, thereby fostering a direct and meaningful connection with the community and working with them as equal partners.
The audio data is on loan to the team and remains the property of the original speakers. They are free to withdraw their consent, and all their data will be removed from the model.
Our model’s word error rate of around 70% is comparable to the expected word error rate for speech recognition models with comparable amounts of training data (Slam et. al, 2023). 

## Conclusion
We were able to achieve creditable ASR results in this low-data setting, while adhering to the ethical goals of Privacy, Property, Equality, Transparency, and Freedom in supporting language preservation efforts for Khroskyabs.

## References
Boersma, P., & Weenink, D. (n.d.). Praat: doing Phonetics by Computer [Computer program] Version 6.4.12. Phonetic Sciences. Retrieved May 02, 2024, from https://www.fon.hum.uva.nl/praat

Foley, B., Arnold, J., Coto-Solano, R., Durantin, G., Ellison, T. M., van Esch, D., Heath, S., Kratochvíl, F., Maxwell-Smith, Z., Nash, D., Olsson, O., Richards, M., San, N., Stoakes, H., Thieberger, N., & Wiles, J. (2018). Building Speech Recognition Systems for Language Documentation: The CoEDL Endangered Language Pipeline and Inference System (Elpis v 1.0.6). The 6th Intl. Workshop on Spoken Language Technologies for Under-Resourced Languages (SLTU), 200-204. https://www.isca-archive.org/sltu_2018/foley18_sltu.pdf

Kamocki, P., & Witt, A. (2022). Ethical Issues in Language Resources and Language Technology – Tentative Categorisation. European Language Resources Association, Proceedings of the Thirteenth Language Resources and Evaluation Conference, 559-563. Retrieved May 29, 2024, from https://aclanthology.org/2022.lrec-1.59

McAuliffe, Michael, Michaela Socolof, Elias Stengel-Eskin, Sarah Mihuc, Michael Wagner, and Morgan Sonderegger (2017). Montreal Forced Aligner [Computer program]. Version 1.0.0, retrieved 05 May 2017 from http://montrealcorpustools.github.io/Montreal-Forced-Aligner/

Slam W, Li Y, Urouvas N. Frontier Research on Low-Resource Speech Recognition Technology. Sensors (Basel). 2023 Nov 10;23(22):9096. doi: 10.3390/s23229096. PMID: 38005483; PMCID: PMC10674334.

Taylor-Adams, A., & Lhawa Y. (2020, 12 31). A Sketch Grammar of Siyuewu Khroskyabs. Himalayan Linguistics, (Archives and Field Reports). https://doi.org/10.5070/H919246822
