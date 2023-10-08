<br> Use 0030 for better sound quality.

[Fix] HyperX Cloud II annoying high treble and little low bass
Today, I found how to fix my Cloud II horrible boosted treble and very little bass problem.

1. Download and install Equalizer APO from
https://sourceforge.net/p/equalizerapo/

2. During installation, select HyperX Cloud II from the playback devices available and hit OK.

3. Open Equalizer APO Configuration Editor from the start menu.

4. Inside 'config.txt' window, delete the three default presets. (click the red minuses)

5. Click the green plus to add this preset: (Graphic equalizers > 15-band graphic equalizer)

6. Click the little notepad button and copy-paste this config:
GraphicEQ: 25 1.8; 40 1.4; 63 1.4; 100 0.6; 160 0; 250 -3; 400 -4.6; 630 -4.6; 1000 -4.6; 1600 -4.6; 2500 -4.2; 4000 -4.6; 6300 -5.8; 10000 -7.8; 16000 -9

7. Turn off this preset and turn it on again.

That's all, your headset should sound way better than how it came from the box.

Source: https://steamcommunity.com/discussions/forum/1/1729828401679409289/
