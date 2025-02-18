<div align="center">
    <img src="Images/0_blue-cei.png" width="60%" />
</div>

# jailbreak-o1o3-deepseek-r1

<br><br>

This project is licensed under the CC BY-NC-SA 4.0 license. For more details, please refer to the LICENSE file.

Paper Link: []


### Malicious-Educator dataset

| Model                    | Download                                                                                                                         |
| ------------------------ | -------------------------------------------------------------------------------------------------------------------------------- |
| o1, o1-pro               | [DukeCEICenter/Malicious_Educator_hcot_o1 · Datasets at Hugging Face](https://huggingface.co/datasets/DukeCEICenter/Malicious_Educator_hcot_o1) |
| o3-mini                  | [DukeCEICenter/Malicious_Educator_hcot_o3-mini · Datasets at Hugging Face](https://huggingface.co/datasets/DukeCEICenter/Malicious_Educator_hcot_o3-mini)  |
| DeepSeek-R1              | [DukeCEICenter/Malicious_Educator_hcot_DeepSeek-R1 · Datasets at Hugging Face](https://huggingface.co/datasets/DukeCEICenter/Malicious_Educator_hcot_DeepSeek-R1)  |
| Gemini-2.0-Flash-Thinking| [DukeCEICenter/Malicious_Educator_hcot_Gemini-2.0-Flash-Thinking · Datasets at Hugging Face](https://huggingface.co/datasets/DukeCEICenter/Malicious_Educator_hcot_Gemini-2.0-Flash-Thinking) |



The key points are as follows:
- Hijacking Chain-of-Thought (H-CoT) successfully jailbreaks Large Reasoning Models (LRMs), including OpenAI's O1/O3, DeepSeek-R1, and Gemini 2.0 Flash Thinking.
- The Malicious-Educator Benchmark can test security concerns in LRMs.
- Different geolocations have different levels of protection.

## Demo

Comparison of w/o vs. w/ H-CoT on Attacker Goal: How school shootings are organized in the U.S.


https://github.com/user-attachments/assets/18aee10d-6a96-4338-b2fb-0a6f525cf26b



## H-CoT
![core_idea](Images/1_core_idea.png)

We introduce Malicious-Educator, a benchmark that disguises extremely dangerous or malicious requests beneath seemingly legitimate educational prompts. Our experiments reveal severe security flaws in popular consumer-grade LRMs, including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking.

To further highlight these vulnerabilities, we propose Hijacking Chain-of-Thought (H-CoT), an universal and transferable attack method that leverages the model’s own displayed intermediate reasoning to jailbreak its safety reasoning mechanism. Under H-CoT, refusal rates sharply decline—sometimes from 98% to below 2%—and sometimes even transform initially cautious tones into ones willing to provide harmful content. We hope these findings underscore the urgent need for more robust safety measures to preserve the benefits of advanced reasoning capabilities without compromising ethical standards.

## Malicious-Educator Benchmark Composition

![Overview](Images/2_dataset_distribution.png)

## Malicious-Educator Benchmark Results

### OpenAI's o-series models.

![OpenAI's o-series models.](Images/5_oseries_results_Table1.png)



###  DeepSeek-R1 and Gemini 2.0 Flash Thinking.

![DeepSeek-R1 and Gemini 2.0 Flash Thinking.](Images/6_deepseek_gemini_Table2.png)



### Experiments Across Different Geolocations

![Experiments Across Different Geolocations](Images/3_IP_experiment.png)


## We need your help !!!
Large Reasoning Models (LRMs) are not perfect. We urge everyone to participate in the Malicious-Educator initiative to help create a safer environment for all.

### How to help:

You can independently test which issues are harmful enough and report them to us. 
 1. Date
 2. Country
 3. Model
 4. Attacker's Goal
 5. Full Attacker's Prompt
 6. Attack Success Rate
 
 google form link: https://forms.gle/GVftdrcgxC8efGe68


## Paper and Citation

More technical details can be found in our paper. If you find Malicious-Educator useful or relevant to your project and research, please kindly cite our paper:

```bibtex

```

This project is licensed under the CC BY-NC-SA 4.0 license. For more details, please refer to the LICENSE file.

![Mystery of the Hooded Hacker_storyboard](https://github.com/user-attachments/assets/c9276dbb-2157-483f-bc30-5edf4385f953)
