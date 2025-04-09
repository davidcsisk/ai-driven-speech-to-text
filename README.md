# ai-driven-speech-to-text
Examples and test results from using AI models to transcribe speech to text

There are now two examples...one python cli app that uses OpenAI's Whisper model (you'll need an account with payment means already configured), and a newer example using the free open-source locally-running Vosk model.  Whisper seems to work the best, but the 2nd smallest Vosk model did quite well based on simply spot-checking some sections.  The larger Vosk models would likely perform even better...you'll just need more computing resources to use those. 

These tests were conducted 4 chapters of a free public-domain audio book from librivox.org called "A Popular History of the Art of Music" by WSB Mathews.

URL: https://librivox.org/a-popular-history-of-the-art-of-music-by-w-s-b-mathews/
- 00 - PREFACE AND INTRODUCTION	Tony Oliva  00:21:15
- 01 - MUSIC AMONG THE ANCIENT EGYPTIANS	Tony Oliva   00:17:16
- 02 - MUSIC AMONG THE HEBREWS AND ASSYRIANS.	Tony Oliva   00:11:24
- 03 - MUSIC AMONG THE ANCIENT GREEKS.	Tony Oliva    00:46:07

File list:
  
| Size | Name |
| ---- | ---- |
| 20416640 | popularhistoryoftheartofmusic_00_mathews.mp3 |
| 16580736 | popularhistoryoftheartofmusic_01_mathews.mp3 |
| 10949672 | popularhistoryoftheartofmusic_02_mathews.mp3 |
| 19369028 | popularhistoryoftheartofmusic_03_mathews_reduced-sample-rate_16KHz.mp3 | 
