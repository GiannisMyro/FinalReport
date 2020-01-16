# Τίτλος: User land
## Ονοματεπώνυμο: Χρήστος Μήλιος
## Αριθμός Μητρώου: Π2018219
### [Link αποθετηρίου hci](https://github.com/p18mili1/hci/tree/2018219/projects/2018219)
### [Link αποθετηρίου gr](https://github.com/p18mili1/gr)
### [Link εκτελέσιμου](https://p18mili1.github.io/gr)

# Εισαγωγή
Η εργασία αυτή εκπονήθηκε στα πλαίσια του μαθήματος Επικοινωνία Ανθρώπου-Υπολογιστή του Γ' εξαμήνου σύμφωνα με το δείγμα τελικής αναφοράς που αναφέρεται στο [παράδειγμα καλής δομής των παραδοτέων](https://github.com/courses-ionio/hci/blob/master/projects/201XXXX/README.md) που έχει παρασχεθεί από τους διδάσκοντες.

# Σύνοψη
Η εργασία χωρίζεται σε δύο μέρη (παραδοτέα) που το καθένα αποτελείται από δύο εργασίες σε Linux και μία εργασία συμμετοχικού περιεχομένου. Υλοποίησα και τα δύο παραδοτέα σύμφωνα με τις απαιτήσεις της εκφώνησης έχοντας την ευκαιρία στο 2ο παραδοτέο να επιλύσω κάποια προβλήματα που υπήρχαν κατά την εκπόνηση του 1ου παραδοτέου. Το πρώτο μέρος προσπαθεί να εξοικειώσει το χρήστη με τις πλέον βασικές εντολές και λειτουργίες της γραμμής εντολών του linux καθώς επίσης και να του μάθει να προσθέτει υλικό σε συμμετοχικά έργα ενώ το δεύτερο μέρος προωθεί το χρήστη σε ένα ψηλότερο επίπεδο πάντα από τη γραμμή εντολών του linux και επίσης να προσθέτει δικό του έργο σε συμμετοχικά έργα.

