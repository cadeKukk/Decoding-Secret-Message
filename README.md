# Decoding a Secret Message

 Initial test is set up with example grid:

F
0	█	0
0	█	1
0	█	2
1	▀	1
1	▀	2
2	▀	1
2	▀	2
3	▀	2

Using this layout, we could also read in another letter like H

H
0	█	0
0	█	1
0	█	2
1	▀	2
2	▀	2
3	▀	2
1	▀	1
2	▀	1

The secret message is 
████████░     ████████░   ██████████░    ███████░  ██░           ███░ ███░    ███░ ██░     ██░
██░     ██░ ███░     ███░ ██░          ███░    ██░ ███░   ███░   ██░    ██░  ██░   ██░     ██░
██░     ██░ ██░       ██░ ██░         ███░          ██░  █████░ ███░     ██░██░    ██░     ██░
████████░   ██░       ██░ ████████░   ██░           ███░ ██░██░ ██░       ███░     ██████████░
██░     ██░ ██░       ██░ ██░         ███░           ██░██░ ██░██░       ██░██░    ██░     ██░
██░     ██░ ███░     ███░ ██░          ███░    ██░   ████░   ████░      ██░  ██░   ██░     ██░
████████░     ████████░   ██████████░    ███████░     ██░     ██░     ███░    ███░ ██░     ██░

You can check the code and make sure that everything functions correctly after installing the dependencies as shown.
And running the command:

python3 grid_printer.py
