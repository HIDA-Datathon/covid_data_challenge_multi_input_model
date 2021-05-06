# covid_data_challenge_multi_input_model
The implementation of the multi-input model for the COVID Data Challenge Hackathon

The idea was to design a model that could take in both clinical data and CXR (chest xray) images and predict the severity of COVID ['MILD','SEVERE'].

The Dense121 pretrained model was used for the part of the model that takes the images.


## Future Work
I am really passionate about the idea of the multi-input model because it creates joint, end-to-end learning of both the clinical data and the images, instead of other approaches that use one or the other.

However, due to time, was not able to explore other ideas like:

* What to do when for a training instance, we have no information about the image, but only the clinical data and vice-versa? Like how to make the model learn even when one of the features (image or clinical data) is absent. I plan on experimenting with masking.

* My team at the hackathon (transcov) and I wanted to implement the attention mechanism. 

### Contact details
I will love any contribution.
My contact details are : chris.emezue@gmail.com
[Twitter](https://twitter.com/ChrisEmezue)
