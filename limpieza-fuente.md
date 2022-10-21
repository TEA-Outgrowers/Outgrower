# Proyecto Outgrower 
import pandas as pd
from matplotlib import pyplot as plt
germ = pd.read_csv("germination.csv") 
germ

# agrupación rice
rice = germ[germ.species == "rice"]
rice 

# agrupación mungbean
mungbean = germ[germ.species == "mungbean"]
mungbean

# agrupación wheat 


