Run :
Bash script
1)bash readfiles.sh diseasesFile.txt countriesL.txt 1000 1(no duplicate)
2)bash readfiles.sh diseasesFile.txt countriesL.txt 1000 0( duplicate)
# σε καθε run σβήνω το touch
Περιέχει μια βασική while που εκτελείται τόσο όσο τις γραμμες που θέλουμε να εχει το .txt
για diseases και countries πέρνω τυχαία από τα αρχεία, οτι έχει σχεση με νούμερα τα δημιουργω με
καταλληλη χρήση της RANDOM , για συμβολοβοσειρές πέρνω τυχαία σύμβολα εντος ζητούμενου
εύρους , και no duplicate το εξασφαλιζω μεσω μια while που ελένχει αν βρίσκεται το εισαγόμενο
στοιχείο στον πίνακα που διατηρώ τα citizenId , to duplicated εξεσφαλιζεται μεσω του της
τυχαιότητας, κάθως είναι μεγάλο το εύρος για να μην υπάρχει διπλότηπα.