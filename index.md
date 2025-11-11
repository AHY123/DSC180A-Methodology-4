Andrew Hudson Yang 
any012@ucsd.edu

**Section:** A15: How Effective aretransformer based graph learning models?
**Mentors:** Yusu Wang & Gal Mishne

---

### Project Brainstorming

**What is the most interesting topic covered in your domain this quarter?**
One of the most interesting topics is the competing philosophy for overcoming the limitations of classical Message Passing Neural Networks (MPNNs). I like the debate between building a complex, specialized model for graphical data versus finding a clever way to reformat the data for a potentialy more powerful, general-purpose model.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**
I propose a hierarchical Transformer for Knowledge Graphs (not completely original), which first uses a local LLM to encode the rich text of each node into semantic embeddings. A second, global Transformer will then learn the graph's relational structure by processing the sequence of these node embeddings.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**
My Q1 project compared models on purely structural tasks like cycle checking and ZINC. I would change this by adding a text-rich graph dataset to test how well the "fancy" (GPS) and "simple" (AutoGraph) models can integrate complex node features, not just graph topology.

**What other techniques would you be interested in using in your project?**
I am interested in using transformer finetuning methods such as CLIP or RL to train the hierarchical model to align the text-based node representations with the graph-based structural representations. I would also like to test this final model on a practical downstream task, such as link prediction, to infer missing relationships in the knowledge graph.