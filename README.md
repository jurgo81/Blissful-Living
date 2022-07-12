# Blissful-Living
# The product adoption file describes an app product adoption and produces a cadcad simulation. 
# However, the model is not realistic because it does not take population growth by opening up new locations into account. 
# I would like to add this via a state update function, but I don't know the code yet...all help is welcome!
# The file "test new location code" is my attempt to create a state update function that considers the new location population growth in a simpler cadcad model
# My code attempt can be seen at the state update function "s_new_location"
# What I basically would like to do is add 70k people to the the population every year after the first 2 years. 
# My initial thought was to add 'timestep (s)' as an argument, but I get errors and I don't know how to tie it all together in the partial state update blocks
