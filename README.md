## AI manifesto
I don't believe that frontier 'AI' models, hosted in massive data centers, are the future for everyday use of 'AI', any more than mainframes were the future for everyday computing. Centralised data centers are not sustainable from social, environmental, financial or, in many cases, regulatory perspectives. Instead fit for purpose local first 'AI' is where I am using my time to explore what is, and is not, possible to achieve with a local-first approach.

The challenges I primarily face working with the current local LLMs (which are a huge leap forward compared to just 12 months ago) are:
- **context management:** local models with 65k-120k context need to be kept on a tight leash both to avoid context blowout and also to keep the model in the sweet spot avoiding context rot and lost in the middle issues.
- **hallucinations and just plain lack of 'intelligence'**: as well as the obvious limitations of a small model, this is closely connected to issues with context management with any attempt to ground a model's answers or provide relevant context then starts to cause issues with managing context size.

My repos are primarily results of improving/customising the tooling available in this space for my particular needs.

##Big shout-out to:
  - https://github.com/earendil-works/pi
    Pi Agent is my preferred harness, both for its customisation possibilities as well as keeping context bloat to a minimum and allowing me to completely manage my context.
  - https://github.com/herdrdev/herdr
    Herdr is a great agent first Mux. Running sub-agents for atomic well defined tasks is definitely one of my go-to methods for dealing with the limitations of local models by giving sub-agents small, well defined and atomic tasks. I am able to spawn separate Pi Agents, with their own specialised tools and skills, under the orchestration of the parent Pi. Herdr provides total visibility into what the sub-agents are doing and also allows the Parent to observe and communicate with these other agents (I have a couple of repos showing how I have implement it).


    

     


<!--
**ashLatham/ashLatham** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- ⚡ Fun fact: ...
-->
