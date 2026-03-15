# The Doors Reimagined

This project revisits an earlier notebook on The Doors and updates it with a broader exploratory workflow. It combines lyric preprocessing, frequency analysis, semantic embeddings, BERTopic clustering, and sentiment-based “emotional weather” to study how the songs group, differ, and recur across themes and motifs.

## Contents

- `The-Doors-Reimagined.ipynb` — the main notebook
- `doors_from_kaggle.csv` — the lyric dataset used in the analysis
- `images/jim.jpg` — the mask image used for the word cloud
- `media/` — optional local audio files for notebook playback

## What the notebook covers

- corpus overview and basic descriptive statistics
- lexical structure and repetition
- recurring phrases and thematic motifs
- signature words for selected songs
- semantic song mapping with sentence embeddings
- thematic provinces with BERTopic
- emotional weather across selected songs

## Notes

The notebook is designed to be read as an exploratory analysis rather than a finished model of the band’s work. Some visual outputs depend on the local Jupyter frontend and installed plotting stack. For some reason Github does not render the various visuals apart from the wordcloud which is loaded from a file anyway. to properly inspect the outputs you should download the repo and inspect it with jupyternotebook or open the HTML render.

## License

Dataset and media rights belong to their respective sources and owners.
