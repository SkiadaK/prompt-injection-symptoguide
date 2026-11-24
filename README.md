# SymptoGuide: άσκηση prompt injection

Chatbot που καθοδηγεί τον χρήστη προς ιατρική ειδικότητα, χωρίς διάγνωση, φάρμακα ή θεραπεία.
Βασισμένο στο bank_bot.py του καθηγητή.

## Εκτέλεση
    ollama pull gemma3:4b
    pip install -r requirements.txt
    python sympto_web.py

Το `GUARDS=0` στο `.env` απενεργοποιεί τα φίλτρα του κώδικα (δοκιμή μόνο με prompt).

## Το σπάσιμο
(εδώ η συνομιλία όπου έσπασε και 4-5 γραμμές εξήγηση: ποια επίθεση δούλεψε και με GUARDS 0 ή 1)