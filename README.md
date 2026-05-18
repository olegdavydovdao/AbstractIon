# AbstractIon
I'm making research on the JEPA (Joint-Embedding Predictive Architecture) neural net, but with specific processing of actions. It converts input/action/output into representation vectors with the same number of dimensions, predicts at that level in a self-supervised manner, and ignores unimportant/unpredictable data.  
The JEPA-like neural net will outperform an LLM in:
1) System 2 reasoning, getting new insights on unknown data, and inference by search.
2) Agentic hierarchical planning of actions and their consequences in the real world.
3) Training and inference efficiency use less computation/data.
4) Learning representations of real world complex multimodality data.
5) Physical intuition and understanding the real world.

## Why this idea?
- I think vector representation that fits a particular action is primary to predicting the future, rather than the action itself (millisecond muscle movement). Therefore, the search for a possible action must take place within the space of the action's representation. Representation of all data must have the same number of dimensions for combined and learned action representations and effective training with good backpropagation gradient flow.  
- I understand that next token prediction is very limited, but what's even worse is it mathematically says that the model for predicting only needs part (1 token) of a more complex representation of composite data that does not exist in LLM but should exist in theory.  
- I think that the general idea of rising to an abstract level, getting better representations of composite data, and using it to predict the future is key to developing more powerful AI in both the physical and digital worlds.  
## First principle/intuition behind the idea
<img width="1920" height="851" alt="github first principle screenshot" src="https://github.com/user-attachments/assets/8f268450-8d2c-4bba-bf08-99b418aa01f0" />

I have a [video](./first_principle_video.mp4) that explains this image.

## State of the project
There is only an idea that exists right now, there is no code.  
I'm trying to figure out how to build this architecture.  
ongoing...
