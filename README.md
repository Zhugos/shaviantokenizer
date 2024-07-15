# shaviantokenizer
Using Shavian alphabet to improve tokenization for LLMs and SST

# Why and What is Shavian?
Shavian is something that came from George Bernard Shaw's dislike of the in-elegance of the hodge podge of borrowed letters that the English alphabet uses. In his will he set aside cash to create a more efficient english alphabet.

It turns out its very difficult to make humans change things once there is cultural momentum. From the QwERTY slow you down keyboard to the English alphabet, we are stuck with it for a while. We can still reap the rewards of Shavian if we use it to train LLMs.  My assertion is that its better phonemic orthography will help remove a layer of complexity of CH being a different sound and meaning than C and H separately (as an example).

# Team building
I am not an expert in the tokenization space, git, or python. I want to support open source.  I wanted to pitch this as a unique challenge to collaborate on with others and see if we could get the attention of LLM community. 

# Goals
1. Build a team discuss and determine that there is merit in exploring a phonemic english tokenizer (shawkenizer?)
2. Scope, design, build, and test the tokenizer
3. Data analytics to compare known tokenizers to our state of the art for Compression Ratio, Vocabulary Size, and OOV Rate.  At this point I don't think encoding/decoding speed should be a primary factor
4. Learn best practices and get to know the community.  New community members should be welcomed here.

# Approach
This doesn't need to even display the Shavian fonts, but would be nice homage if it would. The goal is to transform English language input and return the Shavian tokenization.  This would of course require an LLM to be completely retrained.  If has sufficently improved metrics, perhaps this efficiency would be enough to explore further.

# References
- [Shavian Alphabet - Wikipedia](https://en.m.wikipedia.org/wiki/Shavian_alphabet)
- [Prior efforts around Shavian - Dechifro.org](https://www.dechifro.org/shavian/shaw.py)
- [A web interface - Dechifro.org](https://dechifro.org/shavian/)
- [Andrej Karpathy on GPT Tokenization - Youtube](https://www.youtube.com/watch?v=zduSFxRajkE)
- [Andrej Karpathy on GPT Tokenization - Github](https://github.com/karpathy/minbpe/blob/master/exercise.md)
- [Shavian on Reddit](https://www.reddit.com/r/shavian)
- [Shavian-info - Github](https://github.com/Shavian-info)
- [ShavianTTS - Github](https://github.com/serif/Shavian_TTS)
