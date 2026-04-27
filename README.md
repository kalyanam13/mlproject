# ==============================
# 📌 STEP 1: Activate Conda
# ==============================
conda activate

# ==============================
# 📌 STEP 2: Create Virtual Environment
# ==============================
conda create -p venv python==3.12.7 -y

# ==============================
# 📌 STEP 3: Activate Environment
# ==============================
conda activate venv/

# ==============================
# 📌 STEP 4: Pull .gitignore from Repo
# ==============================
git pull

# ==============================
# 📌 STEP 5: Create Project Structure
# ==============================
mkdir src
mkdir src/components
mkdir src/pipeline
mkdir notebook
mkdir logs

# Create files
touch setup.py
touch requirements.txt
touch src/__init__.py
touch src/exception.py
touch src/logger.py

# Optional pipeline files
touch src/pipeline/__init__.py
touch src/pipeline/training_pipeline.py
touch src/pipeline/prediction_pipeline.py

# Optional component files
touch src/components/__init__.py
touch src/components/data_ingestion.py
touch src/components/data_transformation.py
touch src/components/model_trainer.py

