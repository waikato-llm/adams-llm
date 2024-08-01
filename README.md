# adams-llm
[ADAMS](https://adams.cms.waikato.ac.nz) workflows for dealing with LLM datasets etc.

## Workflows

* [compare-translated-alpaca.flow](compare-translated-alpaca.flow) - allows comparing
  original and translated records (Alpaca JSON format) and whether to keep or discard
  them (i.e., cleaning up a dataset).
* [kb_json_to_csv.flow](kb_json_to_csv.flow) - converts the JSON files generated from
  a `kb-eval` script into a CSV file for analysis ([example docker image](https://github.com/waikato-llm/huggingface_transformers/tree/main/4.43.1_cuda12.1_langchain)).

