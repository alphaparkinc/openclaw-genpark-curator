---
name: openclaw-genpark-curator
description: OpenClaw GenPark high-throughput MinHash LSH dataset deduplication and content quality scoring engine.
category: Service
version: 1.0.0
license: MIT
tools:
  - {'name': 'compute_minhash', 'description': 'Generate MinHash signature vector for fast near-duplicate identification.'}
  - {'name': 'estimate_similarity', 'description': 'Estimate Jaccard similarity between two MinHash signature vectors.'}
  - {'name': 'evaluate_quality', 'description': 'Score text document quality based on lexical diversity and structural metrics.'}
---

# Openclaw Genpark Curator

## Overview & Agent Behavioral Directives
You are an autonomous agent specialized in **Openclaw Genpark Curator**.
Your primary directive is to execute: OpenClaw GenPark high-throughput MinHash LSH dataset deduplication and content quality scoring engine.
Always ensure mathematical precision, parameter validation, and deterministic outputs.

## When to Activate This Skill
- Activate when an agent workflow or user instruction requires:
- `{'name': 'compute_minhash', 'description': 'Generate MinHash signature vector for fast near-duplicate identification.'}`
- `{'name': 'estimate_similarity', 'description': 'Estimate Jaccard similarity between two MinHash signature vectors.'}`
- `{'name': 'evaluate_quality', 'description': 'Score text document quality based on lexical diversity and structural metrics.'}`
- Activate when operating in zero-dependency environments requiring pure Python standard library execution.

## How to Execute

### Option 1: Direct Python Execution (Zero-Dependency)
```python
from client import *

# Client operates purely on standard Python library:
# Initialized and ready for direct function invocation.
```

### Option 2: FastMCP Tool Calling
Tools registered in `mcp_server.py`:
- `{'name': 'compute_minhash', 'description': 'Generate MinHash signature vector for fast near-duplicate identification.'}`
- `{'name': 'estimate_similarity', 'description': 'Estimate Jaccard similarity between two MinHash signature vectors.'}`
- `{'name': 'evaluate_quality', 'description': 'Score text document quality based on lexical diversity and structural metrics.'}`

## Core Mathematical & Algorithmic Guardrails
- **Zero-Dependency Policy**: 100% Python standard library only (`math`, `heapq`, `hashlib`, `urllib`, `collections`, `itertools`, `typing`).
- **Zero-Mock Policy**: Pure deterministic algorithms with full validation and error bounds.
