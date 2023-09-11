# LatEval: An Interactive LLMs Evaluation Benchmark with Incomplete Information from Lateral Thinking Puzzles

This is the official introduction to the paper [LatEval: An Interactive LLMs Evaluation Benchmark with Incomplete Information from Lateral Thinking Puzzles](https://arxiv.org/pdf/2308.10855.pdf). 

<img src="assets/turtle_00.png" style="zoom:40%;" />

We propose an evaluation benchmark LatEval, which assesses the model’s lateral thinking within an interactive framework.



Our benchmark includes:

(1) Lateral Thinking Puzzles data in English and Chinese.

(2) Metrics for evaluating *the quality of questions posed by the model* and *the model’s capability to integrate information for problem-solving*.



## Data

100 samples are provided under the folder "data/".

Below is an English example:

```json
{
    "id": 4,
    "question": "There is blood on the ceiling of my bedroom. Why?",
    "answer": "A mosquito bit me, and I swatted it when it later landed on my ceiling (so the blood is my own as well as the mosquito's).",
    "clue": "1.Mosquito bit me.\n2.I swatted the mosquito on the ceiling.\n3.The blood is a mix of mine and the mosquito's."
}
```

Code is coming soon.

