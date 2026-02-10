python3 -m venv build_env  
source build_env/bin/activate  
pip install pyinstaller ttkbootstrap cryptography  
pip install --upgrade pip  
pyinstaller --noconsole --onefile --windowed --name "PyDuty Pro V2" main.py
