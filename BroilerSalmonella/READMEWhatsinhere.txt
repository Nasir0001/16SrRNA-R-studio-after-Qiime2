What's in BroilerSalmonella/

You will find BroilerSalmonellaManifest/ that contains:
the manifest file needed for initial qiime comands for the ileal samples (QiimeManifestIlealBroilerSalmonella/)
and
the manifest file needed for initial qiime comands for the cecal samples (QiimeManifestCecalBroilerSalmonella/)

You will find BroilerSalmonellaMetadata/ that contains:
the
QiimeIlealMetadata/ that contains:
the orginal ileal metadata that contains all the samples (QiimeMetadataOGIlealBroilerSalmonella/). The days will then be subset out of this (see QiimeScriptsIlealBroilerSalmonella/)
and
the renamed ileal metadata that a renamed isolator (RI) coloumn (QiimeMetadataRIIlealBroilerSalmonella/)
and
the grouped ileal metadata (G) that has each of the two replcates grouped/merged by isolator (QiimeMetadataGIlealBroilerSalmonella/)
and
QiimeCecalMetadata/ that contains:
and
the orginal cecal metadata that contains all the samples (QiimeMetadataOGCecalBroilerSalmonella/). The days will then be subset out of this (see QiimeScriptsCecalBroilerSalmonella/)
and
the renamed cecal metadata that a renamed isolator (RI) coloumn (QiimeMetadataRICecalBroilerSalmonella/)
and
the grouped (G) cecal metadata that has each of the two replcates grouped/merged by isolator (QiimeMetadataGCecalBroilerSalmonella/). 

NOTE: The purpose of the "profile" coloumn in the grouped (G) metadata file combines breed and challenge state for beta diversity pairwise adonis testing.
NOTE: You will use these files in order through the qiime pipeline. Manifest and then metadata. The metadata file will change (OG, RI, or G) depending on the day that is being analyzed.

You will find BroilerSalmonellaScripts/ that contains:
IlealQiimeScripts/ that contains:
the 5 different script/commands used in Qiime2 for ileal samples to analyze sequence quality and obtain preliminary outputs needed for R. 
and 
CecalQiimeScripts/ that contains:
the 5 different script/commands used in Qiime2 for cecal samples to analyze sequence quality and obtain preliminary outputs needed for R.
and 
IlealRScripts/ that contains:
the 5 different scripts used in R studio for ileal samples to perform alpha and beta diversity analyses and obtain taxanomic and differentially abundant genera plots.
and
CecalRScripts/ that contains:
the 5 different scripts used in R studio for cecal samples to perform alpha and beta diversity analyses and obtain taxanomic and differentially abundant genera plots.

NOTE: There are 5 scripts from each intestinal location that represents a slightly different script for each day of the experiment (D7, D13, D17, D21, D24).
NOTE: This project was done on Purdue University's computing clusters. Therefore, some parts of code may not pertain to your local machine when reading the Qiime scripts.

