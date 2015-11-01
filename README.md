# 1c.py
x1, y1 = map(float, raw_input().split())
x2, y2 = map(float, raw_input().split())
x3, y3 = map(float, raw_input().split())
a=abs((x1*(y2-y3)+x2*(y3-y1)+x3*(y1-y2)))
print format(a, '.6f')
