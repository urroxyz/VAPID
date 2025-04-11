# VAPID
The **V**isual and **A**uditory **P**rocessed **I**dentification **D**ataset (VAPID) is a human-curated shared task collection of audiovisual media intended for computational research in natural language processing (NLP) to create models for domains such as automatic speech recognition, speech translation, audio description, and speaker verification or diarization.

Currently, to most AI models, this audiovisual media is **vapid**, because they are hardly trained on videos accompanied by audio, and we are trying to change that.

## Format
`platform` > `identifier` > `timestamp_start --> timestamp_end`:
1. `video.mp4` OR `video.webm`
2. `audio.mp3` OR `audio.wav`
3. `captions.[language].vtt`
4. `subtitles.[language].vtt`
5. `description.[language].vtt`

## Annotation
Annotations must always be adjectives.
1. gender `gen` (`male`, `female`, `mixed`, `ambiguous`)
2. age `age` (`young`, `middle-aged`, `elder`, etc.)
3. accent `acc` (`African`, `American`, `Celtic`, `European`, `Oceanic`, `South-Asian`, `South-East-Asian`, etc.)
4. emotion `emo` (`happy`, `saddened`, `angry`, `neutral`, `frustrated`, etc.)
