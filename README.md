# CNN_feature_visualization_by_tensorflow

This fold is about a project doing feature visualization. 

Often we have to some extent treated neural networks as black box function approximators, not interrogating what particular features various layers represent. Feature visualization attempts to understand what feature maps neural networks use. In this project, I trained a neural network to solve a particular classification problem (SVHN & MNIST). Given those parameters, I tried figuring out what input image would drive a particular unit’s activation the most? To be more specific, I fixed the learned parameters and treated the input image itself as an optimization variable, and then optimize for the image that maximally excites a particular unit. I then optimized bu regularization to find images more recognizable that excited different layers of the network. The motivation and large referrence for this project is this recent review publication: https://distill.pub/2017/feature-visualization/.

'GR5242_final_project_yh2875_final_ver.ipynb' records the whole project from introduction, experiments to summary, it cleanly displays code, results and plots.

'GR5242_final_project_yh2875_final_ver.html' is the corresponding knitted version to 'GR5242_final_project_yh2875_final_ver.ipynb'

'project_written_report_v2.pdf' contains the written part and some plots that are extracted from 'GR5242_final_project_yh2875_final_ver.ipynb', it excludes code part so as to look more clear.

'fig' fold contains all the figures that the report inserted, they are mainly produced by running the code and then save there.
