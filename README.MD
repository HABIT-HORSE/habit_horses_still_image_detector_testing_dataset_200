habit_horses_still_image_detector_testing_dataset_200

Developer: Dr Steve North - steve@stevenorth.com - 2017
 
This dataset was developed in 2017 for the HABIT (Horse Automated Behaviour Identification Tool) project [1] to provide test images of horses for computer vision and machine learning applications. 
 
The developer does not claim or assert any copyright over many of the images in this dataset and it is the user’s responsibility to obtain any required licences or clearances.
 
There are a total of 200 images, consisting of:
 
100 x positive images of horses (many horse breeds, ages, genders, viewpoints, scales, occluded, multiple instances of target object etc.): colour, differing pixel dimensions, JPG format in the directory: \posin\
 
The positive images were sourced from various places, including: the developer’s own images, Google Image searches, ImageNet [2], the Weizmann Horse Databases [3][4][5] and habit_horses_still_image_detector_training_dataset_10978 [6].

100 x negative images (not showing horses): colour, differing pixel dimensions, JPG format in the directory: \negin\
 
The negative images were sourced using a Python script (download_neg_image_by_link.py, written by the developer) to bulk download targeted image synsets (for example: ‘athletics’, ‘people’ etc.) from ImageNet [2].
The Python script also automatically renamed each image with a sequential number. 

[1] Steve North, Carol Hall, Amanda Roshier, and Clara Mancini, 2015. HABIT: Horse Automated Behaviour Identification Tool – A Position Paper. In Proceedings of the proceedings of ACI@BHCI (Animal Computer Interaction Workshop), British HCI 2015 (Lincoln, UK, 13 July 2015), BCS, UK.  http://dx.doi.org/10.13140/RG.2.1.3395.0881.
 
[2] Kai Li Li Fei-Fei, Olga Russakovsky, Jonathan Krause, Jia Deng, Alex Berg. ImageNet: an image dataset. 2017. Retrieved from: http://image-net.org/.

[3] E. Borenstein and S. Ullman, 2002. The Weizmann Horse Database.

[4] Jamie Shotton, 2007. Multiscale Weizmann Horse Detection Dataset.

[5] Jamie Shotton, 2007. Single-scale Weizmann Horse Detection Dataset.

[6] Steve North, 2017. habit_horses_still_image_detector_training_dataset_10978. v2.0. http://dx.doi.org/10.5281/zenodo.822849.

 

