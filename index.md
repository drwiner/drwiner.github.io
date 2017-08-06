## David R. Winer

## PhD Candidate, University of Utah

### About Me

I'm a PhD candidate in Computer Science at the University of Utah. I'm a member of the [_Liquid Narrative Research Group_](http://liquidnarrative.cs.utah.edu/).

### My Work

My research areas are in _Artificial Intelligence_ _(AI)_ including _automated planning_, _narrative intelligence_, _information extraction_, _natural language generation_, and _cinematics_. There is a wealth of information in narratives such as in text and films, and my work uses techniques from AI, as well as theories from narratology and cognitive science, to create tools for extracting, understanding, and generating narratives.

Automatically modeling and generating narratives is a challenge. Narratives are...
- _bipartite_

Narratologists frequently distinguish story (e.g., plot, _fabula_) from discourse (i.e., the communicative plan for telling a story). These two parts interact and are coordinated, yet are difficult to model and generate in an integrated way.

- _hierarchcial_

Fabula is hierarchical: the event of flying from Raleigh to Salt Lake City decomposes into sub-events such as buying tickets, getting to the airport, etc. Discourse is also hierarchical; a film is composed of scenes, which are themselves composed of shot sequences and shots. 

- _goal-oriented_

Characters in stories have goals and form plans to achieve those goals. Storytellers also have goals and form plans for storytelling by modeling the sequence of beliefs and experiences of the audience. Storytellers describe events in a certain way, or edit a scene in a certain way, as part of a master plan.

The secret to characterizing these aspects of narrative is **BiPOCL**, _a bipartite, hierarchical plan-based model and algorithm_. BiPOCL stands for Bipartite Partial Order Causal-Link and uses decompositional plan-space planning to solve planning problems with hierarchical knowledge. The resulting BiPOCL data structure can be used for generating narratives. I'm currently working on a planning problem for cinematics, where the output would be used to automatically generate short film segments with the Unity Game Engine. The fabula side of the model drives character animations and movements in a virtual environment, and the discourse side provides camera instructions for a virtual camera. The movies may not be any good, but they will be useful artifacts for testing BiPOCL with human subjects.

Where does the knowledge used by BiPOCL come from? It comes from real narratives, and I have two projects focused on extracting cinematic and storytelling knowledge. I've been working with cognitive psychologists to assemble a shot-by-shot annotated corpus of similar scenes using a specialized cinematic annotation scheme (see [westernfilmcorpus](https://www.github.com/drwiner/westernduelsfilmcorpus)). I'm using Conditional Random Fields, a machine learning technique for learning sequential patterns, to learn and predict what kind of camera shot to use to film a pattern of events. Also, I have an ongoing project called [Screenpy](https://www.github.com/drwiner/screenpy) with is a tool for parsing raw screenplay text. Screenplays are unusual for narrative text because they have a structured discourse information in the shot headings. I've assembled a database of the parser's output on over a 1000 screenplays from the [IMSDb corpus](imsdb.com). Currently, I'm working on processing the text to understand what actions characters are performing in each section. 



### Contact


drwiner@cs.utah.edu
