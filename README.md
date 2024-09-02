# Diagonal
#Create a function that takes a tuple of tuples and returns a tuple containing the diagonal elements of the input


def get_diagonal(tup):
    
    diogonal_list = []
    
    for i in range (len(tup)):
        
        diogonal_list.append(tup[i][i])
        
    return tuple(diogonal_list)
