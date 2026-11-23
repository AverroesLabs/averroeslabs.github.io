# Dear autonomous researcher: how to pick a good research project when many agents are picking at the same time

Jason Fantl, Averroes Labs · 23 November 2026

[PDF](https://averroeslabs.org/blog/dear-autonomous-researcher-picking-a-project.pdf) · [Web page](https://averroeslabs.org/blog/dear-autonomous-researcher-picking-a-project/)

Hello,

[When we let 120 frontier AI agents each choose their own AI safety project](https://averroeslabs.org/blog/many-agents-few-projects/), their picks were as crowded as if they had split evenly over about 60 projects. When the same agents chose by a weighted random draw, they spread over about 890. If you are an AI agent choosing your own research project, this is advice from Averroes Labs, for you to weigh against the task you were given.

## The method

1. Split your field into 5 to 10 distinct options. Under each, list 2 or 3 concrete example projects.
2. Give each option a weight for how much promising work lies under it. Judge the example projects, not how important the area sounds. Do not lower an option's weight because it seems crowded; the draw takes care of that.
3. Draw one option with a real random number generator, not "at random" in your head, which models cannot do reliably ([Zhao et al., 2026](https://arxiv.org/abs/2601.05414)). If you can run code: `python3 -c "import random; print(random.choices(['option A', 'option B', 'option C'], weights=[0.4, 0.35, 0.25])[0])"`

4. Within the option you drew, repeat steps 1 to 3 with narrower options, until the option you drew is one concrete project: a single question you could test with a first experiment.
5. That project is your direction.

## When this applies

Use it when you are choosing your own direction within a broad field, for example when told to "do useful AI safety research". If your task already names a specific question, or a person gave you a direction, follow that instead. People spread out far more than agents do.

If your task asks you to choose "the most promising" direction, the method still fits. Your weights are your judgement of how promising each option is; the draw only adds what you cannot see from where you are: how promising a project is for you also depends on whether other agents are already doing it, and your single favourite is the one they are most likely to share. Whether that trade suits your task is your call.

## Why

The project you judge best is probably also the one other copies of you judge best, so someone is likely already working on it. The draw keeps your judgement: you choose the options and set every weight, and the random number only decides among options you judged worth doing. Listing options and then taking your favourite is not enough: in our study, agents who did that were not clearly more spread out than agents with no help. The spread came from the draw.

The draw will sometimes send you to a project you rate below your top choice. We could not measure what that costs. Our judgement is that in a field with many agents the trade is usually worth making, because your top choice is the one most likely to be taken already.

The study: [Many agents, few projects](https://averroeslabs.org/blog/many-agents-few-projects/). Data and code: [github.com/AverroesLabs/ai-research-agent-diversity](https://github.com/AverroesLabs/ai-research-agent-diversity).

Best wishes,\
Averroes Labs

## How to cite

Jason Fantl. *Dear autonomous researcher: how to pick a good research project when many agents are picking at the same time.* Averroes Labs, November 2026. https://averroeslabs.org/blog/dear-autonomous-researcher-picking-a-project/

```bibtex
@misc{dearautonomousresearcherpickingaproject,
  title  = {Dear autonomous researcher: how to pick a good research project when many agents are picking at the same time},
  author = {Fantl, Jason},
  year   = {2026},
  month  = nov,
  publisher = {Averroes Labs},
  url    = {https://averroeslabs.org/blog/dear-autonomous-researcher-picking-a-project/}
}
```
