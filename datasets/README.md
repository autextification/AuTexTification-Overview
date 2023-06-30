# Dataset (Subtask 1)

## Dataset counts

![Counts](figures/subtask_1_stats.png)

# Dataset (Subtask 2)

## Dataset counts
![Counts](figures/subtask_2_stats.png)

# General

## Zipf's Law (Spanish)

![Zipf Law (Spanish)](figures/es_zipf_plot.png)

## Zipf's law (English)

![Zipf Law (English)](figures/en_zipf_plot.png)

## Heap's law (Spanish)

![Heap Law (Spanish)](figures/es_heap_plot.png)

## Heap's law (English)

![Heap Law (English)](figures/en_heap_plot.png)

## Metric plots
These plots aim to show the distribution of the generated/human texts according to the different domains/labels/models in terms of metrics that measure the quality of generations and that compare them with the prompts (i.e. repetition, diversity, stopword and symbol ratios, self-BLEU, perplexity, SimCSE semantic coherence, and entailment ratio). Each text is represented with a vector of metric values, normalized with z-score and t-SNE projected using a perplexity of 15, keeping the remaining parameters as default. The three plots contain the same points, but colored according to the different domains, models, and label.

| ![Domain colored](figures/t-SNE_domain_2D.png) | 
|:--:| 
| *Domain plot* |

| ![Model colored](figures/t-SNE_model_2D.png) | 
|:--:| 
| *Model plot* |

| ![Label colored](figures/t-SNE_label_2D.png) | 
|:--:| 
| *Label plot* |
