# Cómo ejecutar

1. Activar entorno:
   .venv\Scripts\Activate.ps1

2. Instalar dependencias:
   pip install -r requirements.txt

3. Coloca el archivo CSV en `data/users_behavior.csv`.

4. Ejecutar script:
   python src\train.py --data_path data\users_behavior.csv --save_model models\best_model.joblib

5. O abrir el notebook:
   jupyter notebook notebooks\mi_proyecto.ipynb
