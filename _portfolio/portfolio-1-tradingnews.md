---
title: "TradingNews.press — AI Financial News Analysis Platform"
excerpt: "AI-powered financial news analysis and investment signal generation platform built with multi-agent workflow orchestration using LangGraph.<br/>"
collection: portfolio
---

## Overview

[TradingNews.press](https://tradingnews.press) is an AI-powered platform for automated financial news analysis and investment signal generation, developed from inception during my internship at **Bauhinia AI Limited** (affiliated with Prof. Kani Chen's Lab at HKUST).

## Technical Highlights

### CRDR Workflow Orchestration
Architected a **Channel→Relevant→Decision→ReAct** workflow using LangGraph state machines with parallel processing:
- **Channel**: Extracts assets via JSON Schema-constrained outputs
- **Relevant**: Enriches context with market data
- **Decision**: Aggregates analyst signals from multiple agents
- **ReAct**: Refines low-confidence results through iterative reasoning

### Multi-Agent System
Developed **7 specialized financial analysis agents** with:
- Custom prompt engineering for financial domain expertise
- Pydantic output schemas for structured reasoning chains
- Production-grade error handling with fallback strategies and automatic retry logic

### Text-Grad Optimization
Implemented a **text-grad architecture** featuring:
- Stock price tracking and prompt propagation computation graph
- LLM-as-a-judge framework for evaluating agent performance
- Learnable prompt components optimization across agents
- Data flywheel for continuous improvement

## Impact
The platform is currently **live and serving active users**, providing real-time financial news analysis and investment signal generation.
