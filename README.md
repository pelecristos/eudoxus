# Επικοινωνία Ανθρώπου Μηχανής, Εργασία 3
##### Πελεκούδας Ιωάννης : 1115201500128
##### Παπαχρήστου Δημήτρης : 1115201500124
##### Σκούρας Γεώργιος : 1115201400309

###  Στην Αρχική Σελίδα έχουν υλοποιηθεί
* Δύο βασικά μενού: ένα με τις βασικές ομάδες χρηστών
  και ένα με τις λοιπές λειτουργίες που μπορεί να κάνει κάποιος χρήστης του ιστοχώρου.
* Η λειτουργία εγγραφής χρήστη 
* Λειτουργίες που δέν ζητήθηκε να υλοποιηθούν όπως "Βοήθεια" και Ανακοινώσεις" συνοδεύονται
  από την εικόνα "Under Construction".
* Μπάρα αναζήτησης που κάποιος χρήστης θα μπορεί να βρεί συγγράματα πληκτρολογώντας είτε το 
  ISBN, το τίτλο κάποιου συγγράμματος, τον συγγραφέα και τον εκδότη.

#### Ομάδες Χρηστών
 * Οι δύο βασικές ομάδες χρηστών που επιλέχθηκαν είναι οι "Φοιτητές" και οι "Διανομείς".

#### Φοιτητές
 Η ομάδα χρηστών "Φοιτητές" μπορούν να :
  * Αντλήσουν πληροφορίες σχετικά με τις λειτουργίες που μπορούν να πραγματοποιήσουν.
  * Έχουν πρόσβαση σε όλα τα συγγράματα που διατίθενται στον Εύδοξο.
  * Να πραγματοποιήσουν δήλωση συγγραμμάτων.
  
 * Σημείωση 1: Tα στοιχεία που έχουν οριστεί για να συνδεθεί κάποιος ως φοιτητής είναι:
  * -> username: hacker
  * -> password: okokokok

 * Σημείωση 2: Κατά την δήλωση συγγραμάτων η πορεία βημάτων που πρέπει να ακολουθηθεί είναι η εξής:
     * Επιλογή των στοιχείων του τμήματος μας και επιλογή του πρώτου εξαμήνου.
      * Στη βάση που υλοποιήσαμε έχουν καταχωρηθεί βιβλία για τα εξής μαθήματα: 
      * Εισαγωγή στον Προραμματισμό
      * Εισαγωγή στη Πληροφορική και τις Τηλεπικοινωνίες
      * Λογική Σχεδίαση(και το Εργαστήριο).
     * Επιλογή παραλαβής απο σημείο διανομής.

### Διανομείς 
 Η ομάδα χρηστών "Διανομείς" μπορούν να :
 * Αντλήσουν πληροφορίες σχετικά με τις λειτουργίες που μπορούν να πραγματοποιήσουν.
 * Παραδώσουν κάποιο σύγγραμμα, ενημερώνοντας τη βάση του συστήματος.
 Σημείωση : Tα στοιχεία που έχουν οριστεί για να συνδεθεί κάποιος ως διανομέας είναι:
  * -> username: vivliopoleio
  * -> password: okokokok

### Προφίλ Χρηστών
   Αφού συνδεθεί κάποιος ως χρήστης στον Εύδοξο μπορεί να πραγματοποιήσει επεξεργασία των στοιχείων του
   πατώντας στην επιλογή "Προφίλ" επιλέγοντας το μπλε εικονίδιο δίπλα στην ενότητα προσωπικά στοιχεία.
 
### Εγγραφή νέων Χρηστών
   * Κατά την εγγραφή τους οι νέοι χρήστες συμπληρώνουν μια φόρμα εγγραφής, που πέρα απο τα στοιχεία τους, τους
     ζητείτε και το πώς σκοπεύουν να χρησιμποποιήσουν τον Εύδοξο(ως Φοιτητές, Διανομέας κλπ). 
   * Αφού πατήσουν "Εγγραφή" ανακατευθύνονται σε μία σελίδα που τους ζητείται είτε να επιλέξουν το Ίδρυμα τους
     και τη σχολή τους (αν πρόκειται για φοιτητή/τρια ή γραμματεία) είτε την επωνυμία τους (αν πρόκεται για εκδότες ή διανομείς).

     
System requirements
-------------------

* Python version 3.6 or later
* Django version 2.1 or later

Additional Packages Required
----------------------------

```bash
pip install django-crispy-forms
pip install django-formtools
```

Installation & Testing
----------------------

```bash
git clone git://github.com/pelekoudasq/eudoxus.git
cd eudoxus
python manage.py runserver
```

Then connect to localhost:8000
