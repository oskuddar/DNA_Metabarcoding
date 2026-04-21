Sample_Name: Unique identifier assigned to each soil sample.
Batch: Sequencing run identifier indicating which batch the sample was processed in.
Top5_LabID: USGS identifier corresponding to sample records.
Weight..gram.: Mass of the soil sample used for DNA extraction, measured in grams.
gDNA.Concentration..ng.ul.: Concentration of extracted genomic DNA, measured in nanograms per microliter.
qpcr_nM: Concentration of PCR-amplified DNA (using index primers for both trnL and ITS2), quantified by qPCR and expressed in nanomolar units.
CollDate: Date on which the soil sample was collected.
Latitude: Geographic latitude of the sample collection location.
Longitude: Geographic longitude of the sample collection location.
pH: pH: Soil pH estimated from ArcGIS based on sample latitude and longitude.
Clay: Percentage of clay content estimated from ArcGIS based on sample latitude and longitude.
Sand: Percentage of sand content estimated from ArcGIS based on sample latitude and longitude.
Silt: Percentage of silt content estimated from ArcGIS based on sample latitude and longitude.
temp_mean: Mean annual temperature calculated from PRISM4 data based on sample latitude and longitude.
precipitation_mean: Mean annual precipitation calculated from PRISM4 data based on sample latitude and longitude.
KG_Main: Primary Köppen–Geiger climate classification category.
KG_Sub: Secondary Köppen–Geiger climate subtype.
KG_TempType: Third Köppen–Geiger climate subtype.
KG_Main_Sub: Combined Köppen–Geiger main and secondary classification.
KG_MST: Combined Köppen–Geiger main, secondary and third classification.
trnl_raw_rc: Raw read count obtained from sequencing of the trnL marker.
its2_raw_rc: Raw read count obtained from sequencing of the ITS2 marker.
trnl_nonchim: Number of non-chimeric reads retained for the trnL marker after quality filtering with DADA2.
its2_nonchim: Number of non-chimeric reads retained for the ITS2 marker after quality filtering with DADA2.
