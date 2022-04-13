#Given length(l) and index(i) to generate a Zadoff-Chu Sequence
def zadoff_chu(l ,i):
    q = 0
    l_0 = np.arange(0, l, 1)
    l_1 = np.arange(1, l + 1, 1)
    if l & 1:
        # print(l_0)
        y = np.exp(-1j*i*np.pi/l*np.multiply(l_0, (l_1+2*q)))
    else:
        y = np.exp(-1j*i*np.pi/l*(l_0**2))

    return y
