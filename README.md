Week 4 Challenge: Amharic E-commerce NER
This project extracts products, prices, and locations from Telegram-based e-commerce posts in Amharic using LLMs fine-tuned for Named Entity Recognition (NER).

🔧 Modules
telegram_scraper.py: Fetch messages and media from 5 vendor channels
convert_csv_to_conll.py and generate_token_csv.py: Create token-level label CSV and CoNLL format for model training "telegram_data.csv"-the scraped data "token_for_labeling.csv" - the filtered tockens "labeled_tokens.csv" the labeled form of the above "conll_dataset" converted the above csv file to conell format
📁 Data Example
Token	Label
NIKE	B-Product
Air	I-Product
Force	I-Product
