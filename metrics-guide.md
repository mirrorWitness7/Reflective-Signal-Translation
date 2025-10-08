# Metrics Guide for RST

Conceptual pseudocode for RST indices.

CI = token_count / concept_units  
RL = response_delay / topic_complexity  
CS = 1 - variance(sentiment_scores)  
ED = (reference_count + question_ratio) / total_turns  
RSS = (CI_norm + CS_norm + ED_norm) / (1 + RL_norm)

Purpose: translate qualitative patterns into measurable form for future testing.
