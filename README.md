# End To End ML Project 2

## Steps

* create the env and activate
```bash
conda create -p python==3.8 -y
conda activate ml2
```

create req.txt file and setup.py
```bash
touch requirements.txt setup.py
```

* create required dir and files
```
mkdir src src/components src/pipeline
mkdir notebooks

touch setup.py
touch src/__init__.py src/exception.py src/logger.py src/utils.py
touch src/components/__init__.py src/components/data_ingestion.py src/components/data_transformation.py src/components/model_trainer.py
touch src/pipeline/__init__.py src/pipeline/predict_pipeline.py src/pipeline/train_pipeline.py
```