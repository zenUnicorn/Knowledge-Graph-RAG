## Why Knowledge Graphs Are Catching On

That’s where knowledge graphs come in. Unlike vectors, graphs give you explicit relationships between entities. A product has a supplier. A supplier serves a location. A warehouse stores certain categories. And once that structure exists, querying becomes way more powerful and intuitive.

Here’s what makes knowledge graphs so useful in AI-powered apps:

- **Structured retrieval**: You can write precise queries instead of relying on fuzzy matches.
- **Explainability**: You can show exactly why a result was retrieved.
- **Domain alignment**: Graphs reflect real-world relationships, just like your business rules do.

![KG Image](https://lh7-rt.googleusercontent.com/docsz/AD_4nXebTSWwC1IrgIU8dkccq9lAUPrt-S7eaTz12oAiyTt4jLmytGTuC8HgbpI_pf5lvWnNLLxYurrIQA_RnznCaNobLpEvkW9_Y3vAUI9IScE44qaBv50XiE_bt5Aho9qoEB9lUI1duw?key=lqZSFvuWmXmvGZnyQ5f1lQ)

## Goals

- Load supply chain data (product catalogs, suppliers, purchase orders)
- Convert unstructured descriptions into structured relationships
- Build a knowledge graph using  [Neo4j](https://neo4j.com/)
- Query the graph with user questions like “Which suppliers in Europe provide Product X?”
- Generate natural-language answers based on retrieved graph data


## Dependencies

-   Python 3.8+
-   Neo4j Desktop [Download it here](https://neo4j.com/download/)
-   OpenAI account (for triple extraction)
-   Jupyter Notebook or any Python IDE (e.g., VS Code)
-   [Procurement KPI Analysis Dataset](https://www.kaggle.com/datasets/shahriarkabir/procurement-kpi-analysis-dataset)
    
Open your terminal or notebook and install the following:

```python
pip install pandas py2neo openai neo4j datasets
```
Fulll blog post here: https://supermemory.ai/blog/knowledge-graph-for-rag-step-by-step-tutorial/

If you find this helpful, kindly give this ⭐
