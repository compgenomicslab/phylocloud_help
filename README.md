# Overview
Welcome! PhyloCloud is an easy-to-use online platform for operating and interpreting phylogenetic trees and multiple sequence alignments, serving as a bridge between complex phylogenomic frameworks and non-expert users. Users can browse the public tree collections or build and save your own trees at your own workplace both registerially and anonymously

# Quick Start
 PhyloCloud provides entry point to annotated data and tools for phylogenomic research, regardless of whether registered or anonymous users. The home page of PhyloCloud indicates the most typical features so you can quickly start using PhyloCloud:

 - [Upload and visualize trees](#uploadtree) , registerially or anonymously
 - [Build your phylogenies](#buildtree)  by just one click
 - [Browse and search](#browsetree) public tree collection

Besides of common usage for trees management, we also provide various phylogenetic tools to conduct various analysis

 - [Compare tree topologies](#comparetree)
 - [Query taxonomy databases](#taxaquery) 
 - [Sequence placement](#sequenceplacement)


If you already have a tree, PhyloCloud implemented the state-of-art tree visualizing engine and provide various options for further modification or analysis.

- [Tree visualization](#treepage) with further analysis

# UploadTree
One of the core features in PhyloCloud is to allow user upload multiple trees as a collection. Click the [Upload tree](https://phylocloud.cgmlab.org/) button at the top right corner of the page to open the upload panel.

![uploadTree](./img/uploadtree2.jpeg)

Input trees are expected to be in plain text files which not bigger than 50MB(~500,000 tips), and at the moment we support Newick format and parse with ETE Toolkit, for further imformation about newick format, please check [ETE Toolkit](http://etetoolkit.org/docs/latest/tutorial/tutorial_trees.html#reading-newick-trees)

Phylocloud also allows user to attach alignment (<500MB) with corresponding tree. If you upload alignment files alongside with treefiles, please note that they must share the same prefix, otherwise alignments are not able to detect as attachment.

Besides of data input, users can also choose if their collection private or public for other users. Collection name is optional, once a collection is created, it will generate a collection id and it will be the collection title if it was not named. Anonymous user will be directed to the collection page where storage the trees you just upload. For registered users, they will be redirected to [my cloud](https://phylocloud.cgmlab.org/my_cloud/) where your private cloud is. 

``` *Noted Anonymous users should remember the collection id otherwise it will be lost. ```

# BuildTree
Phylocloud provides a automated phylogenetic workflows to construct phylogeneies with a simple click. Submit nucleotide or amino acids sequences in FASTA format and infer a phylogeny using ETE-Toolkit predefined workflows.  Click [here](https://phylocloud.cgmlab.org/tree_build/) to explore more

Once the job has submit, it will be redirect to result page with job id. After a waiting patiently for a moment, result tree will be render and visualized on the result page. 

``` *Noted users should remember the job id otherwise it will be lost. ```

# BrowseTree
In phylocloud we have storage a several of featured collections which is public and open for browsing and download. Click [Featured Collection](https://phylocloud.cgmlab.org/public_cloud/) to enter the public collection portal. Once your interested collection, click the collection title and entered the collection page.

Here we show example of [eggNOG5](https://phylocloud.cgmlab.org/collection_page/61c3074a7b69b966754c2c4e/) collection:

![eggNOG5Collection](./img/eggNOG5.jpeg)

- Trees of collection are displayed as tree cards with thumnails, with treecard you can find basic information of each tree, such as owner, title, and download button of tree and alignment(if there is)
- User can search trees by <strong>tree title</strong> or <strong>node</strong>'s name against public collection or own collection. When users are at collection page, the search filter will switch to Current Collection where allows user to search within collection


