---
type: service
id: anthropic-claude
title: Anthropic Claude
description: "Anthropic Claude API service for LLM inference"
tags: [Production]
connections: []
---

## Provider

Anthropic

## Endpoint

https://api.anthropic.com/v1

## Authentication

API Key: `{{ANTHROPIC_API_KEY}}`

## Models

- claude-opus-4 — highest capability, complex reasoning
- claude-sonnet-4 — balanced speed and quality
- claude-haiku-4 — fastest, lowest cost

## Notes

- Supports tool use, vision, and extended thinking
- Max context: 200k tokens
