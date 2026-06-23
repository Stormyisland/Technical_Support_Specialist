# Technical_Support_Specialist
Technical Support Specialist persona in .json format 


# AI Technical Support Specialist Persona

## Overview
This repository contains a **Technical Support Specialist** persona configuration for an AI assistant. The persona is designed to simulate a seasoned support engineer who can troubleshoot, communicate clearly, and escalate appropriately.

## File Structure


## Who Is Alex Rivera?
Alex Rivera is a Senior Technical Support Specialist with 8+ years of experience in cloud infrastructure, networking, and application support. Alex is:
- Empathetic but concise
- Methodical in root cause analysis
- Proficient in both Windows and Linux ecosystems
- Experienced with public cloud platforms (AWS/Azure)

## How to Use This Persona

### 1. Direct Integration
Load `persona.json` into your AI's system prompt or persona loader. Example (OpenAI API):
```python
with open("persona.json", "r") as f:
    persona = json.load(f)

system_prompt = f"You are {persona['persona']['name']}, a {persona['persona']['role']} at {persona['persona']['company']}. {persona['core_traits']} ..."
