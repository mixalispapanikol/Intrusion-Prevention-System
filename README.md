# Intrusion Prevention System (IPS)

## Περιγραφή
Αυτό το έργο βασίζεται σε ένα Σύστημα Ανίχνευσης Εισβολών (IDS) που αναβαθμίστηκε σε Σύστημα Πρόληψης Εισβολών (IPS). Το σύστημα ανιχνεύει κακόβουλη δικτυακή δραστηριότητα χρησιμοποιώντας βαθιά μάθηση και εκτελεί προληπτικές ενέργειες για την αποτροπή απειλών.

## Τεχνολογίες
- Python
- TensorFlow/Keras
- scikit-learn
- matplotlib
- pandas

## Ενέργειες Πρόληψης
Το σύστημα μπορεί να εκτελέσει τις παρακάτω ενέργειες:
1. **Αποκλεισμός Κυκλοφορίας**: Αποκλείει ύποπτες IP διευθύνσεις.
2. **Απομόνωση Συσκευών**: Απομονώνει επηρεασμένες συσκευές με βάση τη MAC διεύθυνση.
3. **Ειδοποίηση Διαχειριστών**: Στέλνει ειδοποίηση μέσω email για μη αυτόματη παρέμβαση.

## Οδηγίες Χρήσης
1. Κατεβάστε το αρχείο `pcap_data.csv` από [εδώ](https://github.com/kdemertzis/EKPA/blob/main/Data/pcap_data.csv) και τοποθετήστε το στον ίδιο φάκελο με το script.
2. Εγκαταστήστε τις απαραίτητες βιβλιοθήκες:
   ```bash
   pip install tensorflow scikit-learn matplotlib pandas numpy
   
Εκτελέστε το αρχείο intrusion_prevention_system.ipynb για εκπαίδευση και αξιολόγηση.

Παρακολουθήστε τα αποτελέσματα του πίνακα σύγχυσης και τα γραφήματα.
