# Diet Plan Model — Streamlit

## Files
- `diet_plan_model_fixed.py`: trains the models and saves the Random Forest artifacts.
- `app.py`: Streamlit prediction interface.
- `requirements.txt`: Python dependencies.
- `best_random_forest_model.pkl`, `scaler.pkl`, `label_encoder.pkl`: generated after training.

## Run locally
1. Put your dataset CSV in this folder and update `file_path` inside `diet_plan_model_fixed.py`.
2. Install packages: `pip install -r requirements.txt`
3. Train: `python diet_plan_model_fixed.py`
4. Launch: `streamlit run app.py`

The original plotting code was removed, so matplotlib/seaborn are no longer required.
