# Eco-chat
Reservoir — Eco Mode Chat on Claude
A lightweight chat interface built on top of Claude (claude-sonnet-4-6) that visualizes the real energy and water cost of AI conversations.
Most people don't think about what happens behind the scenes when they send a message to an AI. Every reply requires computation, and computation requires energy — and data centers use significant amounts of water for cooling. Reservoir makes that cost visible.
How it works
Toggle Eco Mode on and Claude is instructed to respond with maximum concision — no preamble, no filler, no unnecessary caveats. Toggle it off and Claude responds normally. The water gauge on the left fills up as you chat, showing an illustrative estimate of cooling water saved compared to a typical unconstrained reply.
Features

Eco Mode toggle that switches Claude's system prompt in real time
Animated water gauge tracking estimated millilitres of cooling water saved
Per-reply token count and output trimming stats
Full conversation history maintained across turns
No API key required — runs on your own Claude session
 A Claude chat interface that visualizes the energy and water cost of AI replies. Toggle Eco Mode to get concise answers and watch the water gauge fill with what you saved. Runs on your own Claude account. No API key needed.
