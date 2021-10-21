# Prose2Poem: The Blessing of Transformers in Translating Prose to Persian Poetry

Persian Poetry has consistently expressed its philosophy, wisdom, speech, and rationale on the basis of its couplets, making it an enigmatic language on its own to both native and non-native speakers. Nevertheless, the notice able gap between Persian prose and poem has left the two pieces of literature medium-less. Having curated a parallel corpus of prose and their equivalent poems, we introduce a novel Neural Machine Translation (NMT) approach to translate prose to ancient Persian poetry using transformer-based Language Models in an extremely low-resource setting. More specifically, we trained a Transformer model from scratch to obtain initial translations and pretrained different variations of BERT to obtain final translations. To address the challenge of using masked language modelling under poeticness criteria, we heuristically joined the two models and generated valid poems in terms of automatic and human assessments. Final results demonstrate the eligibility and creativity of our novel heuristically aided approach among Literature professionals and non-professionals in generating novel Persian poems.


Information about the Semantic Affinity dataset:
	
|topic | poetry |
| ---- | ----|
|khodavand (God) | 237 |
|erfan (Devine) | 288|
|akhlagh (Moral) | 348|
|eshq (Love) | 446|

![alt text](https://github.com/mitramir55/Prose2Poem/blob/main/topics%20dist.png)
