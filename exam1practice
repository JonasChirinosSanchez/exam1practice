from string import whitespace


def fourbonacci(n):

    if n == 1:
        return 1
    elif n == 2:
        return 4
    elif n == 3:
        return 7
    elif n == 4:
        return 8

    else:
        a, b, c, d = 1, 4, 7, 8
        for i in range(4, n):
            new_val = (4 * a) + (3 * b) + (2 * c) + (1 * d)
            a = b
            b = c
            c = d
            d = new_val
        return new_val


def odd_squares(num_sq):
    n = 1
    while num_sq > 0:
        new_square = n**2

        if not(new_square % 2 == 0): #is it odd?
            print(new_square)
        else:
            num_sq += 1

        num_sq -= 1
        n += 1


def diamond(n):
    for i in range(n):
        space_count = abs(i - n // 2)
        for _ in range(space_count):
            print(" ", end="")
        for j in range(n - space_count * 2):
            print(j+1, end="")
        print()
