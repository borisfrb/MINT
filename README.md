## The image data will come soon...
## 📚 Data Format
Our dataset includes images, narrative text, audio captions, and audio. We organize the data using JSON files, where each line represents a data sample. 
You can use the [yt-dlp](https://github.com/yt-dlp/yt-dlp) to get audio files using the provided **youtube\_id** and **audio\_start\_time**. Note that when using the yt-dlp tool to fetch audio files, ensure that the duration for fetching audio is set to **10 seconds**, as specified by AudioSet and AudioCaps. For images, we provide their indices in the JSON file. The actual images can be downloaded from Zenodo.


This is an example of our dataset：
```
{"audiocaps_id": "97151",

"youtube_id": "vfY_TJq7n_U",

"audio_start_time": "130",

"audio_caption": "Rustling occurs, ducks quack and water splashes, followed by an adult female and adult male
speaking and duck calls being blown",

"image": "97151.png",

"narrative_text": "As I make my way along the winding path, I come across a loving couple, their gentle conversation a warm and intimate accompaniment to the natural soundscape. The adult female's voice is soft and melodious, while the adult male's is deep and soothing. Their words are lost in the distance, but the love and contentment in their tone is palpable. Suddenly, a duck call pierces the air, followed by a chorus of quacks and honks from the ducks in the water. The sounds blend together in perfect harmony, a beautiful tapestry of sound that envelops me in its serenity."}
```
## :warning:  Ethics Statement

The access to this MINT dataset is limited to academic institutions and is for research purposes only. We include frames extracted from each YouTube video as images in the dataset and ensure that these images do not adversely affect the copyright owner's ability to generate revenue from their original content, thereby complying with YouTube's fair use policy. If any copyright owner believes their rights have been infringed, we commit to promptly removing the disputed materials from our dataset.
