# Tuples-Hash-
if __name__ == '__main__':
    n = int(raw_input())
    integer_list = map(int, raw_input().split())
    a=tuple(integer_list)
    t=hash(a)
    print(t)
