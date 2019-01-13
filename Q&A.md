헷갈리기 쉬운 것

1. numpy max, maximum

    np.max(a,axis=0) 0과 비교하는 게 아니라 axis 0에서 max
    
    np.maximu(a,0) 0과 비교
    
    a = np.array([[0, -1, 6],
                 [2, -4, 1]])
                 
    print(np.max(a))
    
    print(np.max(a,0))
    
    print(np.maximum(a,0))   # 0은 브로드캐스팅됨


    6
    
    [ 2 -1  6]

    [[0 0 6]
    [2 0 1]]

