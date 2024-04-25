This DATSETNAMEreadme.txt file was generated on YYYY-MM-DD by NAME
<help text is included in angle brackets, and can be deleted before saving>


GENERAL INFORMATION

1. Title of Dataset: Differentially methylated cytosines in Fragaria vesca

2. Author Information
	A. Principal Investigator Contact Information
		Name: Hanne De Kort
		Institution: KU Leuven
		Address: Kasteelpark Arenberg 31, 3001 Leuven, Belgium
		Email: hanne.dekort@kuleuven.be

	B. Associate or Co-investigator Contact Information
		Name: 
		Institution: 
		Address: 
		Email: 

	C. Alternate Contact Information
		Name: 
		Institution: 
		Address: 
		Email: 

3. Date of data collection (single date, range, approximate date) <suggested format YYYY-MM-DD>: 2018-07-30

4. Geographic location of data collection <latitude, longiute, or city/region, State, Country, as appropriate>: French Pyrenees, French Vosges and Karkonosze in Poland.

5. Information about funding sources that supported the collection of the data: Research Foundation Flanders (FWO), 12P6517N


SHARING/ACCESS INFORMATION

1. Licenses/restrictions placed on the data: NA

2. Links to publications that cite or use the data: https://doi-org.kuleuven.ezproxy.kuleuven.be/10.1111/mec.15689

3. Links to other publicly accessible locations of the data: NA

4. Links/relationships to ancillary data sets: NA

5. Was data derived from another source? no
	
6. Recommended citation for this dataset: NA


DATA & FILE OVERVIEW

1. File List: 
DMCs Dryad.xlsx. One data table sheet including statistically significant DMCs (differentially methylated cytosines) along a fine-scale altitudinal gradient, a large-scale spatial gradient, and between soil moisture treatments, along with methylation proportions at each sampled location, and whether or not the genes alining with the Fragaria vesca genome were involved with transposon activity.

2. Relationship between files, if important: NA

3. Additional related data collected that was not included in the current data package: NA

4. Are there multiple versions of the dataset? no
	

METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data: 
Whole genome bisulfite sequencing was used to identify methylated cytosines across 30 genomes of wild woodland strawberries raised in a common garden. The seeds were collected in France (west and east) and Poland (west). Differentially methylated cytosines (DMCs) were called using the R package methylKit version 1.10.0 with conventional DMC parameters (Akalin et al. 2012). Specifically, only cytosines with at least 5x coverage in at least 3 samples per group were retained (Walker et al. 2015; Wan et al. 2016). To reduce bias due to outlier depth, bases with a read depth above the 99.9th percentile of coverage are filtered out. The filtered data were used to test for differentially methylated cytosines (DMCs), considering a 25% difference and q-values <0.01 as significant. DMCs were identified between (i) low, mid and high altitudinal samples (hereafter “altitudinal DMCs”), (ii) three distance European samples (hereafter “spatial DMCs”), and (iii) two soil moisture treatments (hereafter “drought DMCs”).

2. Methods for processing the data: 
Regression models and gene ontology enrichment analysis.

3. Instrument- or software-specific information needed to interpret the data: 
NA

4. Standards and calibration information, if appropriate: NA

5. Environmental/experimental conditions: Seedlings grown in controlled conditions in a growth chamber with standardized light and soil moisture regimes. To compare the magnitude of inherited epigenetic memories to intra-generational epigenetic change acquired through acute drought stress, an additional seedling per mother plant was raised for the mid-altitudinal Pyrenean plants, and these seedlings were subjected to reduced soil moisture levels starting two months after germination. Specifically, watering stopped until leaves went limp (6-10 days), and this process was repeated consecutively for four weeks, after which the plants were allowed to rehydrate for one week to remove most drought-induced epigenetic effects that do not result in a relatively stable epigenetic signal. Between each of three cycles of drought, plants were watered for three days to allow partial recovery of the soil. The plants were full grown (ca. 3 months of age) prior to the drought treatment and WGBS. They were kept in a growth chamber at room temperature and with regular growth lamps. 

6. Describe any quality-assurance procedures performed on the data: NA

7. People involved with sample collection, processing, analysis and/or submission: Bart Panis, Filip Van Nieuwerburgh, Olivier Honnay


DATA-SPECIFIC INFORMATION FOR: DMCs Dryad.xlsx


1. Number of variables: 9

2. Number of cases/rows: 37155

3. Variable List: 
Chromosome; Position; DMC Type; Genomic Context, DNA strand, DMC pvalue, qvalue, methylation differnce,	gene, transposon


4. Missing data codes: 
"NA"

5. Specialized formats or other abbreviations used: NA
