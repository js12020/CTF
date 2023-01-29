
http://mercury.picoctf.net:27393/

picoCTF{th4ts_4_l0t_0f_pl4c3s_2_lO0k_d375c750}

There were 5 parts to the flag that you had to hunt down.

Going to the website, inspecing in the broswer

html -> part 1  <!-- Here's the first part of the flag: picoCTF{t -->

mycss.css  -> part 2    h4ts_4_l0

myjs.js - didn't have anything except for a hint

/* How can I keep Google from indexing my website? */

Went to robots.txt to get Part 3
http://mercury.picoctf.net:27393/robots.txt


User-agent: *
Disallow: /index.html
# Part 3: t_0f_pl4c
# I think this is an apache server... can you Access the next flag?


Apache server -> .htaccess
Went to .htaccss to get Part 4
http://mercury.picoctf.net:27393/.htaccess

# Part 4: 3s_2_lO0k
# I love making websites on my Mac, I can Store a lot of information there.


Store -> .DS_Store
http://mercury.picoctf.net:27393/.DS_Store
Congrats! You completed the scavenger hunt. Part 5: _d375c750}


