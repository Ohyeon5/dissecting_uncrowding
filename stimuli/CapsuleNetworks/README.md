# How to train and test Capsule networks

1. Download the model: 

2. Place all the stimuli to '' directory

3. Place 'mongrel_list.txt' to '' directory

4. Run the model with '' command

5. Place mogrelized images to '' directory and run 'template_match.py' to get the model performance


Additional Notes (not formalize yet): 
- For 'TOPDOWN_RNN' networks, bottom_layer_shape has to be specified depends on the image size (line 475, in capser_model_fn.py), here we used 1408
