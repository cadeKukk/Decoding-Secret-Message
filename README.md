# Decoding a Secret Message

<pre> Initial test is set up with example grid:

<pre>F
<pre>0	█	0
<pre>0	█	1
<pre>0	█	2
<pre>1	▀	1
<pre>1	▀	2
<pre>2	▀	1
<pre>2	▀	2
<pre>3	▀	2

<pre>Using this layout, we could also read in another letter like H

<pre>H
<pre>0	█	0
<pre>0	█	1
<pre>0	█	2
<pre>1	▀	2
<pre>2	▀	2
<pre>3	▀	2
<pre>1	▀	1
<pre>2	▀	1

<pre>The secret message is 
<pre>████████░     ████████░   ██████████░    ███████░  ██░           ███░ ███░    ███░ ██░     ██░
<pre>██░     ██░ ███░     ███░ ██░          ███░    ██░ ███░   ███░   ██░    ██░  ██░   ██░     ██░
<pre>██░     ██░ ██░       ██░ ██░         ███░          ██░  █████░ ███░     ██░██░    ██░     ██░
<pre>████████░   ██░       ██░ ████████░   ██░           ███░ ██░██░ ██░       ███░     ██████████░
<pre>██░     ██░ ██░       ██░ ██░         ███░           ██░██░ ██░██░       ██░██░    ██░     ██░
<pre>██░     ██░ ███░     ███░ ██░          ███░    ██░   ████░   ████░      ██░  ██░   ██░     ██░
<pre>████████░     ████████░   ██████████░    ███████░     ██░     ██░     ███░    ███░ ██░     ██░

<pre>You can check the code and make sure that everything functions correctly after installing the dependencies as shown.
<pre>Running the command:

<pre>python3 grid_printer.py

