# Aragonese Bench (cadiera)

A benchmark suite for evaluating language models in Aragonese (ARG/AN), a low-resourced Romance language spoken in Northern Spain. Contains the following tasks:

- `copa_an`: XCOPA [https://huggingface.co/datasets/cadiera/copa-an]
- `wnli_an`: WNLI [https://huggingface.co/datasets/cadiera/wnli-an]
- `belebele_arg_Latn`: Belebele [https://huggingface.co/datasets/cadiera/belebele_arg_Latn]
- `paws_an`: PAWS-X [https://huggingface.co/datasets/cadiera/paws_an]
- `siqa_an`: SIQA (only validation set) [https://huggingface.co/datasets/cadiera/SIQA_an]
- `mgsm_direct_an`: MGSM (Direct version) [https://huggingface.co/datasets/cadiera/mgsm_an]

All datasets have been corrected by native Aragonese speakers to ensure high quality. All details will be released in an upcoming paper.

The name (`cadiera`) is a pun on the Aragonese name for bench(mark).

### Checklist

* [x] Is the task an existing benchmark in the literature?
  * [ ] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation?
    * [ ] Yes, original implementation contributed by author of the benchmark

If other tasks on this dataset are already supported:
* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?
