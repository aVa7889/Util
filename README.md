# Utility files
import utils

df = utils.get_data()

normalized_ratings = utils.get_normalized_data()

# Get the weights and bias tensors
W = utils.weights()

hb = utils.hidden_bias()

vb = utils.visible_bias()
