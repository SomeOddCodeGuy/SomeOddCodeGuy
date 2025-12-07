## About
***

<p align="center">
<img src="https://github.com/SomeOddCodeGuy/SomeOddCodeGuy/blob/main/SomeOddCodeGuy_Sway.gif" alt="SomeOddCodeGuy">
</p>

I'm a developer who's been visiting the world of LLMs as a hobby since 2023. My main focus is on locally run, offline,
LLMs which I mostly use for even more hobby tinkering. 

I generally do most of my development locally, and I do most of my work on weekends. Usually I'm too tired after work
to do much in the weekday evenings.

I'm quite passionate in regards to the power of workflows with LLMs, and as a developer I generally prefer more manual
chat-style interfacing with LLMs powered by workflows than I do leaving a task to an automated agent. There are some
exceptions, however; web searching is a great use of agents, IMO. 

But as a developer, with the current tech (as of 2025-08), I feel that I can iterate faster and cleaner sitting in 
between the AI and my code.

> Update: 2025-12-07
>
> I haven't vanished or quit working on Wilmer; I'm currently in the middle of a job transition, and it's taking
> a fair bit of my time. I'm still doing Wilmer work in the background, but I don't have a lot of time to do clean
> testing and ensure a push is good, so I'm holding off pushing anything until I hit the point that I can. I'm using Wilmer
> daily, so don't take my absence as meaning I gave up on it. Far from it. I've just been spending more time making
> workflows than updating the code itself.


## [WilmerAI](https://github.com/SomeOddCodeGuy/WilmerAI)
***
I started Wilmer during the Llama 2 era based on the idea that open-weight models at the time were weak as generalists
compared to the big proprietary models like ChatGPT; however, individual fine-tunes within scoped domains (like coding
or medical) could often compete with those big models. My goal has always been to try to find a way, either through
routing or workflows, to help my local models keep pace with the big APIs. 

Obviously, modern open-weight models are strong enough to not need that help nearly as much, but that just means the same 
methods can push those models even farther.

I'm not a python developer by trade; I picked it up to work on Wilmer, and I've been learning it ever since. Some
of the mess in the codebases here are tech debt due to my fumbling along and learning early on as I started to 
understand it more. In my day job, I'm a dev manager that mostly works with C# and web tech.

## Posts
***

### [Breakdown of Understanding Llama.cpp Offloading for MoE Models](https://www.someoddcodeguy.dev/understanding-moe-offloading/)
- This started as a reddit post and then I decided to make it into an article, since I think it was something a lot of folks
  were interested in reading.

### [My Guide to How I Develop Using LLMs](https://www.someoddcodeguy.dev/my-personal-guide-for-developing-software-with-ai-assistance/) [[Github Mirror](Github_Images/My%20personal%20guide%20for%20developing%20software%20with%20AI%20assistance%20r_LocalLLaMA.png)]
- Guide is a bit older now, but still applies. I've automated a lot of this in workflows, but when I'm somewhere like
  my work, I'd still make use of these techniques.
- Many of my Wilmer workflows are in some part inspired by the general workflows I do here

### Mac Studio Speed Tests
- [M2 Ultra Mac Studio speed tests from freshly loaded models](https://www.someoddcodeguy.dev/here-are-some-real-world-speeds-for-the-mac-m2-ultra-in-case-you-were-curious/) [[Github Mirror](Github_Images/Here%20Are%20Some%20Real%20World%20Speeds%20For%20the%20Mac%20M2%20Ultra%20In%20Case%20You%20Were%20Curious%20r_LocalLLaMA.png)]
- [M2 Ultra Mac Studio speed tests utilizing KoboldCpp's context shifting](https://www.someoddcodeguy.dev/real-world-speeds-on-the-mac-koboldcpp-context-shift-edition/) [[Github Mirror](Github_Images/Real%20World%20Speeds%20on%20the%20Mac%20Koboldcpp%20Context%20Shift%20Edition!%20r_LocalLLaMA.png)]
- [M3 Ultra running Command-A 111b and Llama 3.1 405b](https://www.someoddcodeguy.dev/running-llama-3-1-405b-q6-and-command-a-111b-q8-on-m3-ultra-mac-studio/) [[Github Mirror](Github_Images/Has%20anyone%20tried%2070B%20LLMs%20on%20M3%20Ultra%20r_LocalLLaMA.png)]
- [M3 Ultra Deepseek V3 Run Speeds and Memory Costs](https://www.someoddcodeguy.dev/m3-ultra-mac-studio-512gb-prompt-and-write-speeds-for-deepseek-v3-0-671b-gguf-q4_k_m-for-those-curious/) [[Github Mirror](Github_Images/M3%20Ultra%20Mac%20Studio%20512GB%20prompt%20and%20write%20speeds%20for%20Deepseek%20V3%20671b%20gguf%20q4_K_M%20for%20those%20curious%20r_LocalLLaMA.png)]
- [M3 Ultra R1-0528 Run Speeds and Memory Costs + MLA difference](https://www.someoddcodeguy.dev/running-deepseek-r1-0528-q4_k_m-and-mlx-4-bit-on-a-mac-studio-m3/) [[Github Mirror](Github_Images/Running%20Deepseek%20R1%200528%20q4_K_M%20and%20mlx%204-bit%20on%20a%20Mac%20Studio%20M3%20r_LocalLLaMA.png)]
- [M3 Ultra running Qwen3 235b, GPT-OSS-120b, GLM 4.5, and Deepseek V3.1](https://www.someoddcodeguy.dev/mac-studio-m3-ultra-speeds-for-qwen3-235b-gpt-oss-120b-glm-4-5-and-deepseek-v3-1/)
- [M3 Ultra comparison of Q8_0 and MXFP4 ggufs for GLM 4.6](https://www.someoddcodeguy.dev/glm-4-6-mxfp4-vs-q8_0-gguf-speeds-on-mac-m3-ultra/)

## Comparison Speed Tests
- [Comparison of M2 Max, M2 Ultra and RTX 4090 speeds](https://www.someoddcodeguy.dev/mmlu-pro-combined-results-model-quantization-comparison/) [[Github Mirror](Github_Images/Low%20Context%20Speed%20Comparison%20Macbook%20Mac%20Studios%20and%20RTX%204090%20r_LocalLLaMA.png)]
- [Comparison of M2 Ultra and M3 Ultra Speeds](https://www.someoddcodeguy.dev/mac-speed-comparison-m2-ultra-vs-m3-ultra-using-koboldcpp/) [[Github Mirror](Github_Images/Mac%20Speed%20Comparison%20M2%20Ultra%20vs%20M3%20Ultra%20using%20KoboldCpp%20r_LocalLLaMA.png)]

### MMLU-Pro Home Runs To Compare Effects Of Quantization
- [Combined Test Results Including More Models Across Multiple Quants](https://www.someoddcodeguy.dev/mmlu-pro-combined-results-model-quantization-comparison/) [[Github Mirror](Github_Images/MMLU-Pro%20Combined%20Results-%20Including%20New%20Results%20for%20L3%208b%20SPPO%20Hermes%202%20Theta%20L3%208b%20and%20Some%20Golden%20Oldies%20Like%20Dolphin%202.5%20Mixtral%20Nous%20Capybara%2034b%20and%20WizardLM-2-7b%20r_LocalLLaMA.png)]


***

<p align="center">
<img src="https://github.com/SomeOddCodeGuy/SomeOddCodeGuy/blob/main/Socg_Cat_Cards.gif" alt="SomeOddCodeGuy">
</p>
