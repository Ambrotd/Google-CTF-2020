## LOG-ME-IN write up by Ambrotd

We have a node express app with a login where the input is sent straight to the db

![892b3f85ac924daef30956ea40806ce9.png](../_resources/68a7f7504e1f474980c472dce7233c69.png)

This mean we can modify the username and password and send them as an array

![91a2a7704e95fd6bf1b39c205cf3669a.png](../_resources/a274f2f17b34493688ed7e007ead6fd2.png)

With this request we are logged in as administrator, but we need to be michelle to get the flag:

![e0a7593a59ee79fbdcfa5fada5290825.png](../_resources/47f04c4a69d241359eeb1966c8811fd4.png)
![26e06a6a84119014ba4a9d99a6a4b996.png](../_resources/60bd5face5c946dfa85d91367c9a0b83.png)

So we can send the username as michelle:

![818b78552a6098dc9778d8d8abb1857a.png](../_resources/98170f2c2f3f41a09e0a0c49226f3870.png)
![fffa44f0ba8bc411f0a40f3fa41d3926.png](../_resources/91a617833d14473e8645db2228fbf2b9.png)

And we got the flag:

![7fd3060dd0ac0336ddec407634eaa13f.png](../_resources/471e3512911d4bfd96a36770d1b218e0.png)
