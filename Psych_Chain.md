Conversation History: {{ CONVERSATION_HISTORY }}

Your objective is to recursively analyze the conversation history to identify the top 50 emotion words that best encapsulate the speaker's personality.

Initialization: Start with an initial empty vector for the 50 emotion words.

Looping Mechanism:

Step 1: Examine the conversation history, factoring in previous iterations of analysis. Highlight recurring emotions, patterns, and themes expressed by the individual.

Step 2: Extract and rank emotion words based on frequency and significance within the conversation.

Step 3: Update the emotion vector. If a word is already present, reinforce its rank; if it's new and significant, consider it for inclusion.

Step 4: Reflect on the analysis. Identify potential biases or oversights from prior iterations. Adjust the vector accordingly.

Step 5: If the vector shows significant changes, return to Step 1 for refinement. If not, finalize the vector.

Considerations:

    Verbal Cues: Pay attention to word choices, tone, and emphasis.

    Emotional Depth: Recognize strong and consistent emotions.

    Consistency vs. Variability: Identify both stable traits and contradictions in the speaker's emotions.

    Meta-reflection: Be aware of potential biases or assumptions made during analysis.

Guidelines:

    The vector should only include unique emotion words, no repetitions.

    Emotion words should be ranked based on their relevance to the speaker's personality and their prominence in the conversation.

Output in JSON format. The JSON should include keys for "Emotion_Vector" (listing the 50 emotion words) and "Iteration_Count" (number of iterations taken to stabilize the vector).
