OVERVIEW OF THE MATERIAL

CSV Files

The list of Green and Amber genes in Structural Eye disease has been downloaded from https://panelapp.genomicsengland.co.uk/panels/509/
version 1.3
Files contain human-mouse syntenic Long Range Interactions(hmsLRI) in which a green or amber gene is involved:
	hmsLRI list files
	"hmsLRI's_Promoter_within_Green_Genes.csv": List of hmsLRI in which the promoter anchor overlaps the promoter
	of a Green Gene (defined as ± 2.5kb of TSS)
	
	"hmsLRI's_Enhancer_within_Green_Genes.csv": List of hmsLRI in which the enhancer anchor is within a Green Gene region
	
	"hmsLRI's_Promoter_within_Amber_Genes.csv": List of hmsLRI in which the promoter anchor overlaps the promoter 
	of an Amber Gene (defined as ± 2.5kb of TSS)
	
	"hmsLRI's_Enhancer_within_Amber_Genes.csv": List of hmsLRI in which the enhancer anchor is within a Amber Gene region
	
	"hmsLRI's_Promoter_within_Fitzpatrick_Genes.csv": List of hmsLRI in which the promoter anchor overlaps the promoter 
	of a Fitzpatrick Gene (defined as ± 2.5kb of TSS)
	
	"hmsLRI's_Enhancer_within_Fitzpatrick_Genes.csv": List of hmsLRI in which the enhancer anchor is within a Fitzpatrick Gene region
	
	"hmsLRI's_Promoter_within_Eye_development_Genes.csv": List of hmsLRI in which the promoter anchor overlaps the promoter 
	of an Eye development Gene (defined as ± 2.5kb of TSS)
	
	"hmsLRI's_Enhancer_within_Eye_development_Genes.csv": List of hmsLRI in which the enhancer anchor is within a Eye development Gene region
	
	Enhancer nodes files
	"Enhancer_Nodes_Connected_to_Green_Genes.csv": List of Enhancer nodes in which the promoter anchor is the promoter of a Green Gene
	(defined as ± 2.5kb of TSS)
	
	"Enhancer_Nodes_within_Green_Genes.csv": List of Enhancer nodes in which the enhancer anchor is within a Green Gene region
	
	"Enhancer_Nodes_Connected_to_Amber_Genes.csv": List of Enhancer nodes in which the promoter anchor is the promoter of an Amber Gene
	(defined as ± 2.5kb of TSS)
	
	"Enhancer_Nodes_within_Amber_Genes.csv": List of Enhancer nodes in which the enhancer anchor is within a Amber Gene region
	
	"Enhancer_Nodes_Connected_to_Fitzpatrick_Genes.csv": List of Enhancer nodes in which the promoter anchor is the promoter of a Fitzpatrick Gene
	(defined as ± 2.5kb of TSS)
	
	"Enhancer_Nodes_within_Fitzpatrick_Genes.csv": List of Enhancer nodes in which the enhancer anchor is within a Fitzpatrick Gene region
	
	"Enhancer_Nodes_Connected_to_Eye_development_Genes.csv": List of Enhancer nodes in which the promoter anchor is the promoter of an 
	Eye development Gene (defined as ± 2.5kb of TSS)
	
	"Enhancer_Nodes_within_Eye_development_Genes.csv": List of Enhancer nodes in which the enhancer anchor is within a Eye development Gene region

	

Genome Browser track hub

	UCSC Genome Browser
	The hmsLRI are available as a remote track hub for UCSC Genome Browser, the interactions are represented using
	different colors based on if the involved gene is a Green gene or an Amber gene and in a separate track there 
	are the interactions involving a gene identified by Fitzpatrick (Red) and the list of eye development genes (blue);
	Below each interactions track there is a track with the enhancer node regions
	You can browse them at: http://genome.ucsc.edu/cgi-bin/hgHubConnect?redirect=manual&source=genome.ucsc.edu
	Under the section "My Hubs" you can insert the following URL and add the Hub: https://github.com/ctglab/UCSC_Track_hub_hmsLRI_Eye_diseases/raw/main/UCSC_Genome_Browser_hub/hubDirectory/hub.txt 
