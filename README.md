# GenderRecognition
Determine male or female based on voice data.

To analyze gender by voice and speech, a training database was required. A database was built using thousands of samples of male and female voices, each labeled by their gender of male or female. Voice samples were collected from the following resources:

The Harvard-Haskins Database of Regularly-Timed Speech Telecommunications & Signal Processing Laboratory (TSP) Speech Database at McGill University VoxForge Speech Corpus Festvox CMU_ARCTIC Speech Database at Carnegie Mellon University Each voice sample is stored as a.WAV file, which is then pre-processed for acoustic analysis using the specan function from the WarbleR R package. Specan measures 22 acoustic parameters on acoustic signals for which the start and end times are provided.

The output from the pre-processed WAV files were saved into a CSV file, containing 3168 rows and 21 columns (20 columns for each feature and one label column for the classification of male or female). You can download the pre-processed dataset in CSV format, using the link above.In order to analyze gender by voice and speech, a training database was required. A database was built using thousands of samples of male and female voices, each labeled by their gender of male or female.
