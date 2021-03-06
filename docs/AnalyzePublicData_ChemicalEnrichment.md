# Analyze All Public Data: Chemical Annotation Enrichment Analysis

## Example Use Cases
* **Explore which chemicals have been detected in the public data** in order to test or develop hypotheses, and determine the specific files in the public data that are relevant for follow up analysis. *viz.* I'm interested in the analysis of piperine (a chemical found in black pepper), but I don't know if I can detect it using mass spectrometry; has this chemical be found in any of the public data?
* **Launch sample information enrichment analysis** on a specific chemical annotation to test or develop hypotheses, *viz.* I'm interested in the analysis of piperine (a chemical found in black pepper), but I don't know what types of samples should I look in; launching sample information enrichment analysis indicates that it is detected in food sample, human feces, etc.

## Summary
Chemical annotation is performed in [GNPS](https://gnps.ucsd.edu/ProteoSAFe/static/gnps-splash2.jsp) by comparing MS2 spectra, specifically product ion spectra, with reference MS2 fragmentation patterns (GNPS integrates of the majority of public reference MS2 spectra library). **All chemical annotations that originate from public data are tabulated along with the number of files, a button that then provides the individual file names, and a button that lanches a sample information enrichment analysis.** Further documentation on GNPS is located [here](https://ccms-ucsd.github.io/GNPSDocumentation/).

## Tutorial
1. Navigate to the [ReDU-MS2](http://dorresteinappshub.ucsd.edu:5005/) homepage.
2. Click on the **"Chemical Annotation Enrichment Analysis"** under the **Analyze All Public Data** section.

**IMAGE**

3. The table will load (this can take a few seconds). You can browse the chemicals either by scrolling down the page or search for specific chemicals via Ctrl+F (COMMAND F on MAC OS). **NOTE: The same chemical can have multiple GNPS annotations.**
  
  **IMAGE**

4. Users can click on the **View Files** button (orange) on the right side of that page to view the files in which a particular chemical was annotated.

  **IMAGE**
  
5. Users can launch a **sample information enrichment analysis** by clicking the **View Enrichment** button (orange) on the right side of the page. Further information on **sample information enrichment analysis** can be found [here](AnalyzePublicData_SampleInformationEnrichment.md).

  **IMAGE**

## Notes:
* GNPS annotations via spectral reference matching are considered level 2 (putative annotation based on spectral library similarity) or 3 (putatively characterized compound class based on spectral similarity to known compounds of a chemical class) by the 2007 metabolomics standard initiative [PMID: 24039616](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3772505/).
* **The same chemical can have multiple GNPS annotations.** Slight variation in the MS2 spectra (*m/z* or abundance) cause the pattern to match difference reference MS2 spectra for the same chemical. Users are highly-encouraged to double check their findings.
