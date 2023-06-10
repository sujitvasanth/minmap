# Minmap
platform agnostic javascript mind-mapping https://minmap.vercel.app/

I wanted to create a minmapping app that will run on windows, ubuntu, ios and android without any alteration. I asked chat GPT which suggested using React framework but I wanted to do it natively so went with plain javascript. Its my furst time building a javascript gui,

The existing mobile minmapping apps for android are really distracting as they insist on overlaying an input window over your mindmap. (see simplemind etc) I previously spoke to the devs at simplemind that said it was impossible to fix (QED!). I asked chatGPT how to fix this and it suggested a hidden input window and this works a treat. Had to implement some workarounds to keep the android keyboard from hiding.

![Screenshot from 2023-06-10 19-11-44](https://github.com/sujitvasanth/minmap/assets/18464444/babc86f4-211a-43c1-b493-1ab0799b0eff)

It can be accessed as a webapp at https://minmap.vercel.app/
works on ios, android, windows, mac, linux
