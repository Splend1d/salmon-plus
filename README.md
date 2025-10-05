# salmon-plus


Edit: https://www.kaggle.com/code/a24998667/llama-mimi-1b

Refresh:https://www.kaggle.com/code/a24998667/salmon-plus-refresh-metadata

## Experimental Results

<!-- AUTO-GEN: EXPERIMENTAL RESULTS BEGIN -->
### `llm-jp_Llama-Mimi-1.3B`

| exp | bg_alignment | bg_all_consistency | bg_domain_consistency | gender_consistency | rir_consistency | sentiment_alignment | sentiment_consistency | speaker_consistency | avg of tasks |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| P2-ppl-spike-pinned-window100.0ms-is-max | 0.00% | 83.50% | 80.50% | 88.00% | 84.50% | 0.00% | 84.50% | 88.00% | 63.62% |
| P2-ppl-spike-pinned-window1000ms-is-max | 0.00% | 83.00% | 80.50% | 99.00% | 88.00% | 0.00% | 92.50% | 95.50% | 67.31% |
| P2-ppl-spike-pinned-window200.0ms-is-max | 0.00% | 86.50% | 83.50% | 98.50% | 88.50% | 0.00% | 92.50% | 95.00% | 68.06% |
| P2-ppl-spike-pinned-window500.0ms-is-max | 0.00% | 83.50% | 79.50% | 100.00% | 84.50% | 0.00% | 95.50% | 96.00% | 67.38% |
| ppl | 52.50% | 73.00% | 73.00% | 83.50% | 91.50% | 48.50% | 79.50% | 85.00% | 73.31% |
| ppl-spike-pinned-topk1 | 0.00% | 79.50% | 74.00% | 92.00% | 76.50% | 0.00% | 81.50% | 88.00% | 61.44% |
| ppl-spike-pinned-topk16 | 0.00% | 87.00% | 81.50% | 99.00% | 86.00% | 0.00% | 92.00% | 94.50% | 67.50% |
| ppl-spike-pinned-topk2 | 0.00% | 81.00% | 77.50% | 97.50% | 80.00% | 0.00% | 88.00% | 91.00% | 64.38% |
| ppl-spike-pinned-topk4 | 0.00% | 83.00% | 81.00% | 99.00% | 82.00% | 0.00% | 88.50% | 91.50% | 65.62% |
| ppl-spike-pinned-topk8 | 0.00% | 86.50% | 81.50% | 99.50% | 83.00% | 0.00% | 92.00% | 94.50% | 67.12% |
| ppl-spike-pinned-window100.0ms | 0.00% | 83.50% | 80.50% | 88.00% | 84.50% | 0.00% | 84.50% | 88.00% | 63.62% |
| ppl-spike-pinned-window1000ms | 0.00% | 83.00% | 80.50% | 99.00% | 88.00% | 0.00% | 92.50% | 95.50% | 67.31% |
| ppl-spike-pinned-window200.0ms | 0.00% | 86.50% | 83.50% | 98.50% | 88.50% | 0.00% | 92.50% | 95.00% | 68.06% |
| ppl-spike-pinned-window500.0ms | 0.00% | 83.50% | 79.50% | 100.00% | 84.50% | 0.00% | 95.50% | 96.00% | 67.38% |
| ppl-spike-topk1 | 52.00% | 70.00% | 62.50% | 88.00% | 83.00% | 51.50% | 66.50% | 84.00% | 69.69% |
| ppl-spike-topk16 | 52.00% | 73.00% | 74.00% | 96.00% | 91.50% | 49.00% | 75.50% | 94.50% | 75.69% |
| ppl-spike-topk2 | 49.50% | 70.50% | 64.50% | 94.50% | 84.50% | 49.00% | 71.50% | 89.50% | 71.69% |
| ppl-spike-topk4 | 52.00% | 68.00% | 67.00% | 97.00% | 86.00% | 50.50% | 73.50% | 92.50% | 73.31% |
| ppl-spike-topk8 | 51.50% | 68.50% | 73.00% | 96.50% | 88.00% | 50.00% | 79.00% | 93.50% | 75.00% |
| ppl-spike-window100.0ms | 51.50% | 74.00% | 74.50% | 96.50% | 86.50% | 51.00% | 84.50% | 90.50% | 76.12% |
| ppl-spike-window1000ms | 53.00% | 69.00% | 72.50% | 97.00% | 90.00% | 54.00% | 79.50% | 94.00% | 76.12% |
| ppl-spike-window200.0ms | 46.50% | 77.50% | 73.50% | 99.00% | 87.00% | 49.50% | 87.50% | 93.50% | 76.75% |
| ppl-spike-window500.0ms | 49.50% | 70.50% | 75.50% | 98.00% | 92.50% | 54.00% | 85.00% | 94.00% | 77.38% |
<!-- AUTO-GEN: EXPERIMENTAL RESULTS END -->
