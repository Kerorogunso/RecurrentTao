# RecurrentTao

Advances in recurrent neural nets has enhanced the ability for machines to construct sentences by learning from reference material. This notebook applies these techniques on an english translation of Tao Te Ching - the famous philosophical text for Taoism. The book consists of 81 chapters of 5,000 characters in the native language, is much longer in the english variant and less gramatically correct due to the direct translation of the text.

We explore a number of popular advances in the RNN space and how they work on sequence generation:
- Simple RNN: The basic RNN unit where hidden states receive information from observations and outputs from the previous hidden state
- Long Short Term Memory (LSTM): LSTM units consist of cells, input gates, output gates and forget gates. Storing information from many sequences ago and removing text which is no longer relevant addresses the long term dependencies of sequential data.
- Gated Recurrent Units (GRU): An RNN unit that controls the flow of information using reset and update gates. Filtering information and storing it into the next states has shown to help resolve the vanishing gradient problem. GRU's have been reported to be effective on small datasets.

![](https://github.com/Kerorogunso/RecurrentTao/blob/master/tao.jpg "Tao Te Ching"){:height="700px" width="400px"}
