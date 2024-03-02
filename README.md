# Indian-name-generator
Introducing our Indian Names Generator a precise tool that utilizes auto-regressive character-level models to create authentic Indian personal names. Explore a curated selection of traditional and contemporary names, reflecting the rich linguistic diversity of India. Whether for storytelling, gaming, or personal use, discover the perfect Indian name effortlessly.

## Current implementation follows a few key papers:
- Bigram (one character predicts the next one with a lookup table of counts)
- MLP, following Bengio et al. 2003
- CNN, following DeepMind WaveNet 2016 
- RNN, following Mikolov et al. 2010
- LSTM, following Graves et al. 2014
- GRU, following Kyunghyun Cho et al. 2014
- Transformer, following Vaswani et al. 2017

## Dataset
In names.txt file consist of 6485 Indian names comprising of both the genders.

Examples:
1. aabida
2. aachal
3. aadesh
4. aadil
5. aadish
6. aaditya
7. aaenab
8. aafreen
9. aafrin
10. aaftaab

## Conclusion
As training progresses the script will print some samples throughout and automatically load the best model so far and print more samples on demand. Here are some unique baby names that get eventually generated from current default settings.

Results:
Yathuramidhi
Sarujeshri
Kutmika
RomuneshDuman
Laathikana
Vendh
Shinchit
Kinthith
