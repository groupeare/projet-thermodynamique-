# projet-thermodynamique-
def points_aleatoires(n):
    x1=[]
    for i in range(0,n):
        x1.append(np.random.random())
    y1=[]
    for i in range(0,n):
        y1.append(np.random.uniform())
    return x1,y1;

