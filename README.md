# MasterThesisMaterial
README file - Reproducibility of Material used for: “Exploring structural sections in EDM DJ-created radio mixes with the help of automatic music descriptors” - Supervised by P. Herrera & G. Bandiera - Master in Sound & Music Computing - Pompeu Fabra, Barcelona - Vincent Zurita Turk - 2016

There are 4 .zip files containing:

-Structural sections Annotations: .csv file for each of the 8 DJ mixes (16 hours) with the annotations giving the point in time when a new structural sections starts

-Music descriptors x Structural sections Annotations: .csv file of reach of the 8 DJ mixes (16 hours) with the values of the extracted descriptors and the annotations giving the points in time when both a new song & new structural sections starts.

(Descriptors used: BPM, pitch salience, spectral centroid loudness, energy, RMS, danceability, onset rate, 13 MFCC bands, 27 Bark bands)

-Scripts 
	read.py: extracts BPM, pitch salience, spectral centroid loudness, energy, RMS, danceability & onset rate, averaging its values every 10 seconds. 
	barkbands.py: extracts 27 bark bands, averaging its values every 10 seconds
	mfcc.py: extracts 13 MFCC bands, averaging its values every 10 seconds

-Starting point of songs Annotations - .csv file for each 20 DJ mixes (40 hours) with the annotations giving the point in time when a new song stars

2014.08.09 - Essential Mix - Skream in Ibiza.csv
2015.08.15 - Essential Mix - Jose Padilla.csv
2015.05.09 - Essential Mix - Scuba.csv
2015.03.28 - Essential Mix - Four Tet x Jamie XX.csv
2015.03.21 - Essential Mix - Kryder.csv
2015.02.21 - Essential Mix - Redlight.csv
2015.10.24 - Essential Mix - Loco Dice.csv
2015.09.05 - Essential Mix - Lee Burridge.csv
2015.01.24 - Essential Mix - Tale Of Us.csv
2015.08.29 - Essential Mix - Rudimental.csv
2015.10.17 - Essential Mix - Ed Banger Special.csv
2015.04.25 - Essential Mix - Claptone.csv
2015.10.31 - Essential Mix - Dave Clarke.csv
2015.01.31 - Essential Mix - Joris Voorn.csv
2015.10.03 - Essential Mix - Flume.csv
2015.07.31 - Essential Mix - Hot Since 82.csv
2015.05.02 - Essential Mix - Julio Bashmore.csv
2015.09.19 - Essential Mix - Seth Troxler.csv
2015.02.28 - Essential Mix - Max Cooper.csv
2015.10.31 - Essential Mix - Dave Clarke

-EDM radio DJ-created mixes - The collection in mp3 for the study
2015.10.24 - Essential Mix - Loco Dice
2015.09.19 - Essential Mix - Seth Troxler
2015.09.05 - Essential Mix - Lee Burridge
2015.05.09 - Essential Mix - Scuba
2015.04.25 - Essential Mix - Claptone
2015.03.28 - Essential Mix - Four Tet x Jamie XX
2015.02.28 - Essential Mix - Max Cooper
2015.10.31 - Essential Mix - Dave Clarke
