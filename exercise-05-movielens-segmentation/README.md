# Exercise 05 - MovieLens Audience Segmentation

Use MovieLens ratings to build, compare, and interpret audience segments. The notebook downloads the `ml-latest-small` dataset, creates user-level behavioral and genre-preference features, scales the feature table, and evaluates candidate cluster solutions.

## Learning goals

- Explain why representation and scaling affect cluster geometry.
- Compare candidate values of K using inertia and silhouette.
- Check stability across random starts with adjusted Rand index (ARI).
- Compare K-means with hierarchical clustering.
- Translate cluster profiles into useful audience personas while stating limitations.

## Start here

Open `notebooks/getting_started.ipynb` in Google Colab and choose **File > Save a copy in Drive** before editing.

The notebook downloads the public MovieLens `ml-latest-small` archive from GroupLens. If that download is unavailable, rerun later or use a local copy of the dataset with the same folder structure.

## Submission evidence

Submit the completed notebook or PDF export requested in Blackboard. Your work should include the selected K, evidence from inertia and silhouette, a stability result, interpreted personas, one recommended action, and at least one limitation.
