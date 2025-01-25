### Hi there 👋

⚔️ This is the code for our paper `CUTTANA: Scalable Graph Partitioning for Faster
Distributed Graph Databases and Analytics`. ⚔️

Two main repositories are [`cuttana-partitioner`](https://github.com/cuttana/cuttana-partitioner) and [`application-study`](https://github.com/cuttana/application-study). The first one contains the codes for the actual implementation of Cuttana and the second one is the framework for application study. 

Our graph partitioning algorithm has been accepted in the VLDB2025 conference. You can read the full paper [here](https://www.vldb.org/pvldb/vol18/p14-hajidehi.pdf). 

If you used our paper please cite it using this bibtex: 

```
@article{hajidehi2023cuttana,
  title={CUTTANA: Scalable Graph Partitioning for Faster Distributed Graph Databases and Analytics},
  author={Hajidehi, Milad Rezaei and Sridhar, Sraavan and Seltzer, Margo},
  journal={arXiv preprint arXiv:2312.08356},
  year={2023}
}
```

## Updates:
We add versions of requirements (g++, make, openmp) as well as documentation about file format and an example file to [`cuttana/cuttana-partitioner`](https://github.com/cuttana/cuttana-partitioner) repository. 

We add an efficient single threaded implementation (without lock-free queues) in `cuttana/cuttana-partitioner` repository.

We added a notation table for easier understanding of paper [here](https://github.com/cuttana/cuttana/blob/main/Notation_Table.pdf). 

Make code cleaner and minor fixes. 
<!--
**cuttana/cuttana** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
