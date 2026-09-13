
## Uruchomienie lokalne

### Wymagania

- Python 3.10 lub nowszy
- Klucz Anthropic API ([console.anthropic.com](https://console.anthropic.com))

### Krok po kroku


1. Sklonuj repozytorium i wejdź do katalogu
git clone https://github.com/twoj-user/gdzie-na-wakacje.git
cd gdzie-na-wakacje

# 2. Utwórz środowisko wirtualne
python -m venv .venv

3. Aktywuj je
 .venv\Scripts\activate           # Windows

 4. Zainstaluj biblioteki
pip install -r requirements.txt

 5. Skopiuj .env.example do .env
cp .env.example .env
 Windows: copy .env.example .env

6. Otwórz .env i wpisz swój prawdziwy klucz API
    ANTHROPIC_API_KEY=sk-ant-...

 7. Uruchom aplikację
python app.py

8. Otwórz w przeglądarce
   http://127.0.0.1:5000