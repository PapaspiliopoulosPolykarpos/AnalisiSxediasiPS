# Στήσιμο του περιβάλλοντος λειτουργίας.

Αφού έχουμε εγκαταστήσει στο σύστημά μας τα npm και node, κάνουμε git pull ώστε να έχουμε την πιο πρόσφατη έκδοση του κώδικα.
Έπειτα κάνουμε npm install ώστε να εγκατασταθούν όλα τα Dependencies και αφότου ολοκληρωθεί αυτό, "σηκώνουμε" τον server με την εντολή npm start.
Η εντολή npm start τρέχει το nodemon, άρα μετά από κάθε αλλαγή στον κώδικα (μετά από το save) ο server επανεκκινεί αυτόματα.

## Error στο console
Το error "(node:7612) Warning: Accessing non-existent property 'MongoError' of module exports inside circular dependency (Use `node --trace-warnings ...` to show where the warning was created)" το αμελούμε καθώς θα διoρθωθεί σε επόμενη έκδοση του mongoose.

#html arxeia
kanoume: npm install ejs --save (ola ta .html arxeia metafrazontai se .ejs san template)
documentation: https://expressjs.com/en/guide/using-template-engines.html
