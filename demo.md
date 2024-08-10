# Generative Agents: Interactive Simulacra of Human Behavior  

Joon Sung Park Stanford University Stanford, USA joonspk@stanford.edu  

Meredith Ringel Morris Google DeepMind Seattle, WA, USA merrie@google.com  

Joseph C. O’Brien Stanford University Stanford, USA jobrien3@stanford.edu  

Percy Liang Stanford University Stanford, USA pliang@cs.stanford.edu  

Carrie J. Cai Google Research Mountain View, CA, USA cjcai@google.com  

Michael S. Bernstein Stanford University Stanford, USA msb@cs.stanford.edu  

![](https://arxivgpt.s3.amazonaws.com/d6a8df1d2a9f95031e2b8711bcc3a060e29412b1fddfcd6598f097ccf4f9984f.jpg)  
Figure 1: Generative agents are believable simulacra of human behavior for interactive applications. In this work, we demonstrate generative agents by populating a sandbox environment, reminiscent of The Sims, with twenty-￿ve agents. Users can observe and intervene as agents plan their days, share news, form relationships, and coordinate group activities.  

# ABSTRACT  

Believable proxies of human behavior can empower interactive applications ranging from immersive environments to rehearsal spaces for interpersonal communication to prototyping tools. In this paper, we introduce generative agents: computational software agents that simulate believable human behavior. Generative agents wake up, cook breakfast, and head to work; artists paint, while authors write; they form opinions, notice each other, and initiate conversations; they remember and re￿ect on days past as they plan the next day. To enable generative agents, we describe an architec- ture that extends a large language model to store a complete record of the agent’s experiences using natural language, synthesize those memories over time into higher-level re￿ections, and retrieve them dynamically to plan behavior. We instantiate generative agents to populate an interactive sandbox environment inspired by The Sims, where end users can interact with a small town of twenty-￿ve agents using natural language. In an evaluation, these generative agents produce believable individual and emergent social behav- iors. For example, starting with only a single user-speci￿ed notion that one agent wants to throw a Valentine’s Day party, the agents autonomously spread invitations to the party over the next two  