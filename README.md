# AudioSR-Colab-Fork


*notebook will be released shortly...*



Colab adaptation of AudioSR, with some tweaks:
- added a chunking feature to process input of any length
- added stereo handling, stereo input channels will be splitted and processed independantly (dual mono) and then reconstructed as stereo audio.
- added overlap feature to smooth the transitions between chunks (don't use high values because AudioSR is not 100% phase accurate and this will create weird phase cancellations accross the overlapping regions)

---
Adaptation & tweaks by [jarredou](https://https://github.com/jarredou/)

Original work [AudioSR: Versatile Audio Super-resolution at Scale](https://github.com/haoheliu/versatile_audio_super_resolution) by Haohe Liu, Ke Chen, Qiao Tian, Wenwu Wang, Mark D. Plumbley


