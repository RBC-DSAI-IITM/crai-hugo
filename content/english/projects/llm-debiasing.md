---
title: "LLM agents for debiasing and explanations"
image: "/images/debiasing.png"
researchers: ["C. Subramaniam"]
filters: [making-ai-understandable]
tags: ["llm-agents", "safe-ai"]
draft: false
---

<style>

    .rectangle {
  height: 200px;
  width: 400px;
  background-color: #4cb4ac;
  border-radius:25px;
   display: flex;
   flex-direction: column;
   justify-content: center;
   align-items: center;
   text-align: center;
}
    
    
</style>

<strong>LLM based systems – WHAT are they?</strong>

<ul style="list-style-type:disc;">
<li>Systems where LLMs form the core reasoning engine</li>
<li>These LLMs interact with the outside world (– vs. – Standalone LLMs)</li>
<li>LLM agents are subsumed into it</li>
</ul>
<br>

<div class="img-div">
    <img src="/images/debiasing-full.png" style="width: 70%; height: 70%;">
</div>

<br>

<strong>A few examples of LLM systems/agents</strong>

<ul style="list-style-type:disc;">
<li>Retrieval augmented generation (RAG)</li>
<li>LLMs using tools</li>
<li>LLM-powered workflow chains (e.g. using LangChain)</li>
<li>Goal-based agents</li>
<li>LLM-powered AI software engineering teams (e.g. CrewAI)</li>
</ul>

And many more...

<br>

<strong>WHY is it important to look at LLM-based systems?</strong>

<ul style="list-style-type:disc;">
<li>Orgs have complex workflows into which LLMs need to be integrated</li>
<li>It can be very expensive to fine-tune large LLMs</li>
<li>Can accomplish more complex tasks</li>
<li>RAI concerns/tradeoffs can be quite different for different applications</li>
<li>It allows components to evolve independently</li>
</ul>

<br>

<strong>Responsible AI (RAI) intersection LLM agents</strong>
<br>
<strong><i>A complex space on its own, and is fast evolving</i></strong>

<div class="contdiv">
    <div class="row">
        <div class="col-md-6">
            <div class="rectangle">
            <strong>Elevated RAI concerns</strong>
            <i>in LLM systems</i>
            </div>
        </div>
        <div class="col">
            <ul>
                <li>Privacy: leak of PII data</li>
                <li>Data ownership: copyrighted material used as part of subtask</li>
                <li>Deception: emergence of deception</li>
                <li>Etc...</li>
            </ul>
        </div>
    </div>
        <div class="row">
        <div class="col-md-6">
            <div class="rectangle">
                <strong>New Approaches to RAI</strong>
                <i>enabled by LLM systems</i>
            </div>
        </div>
        <div class="col">
            <ul>
                <li>Critique LLMs</li>
                <li>Programmable guardrails</li>
                <li>Constitutional AI</li>
                <li>Traceability (e.g. using RAGs).</li>
                <li>Etc...</li>
            </ul>
        </div>
    </div>
</div>