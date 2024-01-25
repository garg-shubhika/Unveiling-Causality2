# This folder deals with fixing data issues in augmented sentences.

- Converting arg and sig in causal_text_w_pairs into uppercase.
- Deleting words in causal_text_w_pairs appearing outside of square brackets.
  ## Example:
  atomic number ['<ARG1>opp atomic number atomic number stages dharna in atomic number karna assembly</ARG1> <SIG0>over</SIG0> <ARG0>finance bill</ARG0>']
  ## Output:
  ['<ARG1>opp atomic number atomic number stages dharna in atomic number karna assembly</ARG1> <SIG0>over</SIG0> <ARG0>finance bill</ARG0>']

Then create text column by removing arg,sig and brackets again
