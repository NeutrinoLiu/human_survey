### A frontend of human survey for image generative model post training

update the `config.json` to specify a list of subdirectories, images in which will be compared with each other. Dont forget to check the postfix in the config.

install dependencies:
```
pip install streamlit pandas
```

run the front end:
```
streamlit run app.py
```

view in  http://localhost:8501

result will be saved as `result_timestamp.json`
