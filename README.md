# BIP-task3
task3 for the deep learning in forestry.

TreeSatAI Benchmark Archive for Deep Learning in Forest Applications

Dataset

200m patches 60m patches

GeoTIFF naming convention: genus_species_ageclass_sampleID_dataset_source.tif
e.g.: Fagus_sylvatica_1_6647_WEFL_NLF.tif

https://owncloud.gwdg.de/index.php/s/aOfOKOnuq4S7WpU
TreeSatAI_Sentinel-2_Tree-Species.zip

▪ Folder “s2” contains 50,381 Sentinel-2 imagery patches derived from summertime
mosaics of the years 2015 to 2020. Patches are available in 60 x 60 m (6 x 6 pixels) and
200 x 200 m (20 x 20 pixels). Band order is B02, B03, B04, B08, B05, B06, B07, B8A, B11,
B12, B01, and B09. Spatial resolution is 10 m.
▪ 20 species classes (single labels)
▪ 12 age classes (single labels)
▪ 15 genus classes (multi labels)
▪ fixed split for train “train_filenames.lst” (90%) and test “test_filesnames.lst“ (10%) data