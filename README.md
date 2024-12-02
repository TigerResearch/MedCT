# MedCT

MedCT is the world's first clinical terminology for non-English community, specifically Chinese. It achieves state-of-the-art performance in medical NER and NEL tasks, for both English and Chinese.

Our first release contains:

1. The MedCT bilingual (en and zh) clinical terminology dictionary: {concept_id, [synonyms]}..., [MedCT](https://huggingface.co/datasets/TigerResearch/MedCT);
2. The MedCT named entity recognition (NER) models: [MedLink-en](https://huggingface.co/TigerResearch/MedLink-en), [MedLink-zh](https://huggingface.co/TigerResearch/MedLink-zh);
3. The MedCT foundation model: [MedBERT](https://huggingface.co/TigerResearch/MedBERT);
4. Our MedCT-clinical-notes dataset, including: 
	* For the NER task, 7.4K real-world clinical notes in Chinese (medct_notes.csv), and 61K entity mention annotations per MedCT graph (medct_annotations.csv).
	* For the search task, 20 clinical queries (medct_queries.csv), and 2K discharge notes with relevance annotations (medct_search.csv).
5. The MedCT and the search application demos.
	* MedCT: https://medct.tigerbot.com/
	* MedSearch: https://medsearch.tigerbot.com/


