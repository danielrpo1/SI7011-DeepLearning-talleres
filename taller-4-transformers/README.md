# Taller 4 – Transformers (TweetEval Emotion)

## Notebooks del curso (código completado)

| Parte | Archivo |
|-------|---------|
| 1 | `tweeteval-part-1-data.ipynb` |
| 2 | `tweeteval-part-2-pipeline.ipynb` |
| 3 | `tweeteval-part-3-distilbert.ipynb` |
| 4 | `tweeteval-part-4-bertweet.ipynb` |
| 5 | `tweeteval-part-5-lora.ipynb` |
| 6 | `tweeteval-part-6-deployment.ipynb` |

## Ejecución en Kaggle (outputs visibles)

Notebook unificado ejecutado en Kaggle (CPU, 1 época por modelo):

**https://www.kaggle.com/code/danielrpo1/si7011-tweeteval-emotion-daniel-restrepo**

Copia local del código: `si7011-tweeteval-emotion-daniel-restrepo-kaggle.ipynb`

## Resultados (test set)

| Modelo | Accuracy (test) |
|--------|-----------------|
| DistilBERT | 69.5% |
| BERTweet | 76.6% |
| BERTweet + LoRA (1 época) | 39.8% |

LoRA con 1 época queda poco entrenado; BERTweet full fine-tuning es el mejor baseline.
