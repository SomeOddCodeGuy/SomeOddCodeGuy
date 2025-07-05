<!-- Attribution for the github readme stats and the repos below that: https://github.com/anuraghazra/github-readme-stats -->
<!-- Awesome little widgets -->
<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=someoddcodeguy&hide=contribs" alt="SomeOddCodeGuy's GitHub stats">
</p>

## Top Repos
<p align="center">
<a href="https://github.com/someoddcodeguy/wilmerai">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=someoddcodeguy&repo=wilmerai" />
</a>
<a href="https://github.com/SomeOddCodeGuy/OfflineWikipediaTextApi">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=someoddcodeguy&repo=OfflineWikipediaTextApi" />
</a>
</p>

## Important Update 2025-07-05: Reddit Account Security Lockout

> On 2025-07-05, I was posting on LocalLlama when I received a warning of suspicious activity on the account,
> and that the account was locked out pending a password change. Unfortunately, while the red bar at the top vanished
> after the password change, the account has remained suspended. I have received no messages or email with further
> explanation.
>
> After going down a Google search rabbit hole on the issue, I have learned that it apparently is a really bad idea
> to use a VPN with Reddit. I confirmed in the Account IP history that my IP changed within a few minutes of me
> being suspended; likely due to my VPN app finding a new connection. Oops.
>
> I have reached out to the Reddit Admins via their contact forms, and am hopeful that they'll be able to get this
> resolved soon.
>
> That Reddit account contained 2+ years of benchmarks, tests, questions/answers and general observations going back
> to mid 2023; its' posts often get referenced in other places. While I am confident that the issue will *eventually*
> be resolved, I am concerned about how long that may take. Looking at posts of people who had similar experiences,
> some reported it taking as long as several months to hear back. As such, I have pulled down the information
> from the posts and will be looking for an alternative location to get that information back up and online.
>
> Sorry for the trouble, folks! Hopefully the admins will be able to get the issue fixed up quickly!
>
> -Socg


## About
***

<p align="center">
<img src="https://github.com/SomeOddCodeGuy/SomeOddCodeGuy/blob/main/SomeOddCodeGuy_Sway.gif" alt="SomeOddCodeGuy">
</p>

I'm a developer who's been visiting world of LLMs as a hobby since 2023. My main focus is on locally run, offline,
LLMs which I mostly use for even more hobby tinkering. 

I generally do most of my development on a local Git repository on my home network, and then push everything up here at once. 
I do most of my commits on weekends, and in some rare cases I might do one late at night on weekdays.

I'm quite passionate in regards to the power of workflows with LLMs, and as a developer I generally prefer more manual
chat-style interfacing with LLMs powered by workflows than I do leaving a task to an automated agent. There are some
exceptions, however; web searching is a great use of agents, IMO. 

But as a developer, with the current tech (as of 2025-03), I feel that I can iterate faster and cleaner sitting in 
between the AI and my code.



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

## Posts (Temporarily Unavailable)
***

### [My Home Setup](https://www.reddit.com/r/LocalLLaMA/comments/1i1kz1c/sharing_my_unorthodox_home_setup_and_how_i_use/)
- Last updated 2025-01
- I recently got an M3 Studio that I've added to the mix, allowing me to separate out coding models from general purpose
  models, and giving Roland its own box.

### [My Guide to How I Develop Using LLMs](https://www.reddit.com/r/LocalLLaMA/comments/1cvw3s5/my_personal_guide_for_developing_software_with_ai/)
- Guide is a bit older now, but still applies. I've automated a lot of this in workflows, but when I'm somewhere like
  my work, I'd still make use of these techniques.
- Many of my Wilmer workflows are in some part inspired by the general workflows I do here

### Mac Studio Speed Tests
- [M2 Ultra Mac Studio speed tests from freshly loaded models](https://www.reddit.com/r/LocalLLaMA/comments/1aucug8/here_are_some_real_world_speeds_for_the_mac_m2/)
- [M2 Ultra Mac Studio speed tests utilizing KoboldCpp's context shifting](https://www.reddit.com/r/LocalLLaMA/comments/1aw08ck/real_world_speeds_on_the_mac_koboldcpp_context/)
- [Comparison of M2 Max, M2 Ultra and RTX 4090 speeds](https://www.reddit.com/r/LocalLLaMA/comments/1fovw8h/low_context_speed_comparison_macbook_mac_studios/)
- [Comparison of M2 Ultra and M3 Ultra Speeds](https://www.reddit.com/r/LocalLLaMA/comments/1jaqpiu/mac_speed_comparison_m2_ultra_vs_m3_ultra_using/)
- [M3 Ultra running Command-A 111b and Llama 3.1 405b](https://www.reddit.com/r/LocalLLaMA/comments/1jcgonz/comment/mi244qd/?context=3)
- [M3 Ultra Deepseek V3 Run Speeds and Memory Costs](https://www.reddit.com/r/LocalLLaMA/comments/1jke5wg/m3_ultra_mac_studio_512gb_prompt_and_write_speeds/)
- [M3 Ultra R1-0528 Run Speeds and Memory Costs + MLA difference](https://www.reddit.com/r/LocalLLaMA/comments/1kzn4ix/running_deepseek_r1_0528_q4_k_m_and_mlx_4bit_on_a/)

### MMLU-Pro Home Runs To Compare Effects Of Quantization
- [All Category Test Across Multiple Quants of Llama 3 70b from q2 to q8](https://www.reddit.com/r/LocalLLaMA/comments/1ds6da5/mmlupro_all_category_test_results_for_llama_3_70b/)
- [Combined Test Results Including More Models Across Multiple Quants](https://www.reddit.com/r/LocalLLaMA/comments/1dx4sa7/mmlupro_combined_results_including_new_results/)

### Some Comments to Help New Users Learn Stuff
- [Starting Information About Local LLMs and Inference](https://www.reddit.com/r/LocalLLaMA/comments/1b6rqi5/comment/ktdwlbl/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1)
- [How Prompt Templates Work](https://www.reddit.com/r/LocalLLaMA/comments/1gddzat/comment/lu0z4aw/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)

***

<p align="center">
<img src="https://github.com/SomeOddCodeGuy/SomeOddCodeGuy/blob/More_Updates/Socg_Cat_Cards.gif" alt="SomeOddCodeGuy">
</p>
