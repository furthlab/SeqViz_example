# SeqViz_example

 How to use Vanilla version (not react) of SeqViz


## Installation 

Create conda environment for node.js.

```
conda create -n seqviz nodejs
```

```
conda activate seqviz
```

```
npm install -g seqparse
```
## Convert SnapGene file.

```
seqparse ./data/snapgene/addgene-plasmid-113168-sequence-217924.dna > ./data/addgene113168.json
```

You now have a JSON file named `addgene113168.json` in the data folder. You can open up `index.html` and view it simply by adding the file prefix as a hash:

```
http://127.0.0.1:5500/#addgene113168
```
