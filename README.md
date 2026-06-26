# Anonymous Review Data Package

This branch contains the de-identified JSONL data files used for the manuscript's fine-tuning and evaluation workflow.

## Files

- `train_data.jsonl`: training file in chat/messages format. It includes stance examples and background-QA examples used during fine-tuning.
- `validation_data.jsonl`: validation file in chat/messages format.
- `test_data.jsonl`: test file in chat/messages format.

## Label Meaning

For stance-classification examples, the assistant message is the gold label:

- `POSITIVE`: anti-recall stance, opposition to recalling the target legislator.
- `NEGATIVE`: pro-recall stance, support for recalling the target legislator.

These are stance labels, not sentiment labels.

## Review Note

This is an anonymous review package. Author names, affiliations, public repository URL, and DOI are withheld until acceptance. Raw platform payloads, account identifiers, profile data, and direct platform metadata are not included.

A persistent DOI and full public repository metadata will be added after acceptance.
