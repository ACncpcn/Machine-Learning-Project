# Machine Learning Project
### Music Classification

This repository contains our project for a Machine Learning class. 

The aim is to create a system that can find songs that are similar based on the audio parameters. Music services recommend music based on tags and what other users like. However, this doesn't help promote music that a user may like based on music preference because a song may not be popular. Furthermore, some tags are broad and may not fully describe a musical type. 

A set of songs will categorized by how similar to each other they sound to us (the group). A 4 means that two songs that are being compared are very similar in style. This does not mean they sound exactly the same but they would share a subgenre and fanbase. A 3 means that two songs are similar in general style. For example, heavy metal and slower classic rock use similar instruments and musical scales but at different tempos and levels of distortion. A 2 means that two songs are loosely related. An example might be a blues song and a R&B song. The R&B song may have elements of the blues but listening to these two songs by side there are more differences than similarities. A 1 means the only similarity two songs share may just be instruments used. A 0 would be little similarity, perhaps like a classical piano solo and a hip-hop bass and drum instrumental.

The general idea is to be able to first detect pitch or chord using a trained model. 
Then the pattern of notes played will be found for a song. The final step would be to match the similarity of the pattern of notes to an existing database of songs. 

Papers that have been published by Juan Bello, a professor at NYU Steinhardt, served as starting points on how to quantify musical qualities. The musical analysis tools that have been utilized in our program to extract musical features from songs come from the Librosa package.
