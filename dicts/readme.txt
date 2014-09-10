These are simple dictionaries that let you score terms you're looking 
for. They can be just plain text (one entry per line), or an entry
followed by 1-3. The idea was:

  0 = a non-offensive term (like slave) that may be a sign of trouble
  1 = a term that can go either way
  2 = a term that's definitely a problem

The code doesn't do stemming, so you'll probably want to throw in
plurals.

Sources:

 racist_words.txt:  a very short list, based on what I saw in Gut
 bad_words.txt: a list culled from a few random web pages
 kellegous.txt: the baggiest bag of words

