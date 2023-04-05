# [[AI CONNECT] 노트북으로 GPT 맛보기(Korean Abstractive Summary Competition)](https://aiconnect.kr/competition/detail/223)


<img width="799" alt="image" src="https://user-images.githubusercontent.com/100005890/230086342-815b5208-67bb-4ec0-907a-4fdaa8fd4e87.png">

## Competition Info
 - Period: 2023.03.20 - 2022.03.30
 - TEAM_NAME : `Kuggle`
 - TASK: `Abstractive Summary`
 - Evaluation Metric: `ROUGE-1(F1)`, `ROUGE-2(F1)`, `ROUGE-L(F1)` | `Tokenizer = Mecab`
 - Environment: `Colab`
 

## Result 
 -  ![public 13rd](https://img.shields.io/badge/PUBLIC-13rd-red?style=plastic)  / 418 teams (total 601 participants)
 -  ![private 9th](https://img.shields.io/badge/PRIVATE-9th-red?style=plastic)  / 418 teams (total 601 participants)
 
## Members

임승섭|신은빈|이준희|김찬영
:-:|:-:|:-:|:-:
|[seopp](https://github.com/seopp)|[eunbinni](https://github.com/eunbinni)|
|y7511204@naver.com|dnflrhra@naver.com|

---

 
## Why Joined this Competition
- Studying `NLG` task; models, how to fine-tune, ... 
- Needs Experience for `NLG` task
  - Never experienced before


## What I learned 
- how to fine-tune LLM with `LoRA`(`huggingface/peft`)
- Evaluation Metric for `NLG` TASK : `ROUGE`
- Inference Strategies of `NLG` `model: model.generate( num_beams, min_length, max_length, ... )`

## What I'm impressed by


## What I missed


## References
- [🤗Huggingface - Summarization](https://huggingface.co/course/chapter7/5?fw=pt)
- [🤗Huggingface - BartForConditionalGeneration](https://huggingface.co/docs/transformers/v4.27.1/en/model_doc/bart#transformers.BartForConditionalGeneration)
- [KoBART Summarization with PL](https://github.com/seujung/KoBART-summarization)
  - [Rouge Class (Mecab)](https://github.com/seujung/KoBART-summarization/blob/main/rouge_metric.py)
- [[LoRA] allow fine-tuning of the text encoder with LoRA (using peft) #2719](https://github.com/huggingface/diffusers/issues/2719)
- [Efficient Large Language Model training with LoRA and Hugging Face](https://www.philschmid.de/fine-tune-flan-t5-peft)
- [Transformer로 텍스트를 생성하는 다섯 가지 전략](https://littlefoxdiary.tistory.com/46)
