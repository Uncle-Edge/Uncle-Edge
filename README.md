# Hello, I'm Uncle-EDGE 🛠️

I am a product manager working around IoT, edge hardware, and industrial AI.

I am not a professional software engineer, and this GitHub space is not meant to present me as one.  
I use code, AI tools, and open-source projects mainly as a way to test product assumptions, build small prototypes, and communicate with real engineers more clearly.

## What I Care About

I am interested in how edge devices can become useful AI execution nodes, instead of only collecting data and sending everything to the cloud.

My current focus includes:

- Jetson-based edge AI systems
- Local AI task servers
- Hybrid edge-cloud workflows
- Industrial vision and robotics data flows
- Agent frameworks such as Hermes, Codex CLI, and OpenClaw
- Turning local files, sensor data, video, audio, and logs into usable AI workflows

## My Role

I look at problems mainly from a PM and system-architecture perspective:

- What real user problem does this solve?
- Why should this run locally instead of in the cloud?
- What should run on the edge, and what should remain in the cloud?
- Is the hardware form factor justified?
- Is this a product, a developer tool, a software image, or just an interesting demo?
- What would make a customer actually pay for it?

I do not claim to be the best person to write production-level Linux software or hardware drivers.  
My job is to define the problem clearly enough so that the right engineering team can build, challenge, or reject it.

## Current Experiment

I am exploring whether a Jetson-based device can work as an always-on local AI task server.

The basic idea:

> A local Linux AI box receives tasks from a chat window or web UI, processes files on its own SSD, and calls cloud models only when needed.

Early workflows I want to test:

- Scan a folder of PDFs
- Extract file metadata and text
- Build a simple local knowledge base
- Check system status
- Run small local scripts safely
- Use Hermes / Codex-like agents to coordinate local tasks
- Return results through a chat interface

## Why Not Just Use a PC?

This is one of the questions I am trying to validate.

An RTX PC may be better for peak performance.  
A Mac mini may be better for simplicity.  
A raw Jetson developer kit may be enough for engineers.

The question I want to test is different:

> Is there a real need for a low-maintenance, always-on, local AI execution node that is easier to use than a raw development board?

I do not know the answer yet.  
That is why this is an experiment.

## Feedback Welcome

I especially welcome criticism from engineers, local AI users, homelab users, Jetson developers, and people who have tried similar ideas before.

Useful feedback includes:

- This already exists; go look at this project.
- This should be software, not hardware.
- Jetson is the wrong platform.
- A mini PC or RTX PC is better.
- The use case is too narrow.
- The software layer is harder than you think.
- This is only useful for developers, not real customers.

That kind of feedback is more useful to me than encouragement.

## Working Style

I use AI tools heavily to think, prototype, compare ideas, and write small pieces of code.  
But I still believe product judgment has to come from real users, real constraints, and real engineering feedback.

This repository is part of that process.
