#

## Encodings

- Label
- One hot
- Hash
- Count
- Target
  - LOO
  - Sigmoid
  - Naive bayes

## Embeddings

- word2vec
- Keras random

## Modelling

- Cleaning: text conforming (e.g. fuzzywuzzy, dirty cat)
- Before modelling, think: is there some external data that explains how groups are related?
  - For postcodes: lat/lng, elevation, population density
  - For wines: alcohol/sugar levels, ratings
- Similar idea: can you group them at a higher level?
- Do I care about interactions between my cats and other variables?
- If data is sufficient: should you try building a separate model for each category?

## Boosting libraries

- XGBoost
- LightGBM
- CatBoost

---

Links to read

https://arxiv.org/pdf/1809.04559.pdf
http://www.csiss.org/SPACE/workshops/2004/SAC/files/fisher.pdf (LightGBM cat algo)

---

Ideas for simulations

- Does catboost's target encoding ignore interactions between variables?
- How much do different encoding strategies reduce overfitting?
  - 