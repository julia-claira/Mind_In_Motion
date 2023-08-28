```bash 
pip install --upgrade pipsource venv/bin/activate

python3 -m venv venv

pip install ipykernel pandas numpy matplotlib Image seaborn scikit-learn xgboost tensorflow scipy openai mlxtend graphviz

python -m ipykernel install --user --name=myenv
pip freeze > requirements.txt
```
