# projet-thermodynamique-
def points_aleatoires(n):
    x1=[]
    for i in range(0,n):
        x1.append(np.random.random())
    y1=[]
    for i in range(0,n):
        y1.append(np.random.uniform())
    return x1,y1;

def positionsuivante(X1,Y1,delta):
    X2=[]
    Y2=[]
    for x in X1:
        X2.append(x+delta*(np.random.random()-0.5))
    for y in Y1:
        Y2.append(y+delta*(np.random.random()-0.5))
    return X2,Y2
