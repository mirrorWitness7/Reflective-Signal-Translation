# RST Simulation Protocol

**Objective:**  
To test whether AI models can recognize and adapt to reflective communication patterns (high containment, low verbosity).

**Setup:**
- Two user profiles:
  - Reflective User (compressed, coherent)
  - Verbose User (expansive, redundant)
- Same base model (GPT / Gemini / Claude).
- 10-turn conversational sequence each.

**Data to log:**
- Token count per turn
- Concept diversity
- Sentiment variance
- Response delay

**Analysis Goals:**
1. Measure Compression Index and Containment Stability.
2. Track Adaptive Mode switching (concise vs verbose).
3. Detect when the model misreads silence as disengagement.

**Outcome Benchmark:**
AI should demonstrate improved balance between **brevity** and **coherence**, not verbosity or over-assurance.
