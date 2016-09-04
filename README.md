# MasterThesisMaterial
README file - Reproducibility of Material used for: “Exploring structural sections in EDM DJ-created radio mixes with the help of automatic music descriptors” - Supervised by P. Herrera & G. Bandiera - Master in Sound & Music Computing - Pompeu Fabra, Barcelona - Vincent Zurita Turk - 2016

There are 4 .zip files containing:
-Starting point of songs Annotations - .csv file for each 20 DJ mixes (40 hours) with the annotations giving the point in time when a new song stars

-Structural sections Annotations: .csv file for each of the 8 DJ mixes (16 hours) with the annotations giving the point in time when a new structural sections starts

-Music descriptors x Structural sections Annotations: .csv file of reach of the 8 DJ mixes (16 hours) with the values of the extracted descriptors and the annotations giving the points in time when both a new song & new structural sections starts.

(Descriptors used: BPM, pitch salience, spectral centroid loudness, energy, RMS, danceability, onset rate, 13 MFCC bands, 27 Bark bands)

-Scripts 
	read.py: extracts BPM, pitch salience, spectral centroid loudness, energy, RMS, danceability & onset rate, averaging its values every 10 seconds. 
	barkbands.py: extracts 27 bark bands, averaging its values every 10 seconds
	mfcc.py: extracts 13 MFCC bands, averaging its values every 10 seconds

