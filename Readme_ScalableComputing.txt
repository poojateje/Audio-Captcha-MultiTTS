Image captcha GitHub repo - https://www.github.com/amrishAK/imageCaptcha.git
Audio captcha GitHub repo - https://www.github.com/amrishAK/audioCaptcha.git


Audio Captcha current accuracy - 95%

Steps taken in preprocessing to improve the model accuracy:

	1. Pre-processing as audio:	
		a) dimension reduction of the audio using melspectrogram
		c) Converting amplitude into decibels using librosa.amplitude_to_db
		d) Plottig audio as a spectogram in greyscale (dimensions - 128 x 64)
	
	4. Pre-processing as image:
		a) Auto-contrasting (cutoff = 10)
		

Audio Captcha Model Training Method:

Number of Audio files	Epoch	Accuracy
      20000		  2	  12%
      20000		  2	  40%
      40000		  2	  50.10%
      40000		  4	  66%
      40000		  6	  71.187%


Contributors:
1. Amrish Kulasekaran (19327600)
2. Jagadish Rammurthy (19300933)
3. Yeshwanth Rajareddy (19301303)
4. Abishek Vaithylingam (18339763)
5. Shubhanghi Kukreti (19308174)
6. Deepthi Rajappan (19307848)
7. Manasi Palkar (19314065)
7. Kavya Bhadre Gowda (19316050)
8. Pooja Ganesh Teje (19300746)
9. Tanvi Bagla (19300699)


