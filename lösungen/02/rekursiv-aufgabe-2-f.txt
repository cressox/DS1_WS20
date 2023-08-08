def f(n):
    if n == 1:
        return 0
    elif n == 2:
        return 0
    else:
        f = 0
        for i in range(n-1):
            f += i
        return f