# Σύντομη ανάλυση σχετικών έργων και εργαλείων
Το λειτουργικό σύστημα που χρησιμοποήθηκε είναι το Ubuntu 1804, το οποίο ήταν εγκατεστημένο σε VirtualBox Manager 6.0 πάνω σε Windows 10. Για να είναι εφικτή η πραγματοποίηση των εργασιών, έκανα εγκατάσταση των πακέτων homebrew, python και asciinema ενώ για την υλοποίηση των εργασιών εγκατέστησα τις εφαρμογές mc (midnight commander), neofetch, vim, ranger, thefuck, todo.txt-cli και calcurse. Μέχρι και την επίδοση του πρώτου παραδοτέου, είχα ένα πρόβλημα σχετικά με τη δημιουργία μέσω του github pages του εκτελέσιμου του συμμετοχικού έργου για το οποίο δεν μπορούσα να βρω βοήθεια από πουθενά. Τελικά, ανατρέχοντας στα σχόλια ενός issue του github, στο repository του mibook/gr μπόρεσα να βρω τη λύση σε ένα συγκεκριμένο σχόλιο συναδέλφου. Τα υπόλοιπα προβλήματα που αντιμετώπισα ήταν κυρίως σωστής χρήσης εντολών και συντακτικής φύσεως και τα επέλυσα με τη βοήθεια των man-pages και τη συνδρομή άλλων προγραμματιστών μέσω ιστοσελίδων όπως,

  * [https://www.geeksforgeeks.org](https://www.geeksforgeeks.org)
  * [https://stackoverflow.com](https://stackoverflow.com)
  * [https://github.com](https://github.com)
  * [https://askubuntu.com](https://askubuntu.com)

Για την συγγραφή και την εκτέλεση του κώδικα χρησιμοποίησα αποκλειστικά τη διαδικτυακή πλατφόρμα του github. Στην συνέχεια, για κάθε παραδοτέο ανέφερα τα προγράμματα που χρησιμοποίησα, τα link των απαιτούμενων video και τις τσεκαρισμένες λίστες των ζητουμένων των ασκήσεων ενώ για το συμμετοχικό περιεχόμενο παρέθεσα απλά τα link με τα εκτελέσιμα αρχεία. Επίσης, σε κάθε παραδοτέο αναφέρεται το link του αποθετηρίου του κώδικα και το αντίστοιχο εκτελέσιμο, όταν υπάρχει.

# Μέθοδος και τεχνικές ανάπτυξης
Στην **1η** εργασία, στο _Παραδοτέο 1_, άλλαξα το command prompt του συστήματος με τον αριθμό μητρώου μου τροποποιώντας κατάλληλα το αρχείο διαμόρφωσης .bashrc και εμφάνισα στην οθόνη τα κρυφά αρχεία του καταλόγου μου και το αρχείο διαμόρφωσης παραμέτρων .bashrc. Επίσης, με το πρόγραμμα neofetch εμφάνισα τις πληροφορίες του συστήματος. Στην **2η** εργασία, επίσης στο _Παραδοτέο 1_, έκανα χρήση των man-pages, μία επίδειξη χρήσης εντολών του bash και βασικές λειτουργίες επξεργασίας αρχείων με τον editor vim, καθώς επίσης και επίδειξη λειτουργίας του file manager Ranger και του προγράμματος the Fuck, το οποίο προτείνει πιθανές διορθώσεις σε λάθη που ανιχνεύει κατά την πληκτρολόγηση των εντολών. Στην **3η** εργασία, στο _Παραδοτέο 2_, δημιούργησα με την εφαρμογή todo.sh μία λίστα εργασιών σε μη γραφικό περιβάλλον και στη συνέχεια έκανα μια επίδειξη μετατροπών, διαγραφών, προσαρτήσεων και αφαιρέσεων εγγραφών ή στοιχείων για τη λίστα αυτή ενώ στην **4η** εργασία, επίσης στο _Παραδοτέο 2_, με την εφαρμογή calcurse δημιούργησα και επεξεργάστηκα μία λίστα συναντήσεων και εργασιών σε γραφικό περιβάλλον αυτή τη φορά.

Για το **Παραδοτέο Α** της εργασίας συμμετοχικού περιεχομένου, η προσθήκη των πέντε νέων εικόνων στο δικό μου αντίγραφο του βιβλίου έγινε ως εξής: Αρχικά τροποποίησα το αρχείο *\_congfig.yml* και αντικατέστησα τα link του βιβλίου με τα αντίστοιχα link του δικού μου αντίγραφου. Στη συνεχεια, πρόσθεσα τo αρχείo κώδικα (.md) για την κάθε εικόνα στον κατάλογο **/\_gallery** και στη συνέχεια πρόσθεσα τις εικόνες και τα αντίστοιχα εικονίδια (thumbs) στον κατάλογο **/images**.
#### Το link τoυ αρχείου που έχει τροποποιηθεί:
[\_congif.yml](https://github.com/p18mili1/gr/blob/gh-pages/_config.yml)
#### Τα link αρχείων κώδικα που έχουν προστεθεί:
[Atmel_Atmega8.md](https://github.com/p18mili1/gr/blob/gh-pages/_gallery/Atmel_Atmega8.md), 
[Intel_P8051.md](https://github.com/p18mili1/gr/blob/gh-pages/_gallery/Intel_P8051.md), 
[MOS_6502.md](https://github.com/p18mili1/gr/blob/gh-pages/_gallery/MOS_6502.md), 
[Motorola_MC6800.md](https://github.com/p18mili1/gr/blob/gh-pages/_gallery/Motorola_MC6800.md), 
[Zilog_Z80.md](https://github.com/p18mili1/gr/blob/gh-pages/_gallery/Zilog_Z80.md)
#### Τα link των εικόνων και εικονιδίων που έχουν προστεθεί:
[Atmel_Atmega8.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/Atmel_Atmega8.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/Atmel_Atmega8-thumb.jpg), 
[Intel_P8051.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/Intel_P8051.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/Intel_P8051-thumb.jpg), 
[MOS_6502.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/MOS_6502.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/MOS_6502-thumb.jpg), 
[Motorola_MC6800.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/Motorola_MC6800.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/Motorola_MC6800-thumb.jpg), 
[Zilog_Z80.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/Zilog_Z80.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/Zilog_Z80-thumb.jpg)

Για το **Παραδοτέο Γ** της εργασίας συμμετοχικού περιεχομένου επέλεξα να προσθέσω μια νέα βιογραφία, του _Ivan Sutherland_. Αφού συνέθεσα το βιογραφικό έπειτα από σχετική έρευνα στο Internet, το αποθήκευσα σε μορφή markdown στο αρχείο *bio-sutherland.md* και μαζί με το αρχείο κώδικα *ivan-sutherland.md* τα έβαλα στον κατάλογο **/\_biography** του αποθετηρίου. Στη συνέχεια, έβαλα στον κατάλογο **/images** τρεις εικόνες και τα αντίστοιχα εικονίδιά τους (thumb).
#### Τα link αρχείων κώδικα που έχουν προστεθεί:
Αρχείο κώδικα: [ivan-sutherland.md](https://github.com/p18mili1/gr/blob/gh-pages/_biography/ivan-sutherland.md), 
Βιογραφία: [bio-sutherland.md](https://github.com/p18mili1/gr/blob/gh-pages/_biography/bio-sutherland.md) 
#### Τα link των εικόνων και εικονιδίων που έχουν προστεθεί:
[ivan-sutherland.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/ivan-sutherland.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/ivan-sutherland-thumb.jpg), 
[lightpen.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/lightpen.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/lightpen-thumb.jpg), 
[sketchpad1.jpg](https://github.com/p18mili1/gr/blob/gh-pages/images/sketchpad1.jpg) και 
[εικονίδιο](https://github.com/p18mili1/gr/blob/gh-pages/images/sketchpad1-thumb.jpg)

Το πρόβλημα με τα github pages που ανέφερα παραπάνω οφείλονταν στο γεγονός ότι υπήρχαν 20 αρχεία, τα οποία περιείχαν το tag "include_relative" για συνολικά 38 αρχεία χωρίς να υπάρχει ο κατάλογος αυτός. Το πρόβλημα λύθηκε αλλάζοντας το tag "include_relative" σε "include" και αντιγράφοντας τα 38 αυτά αρχεία στον κατάλογο **/\_includes** του αποθετηρίου.

#### Τα link αρχείων κώδικα που έχουν τροποποιηθεί
[alan-kay.md](https://github.com/p18mili1/gr/blob/gh-pages/_biography/alan-kay.md), 
[mark-weiser.md](https://github.com/p18mili1/gr/blob/gh-pages/_biography/mark-weiser.md), 
[reactable.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/reactable.md), 
[poet.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/poet.md), 
[mouse.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/mouse.md), 
[ipod.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/ipod.md), 
[windows.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/windows.md), 
[xerox-parc.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/xerox-parc.md), 
[affective.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/affective.md), 
[www.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/www.md), 
[google_search.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/google_search.md), 
[arduino.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/arduino.md), 
[minecraft.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/minecraft.md), 
[star.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/star.md), 
[facebook.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/facebook.md), 
[wikipedia.md](https://github.com/p18mili1/gr/blob/gh-pages/_case-study/wikipedia.md), 
[method.md](https://github.com/p18mili1/gr/blob/gh-pages/pages/method/method.md), 
[image-credits.md](https://github.com/p18mili1/gr/blob/gh-pages/pages/credits/image-credits.md), 
[make.md](https://github.com/p18mili1/gr/blob/gh-pages/pages/chapters/make.md), 
[research.md](https://github.com/p18mili1/gr/blob/gh-pages/pages/chapters/research.md)
#### Τα link αρχείων κώδικα που έχουν αντιγραφεί από /\_biography σε /\_includes
[bio-kay.md](https://github.com/p18mili1/gr/blob/gh-pages/_biography/bio-kay.md), 
[bio-weiser.md](https://github.com/p18mili1/gr/blob/gh-pages/_biography/bio-weiser.md)
#### Τα link αρχείων κώδικα που έχουν αντιγραφεί από /\_case-study σε /\_includes
[cs-reactable.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-reactable.md), 
[cs-poet.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-poet.md), 
[cs-mouse.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-mouse.md), 
[cs-ipod.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-ipod.md), 
[cs-windows.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-windows.md), 
[cs-xerox-parc.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-xerox-parc.md), 
[cs-affective.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-affective.md), 
[cs-www.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-www.md), 
[cs-google_search.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-google_search.md), 
[cs-arduino.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-arduino.md), 
[cs-minecraft.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-minecraft.md), 
[cs-star.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-star.md), 
[cs-facebook.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-facebook.md), 
[cs-wikipedia.md](https://github.com/p18mili1/gr/tree/gh-pages/_case-study/cs-wikipedia.md)
#### Τα link αρχείων κώδικα που έχουν αντιγραφεί από /pages/method σε /\_includes
[audience.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/audience.md), 
[need.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/need.md), 
[benefit.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/benefit.md), 
[structure.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/structure.md), 
[required.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/required.md), 
[approach.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/approach.md), 
[pedagogy.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/pedagogy.md), 
[syllabus.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/syllabus.md), 
[projects.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/projects.md), 
[evaluation.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/method/evaluation.md)
#### Τα link αρχείων κώδικα που έχουν αντιγραφεί από /pages/credits σε /\_includes
[credits-pre.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-pre.md), 
[credits-intro.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-intro.md), 
[credits-ch01.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ch01.md), 
[credits-ch02.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ch02.md), 
[credits-ch03.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ch03.md), 
[credits-ch04.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ch04.md), 
[credits-ch05.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ch05.md), 
[credits-ch06.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ch06.md), 
[credits-ax01.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ax01.md), 
[credits-ax02.md](https://github.com/p18mili1/gr/tree/gh-pages/pages/credits/credits-ax02.md)
#### Τα link αρχείων κώδικα που έχουν αντιγραφεί από /pages/chapters σε /\_includes
[pi-make.md](https://github.com/p18mili1/gr/blob/gh-pages/pages/chapters/pi-make.md), 
[pi-research.md](https://github.com/p18mili1/gr/blob/gh-pages/pages/chapters/pi-research.md)

# Ενδεικτικές οθόνες

## Παραδοτέο 1
* Ενδεικτική εικόνα για την **Εργασία 1** στην οποία φαίνεται ότι έχει γίνει η αλλαγή του command prompt.

  ![Screenshot](ergasia_1.jpg)

* Ενδεικτική εικόνα για την **Εργασία 2** στην οποία φαίνεται μεταξύ άλλων και η προτροπή της εντολής fuck για διόρθωση της προηγούμενης εντολής.

  ![Screenshot](ergasia_2.jpg)
  
## Παραδοτέο 2
* Ενδεικτική εικόνα για την **Εργασία 3** στην οποία φαίνεται η επεξεργασία μίας λίστας todo.

  ![Screenshot](ergasia_3.jpg)

* Ενδεικτική εικόνα για την **Εργασία 4** στην οποία φαίνονται οι συναντήσεις και οι εργασίες μιας συγκεκριμένης ημέρας.

  ![Screenshot](ergasia_4.jpg)


# Συμπεράσματα
Ο σκοπός της εργασίας αυτής ήταν η ομαλή προσαρμογή του χρήστη στον κόσμο του Linux και της γραμμής εντολών μαθαίνοντάς του τα βασικά αλλά κυρίως δείχνοντάς του πως μπορεί να μάθει και να ανακαλύψει πράγματα μέσα από το ίδιο το λειτουργικό σύστημα ακόμα και χωρίς τη βοήθεια του Internet. Επίσης, μύησε το χρήστη στη λειτουργία της πλαρφόρμας Github, ενός πολύ ισχυρού και δημοφιλούς εργαλείου για τη δημιουργία μεγάλων project εξ΄αποστάσεως με συνεργάτες που δεν γνωρίζονται δια ζώσης αλλά λειτουργούν σαν ομάδα ακολουθώντας συγκεκριμένους κανόνες. Και τέλος, με τα συμμετοχικά περιεχόμενα ο χρήστης μπόρεσε να πάρει μία γεύση για τον τρόπο και τους κανόνες που διέπουν τις συμμετοχικές εργασίες και την ιδιαίτερη προσοχή που απαιτείται για να μπορέσει κάποιος να συνεισφέρει πραγματικά σε ένα τέτοιο project.

# Αναφορές
Περιλαμβάνονται όλοι οι σύνδεσμοι ιστοσελίδων που πάνω στις οποίες βασίστηκα για την ολοκλήρωση της εργασίας συνολικά.

* https://en.wikipedia.org/wiki/Ivan_Sutherland 
* https://www.computerhistory.org/fellowawards/hall/ivan-e-sutherland/
* https://www.computer.org/profiles/ivan-sutherland
* https://en.wikipedia.org/wiki/List_of_early_microcomputers
* https://github.com/ranger/ranger/wiki/Official-user-guide)
* https://guides.github.com/features/mastering-markdown/
* https://www.markdownguide.org/getting-started/
* https://guides.github.com/features/mastering-markdown/
