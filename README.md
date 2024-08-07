# GraphRAG
By following up the course of graph rag on deeplearning.ai, we build our own graph rag with Neo4j 

## Online course on deeplearning.ai   
- https://www.deeplearning.ai/short-courses/knowledge-graphs-rag/

## Before the scripts, prepare Neo4j Database   
- In this case, I use Neo4j cloud instance to prepare our data   
- Try to create a new free instance for yourself from the website:
  https://neo4j.com/cloud/platform/aura-graph-database/?ref=nav-get-started-cta   
- Also, you can create Neo4j server on your computer by following the steps of installation:
  https://blog.csdn.net/Chasingthewinds/article/details/133235138

## Script Description   
- SR2KG_createNodes.ipynb: Try to teach you how to create nodes by steps of `Extraction` and `Enhance`
- SR2KG_createRelationships.ipynb: Try to teach you how to create relationships by step of `Expand`. We also reconstruct stuff prompt and compare the result between window and windowless retriever.
- Note that you need to prepare your own confi file such as `.env.studiomac` where Azure Resource and Neo4j Connection Settings are utilized in this case
