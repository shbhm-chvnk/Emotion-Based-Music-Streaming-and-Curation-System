Emotion-Based Music Streaming and Curation System
=================================================

This project presents a personalized music recommendation system that adapts to users' facial emotions. By leveraging computer vision and deep learning, the system detects facial expressions in real time and curates music playlists that match the detected mood. The system enhances user engagement by dynamically adjusting playlists based on emotions, providing a more immersive and interactive music experience.

Features
--------
**Real-Time Facial Emotion Recognition:**
* Happy
* Sad
* Angry
* Disgust
* Surprise
* Neutral
* Fear

**Emotion-Based Music Recommendation:**
* Maps detected emotions to music moods such as Happy, Sad, Energetic and Calm.
* Uses content-based filtering and cosine similarity to match songs to user emotions.
* Prioritizes personalized curation by analyzing ~160K tracks.

**Seamless Integration with Spotify API:**
* Fetches song metadata and audio features dynamically.
* Creates mood-based custom playlists.

How It Works?
---------------------
1. Capture User’s Facial Expression (via webcam or image upload).
2. Predict Emotion using a trained CNN model.
3. Match Emotion to Music Mood using a pretrained classifier.
4. Generate Recommended Playlist based on similarity measures.
5. Stream Personalized Songs directly via Spotify API.


