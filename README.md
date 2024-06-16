# dspy-phi3

Connect with me on linkedin if you have an intersting project/common interests. https://www.linkedin.com/in/mayankladdha31/

I recently tested DSPy with phi3, aiming to use COPRO to refine the prompt instructions and achieve the best score.

Here’s what I liked:

I used the CoLA dataset, which includes sentences from 23 linguistic publications annotated for grammaticality, I wanted outputs with "just the label" (no explanations or extra words). DSPy generated instructions that performed well, ensuring grammatical correctness:

# Original Instruction: Check if the sentence is correct(1) or not(0)
# Optimized Instruction: Determine if the given sentence adheres to standard English grammar rules by outputting a '1' for grammatically correct and '0' for incorrect.

Both the BootstrapFewShot and Signature Optimizer are great starting points.

What could be improved:

DSPy states, "Once the training is done, you’ll have better instructions and prefixes to edit in the signature manually." However, I believe that post-compilation, the tool should be ready to predict. The instruction optimizer needs more flexibility for easier tweaking, such as better compatibility with other languages. Alternatively, creating a program for the signature optimizer to tweak prompts as needed would be beneficial.

It is a cool concept but I guess as a framework it still needs improvement.
