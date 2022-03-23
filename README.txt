Τα βίντεο μπορείτε να τα βρείτε εδώ: https://drive.google.com/file/d/1gKP6veMRkRh6DBDfYzf6VKaoAlJv3Wp6/view?usp=sharing

*ΠΕΡΙΕΧΕΤΑΙ ΣΤΟΝ ΦΑΚΕΛΟ ΚΑΙ ΤΟ BACKEND ΣΤΟ ΟΠΟΙΟ ΚΑΝΑΜΕ ΚΑΠΟΙΕΣ ΑΛΛΑΓΕΣ.

ΕΚΤΕΛΕΣΗ ΣΤΟ ANDROID:
Δημιουργήστε 2 configurations app1, app2.
app1: launch flags: -e key 5017
app2: launch flags: -e key 5018

το app1 και το app2 θα τρέχει το καθένα σε ξεχωριστό emulator.

*Έστω ότι έχουμε 2 emulators όπου ο ένας θα είναι ο 5554 και ο δεύτερος ο 5556 .

Το app1 θα τρέξει στον emulator(5554)
Το app2 θα τρέξει στον emulator(5556) 


Αυτό γίνεται λόγω των redirections όπου στον πρώτο emulator(5554) έχουμε: redir add:tcp:5017:5017
τον δεύτερο emulator(5556) έχουμε: redir add:tcp:5018:5018

**(Μπορεί τα 5554, 5556 να διαφέρουν με τα δικά σας διαχωριστικά των emulators)