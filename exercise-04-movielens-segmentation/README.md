# Exercise 04 — MovieLens Audience Segmentation

[![Open starter in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lathrahul/modern-ai-ml-exercises/blob/main/exercise-04-movielens-segmentation/notebooks/getting_started.ipynb)

**Release:** November 16  
**Due:** December 6 at 11:59 PM ET  
**Expected effort:** 3–4 hours  
**Work mode:** Pairs; one submission per pair  
**Points:** 4

Use MovieLens ratings to build, compare, and interpret audience segments. The notebook downloads the `ml-latest-small` dataset, creates user-level behavioral and genre-preference features, scales the feature table, and evaluates candidate cluster solutions.

## Learning goals

- Explain why representation and scaling affect cluster geometry.
- Compare candidate values of K using inertia and silhouette.
- Check stability across random starts with adjusted Rand index (ARI).
- Compare K-means with hierarchical clustering.
- Translate cluster profiles into useful audience personas while stating limitations.

## Start here

Open `notebooks/getting_started.ipynb` in Google Colab and choose **File > Save a copy in Drive** before editing. Run the notebook once from top to bottom before changing the representation or selected value of K.

The notebook downloads the public MovieLens `ml-latest-small` archive from GroupLens. If that download is unavailable, rerun later or use a local copy of the dataset with the same folder structure.

## Submission evidence

Submit the completed notebook or PDF export requested in Blackboard. Make the following decisions easy to locate:

1. The user-level representation and whether features were transformed or scaled.
2. The selected K, supported by inertia, silhouette, and interpretability.
3. A stability result across starts or resamples, including neighboring K values.
4. Cluster profiles and cautious persona names grounded in measured behavior.
5. One recommended action, one limitation, and what you would test next.

The goal is a defensible segmentation, not the highest possible internal score.
