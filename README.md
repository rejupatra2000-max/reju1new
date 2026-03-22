n = 5  # number of rows (half diamond height)

# Upper half
for i in range(n):
    print(" " * (n - i - 1) + "* " * (i + 1))

# Lower half
for i in range(n - 1):
    print(" " * (i + 1) + "* " * (n - i - 1))
