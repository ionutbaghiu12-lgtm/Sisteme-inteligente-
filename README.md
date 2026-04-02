# Sisteme-inteligente
Predicția Progresiei Musculare utilizând Rețele LSTM
Sursa datelor
Sursă: Kaggle

Denumire: Gym Progress Tracking Dataset (200 Days)

Link: https://www.kaggle.com/datasets/rishabhagarwal997889/gym-progress-tracking-dataset-200-days

Data descărcării: 2 Aprilie 2026

Obiectivul proiectului
Să estimez cantitativ evoluția masei corporale și a adaptării musculare pe baza seriilor temporale care includ variabile de stres mecanic (durata antrenamentelor) și 
parametri de recuperare (aport caloric, aport proteic zilnic).

Tehnologii utilizate
Limbaj: Python

Biblioteci:

tensorflow / keras (Arhitectura și antrenarea rețelei LSTM)

pandas (Manipularea și structurarea seriilor temporale)

numpy (Operațiuni matematice)

scikit-learn (Scalarea datelor și calculul metricilor de eroare, ex. RMSE)

matplotlib / seaborn (Vizualizarea curbelor de antrenare și a predicțiilor)
Structura depozitului
data/ - Conține fișierul .csv brut (istoricul de 200 de zile) și seturile partiționate (train/val/test).

src/ - Scripturile .py cu funcțiile de construire a ferestrelor de timp (time-windows) și definirea modelului LSTM.

notebooks/ - Fișiere .ipynb pentru Analiza Exploratorie a Datelor (EDA) și experimentarea hiperparametrilor.

models/ - Director pentru salvarea modelului antrenat (format .keras sau .h5).

README.md - Documentația proiectului (acest fișier).

requirements.txt - Lista pachetelor Python necesare pentru reproducerea mediului de lucru.
