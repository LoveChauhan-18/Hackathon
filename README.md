# Hackathon

# AI Interview Coach Agent

Built with TrueForge (open-source agent harness).

## What it does
- Takes the candidate's target role and seniority level
- Generates role-specific conceptual, technical, and coding interview questions
- Conducts a complete mock interview
- Runs coding answers in a sandbox against test cases
- Analyzes technical answers and coding performance
- Scores the candidate's overall performance
- Identifies strengths and areas for improvement
- Provides personalized interview feedback
- **Pauses for human approval** before finalizing the evaluation

## AI tools used
- Claude (Anthropic) — used for planning, debugging WSL/sandbox setup, and designing agent instructions
- Gemini 3.6 Flash — used as the connected model for running the interview agent

## Setup
1. Install TrueForge using `npx @truefoundry/trueforge`
2. Set up Linux/WSL2 for the native sandbox
3. Connect the Gemini 3.6 Flash model
4. Configure the agent instructions
5. Run the interview flow: questions → candidate answers → sandbox evaluation → scoring → human approval → feedback

## Notes
- The coding sandbox requires Linux, so WSL2 was configured on Windows.
- Human approval is included before the final evaluation to keep the feedback controlled and reviewable.

## Demo Video Link 
https://drive.google.com/file/d/1LF_7om0L43EYwc99SjcKzVRCIRmik21I/view?usp=sharing
