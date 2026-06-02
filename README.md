# langgraph-ctr
Langgraph-base Click Through Rate predictor
From: https://cognitiveclass.ai/courses/build-a-multi-agent-ctr-prediction-system-with-langgraph

### Initialise
```
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### Run it
```
python main.py
```

### Additional exercises

Try these enhancements:
- Add More Features: Include additional columns from the dataset as model inputs
- Compare Models: Add a second training tool that uses a different algorithm and compare MSE values side by side
- Add Conditional Routing: Use LangGraph's conditional edges to skip the visualization step if MSE is above a threshold
- Explore the ReAct Pattern: Let the LLM itself decide which tool to call, rather than hard-coding the sequence
- Deploy as a Web App: Wrap the pipeline in a Gradio interface so users can upload their own CSV and see predictions in a browser
