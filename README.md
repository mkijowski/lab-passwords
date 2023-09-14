# CEG 3400 - Lab 2 - Password cracking

Name: 

---

## Task 1 - `hashcat`

* Describe what the `-a 0` flag does when used with `hashcat`.  Be verbose and explain its greatest strength and weakness.

* How many passwords were you able to crack using `hashcat` with the `500_passwords.txt`?

* Describe what would be needed to crack all hashes in the `/data/sha512.hashes` file.

* What is the difference between our two hash files in `/data`?

* What benefit would `john` bring us when trying to crack *all* of the hashes provided?

---

## Task 2 - Choose your own task 2???

Choose one of the following tasks and document it ***well***.

1. Use `john` to crack at least one of the `yescrypt.hashes` (I do not know that this is possible).
2. Crack one `sha512.hases` hash with `rockyou.txt` that was not found using `500_passwords.txt` (this one is possilbe within the time limit)
3. Crack one `sha512.hashes` hash with `500_passwords.txt` using a rule based attack (this one *might* not be possible, but should be likely)

For whichever you chose write a report below documenting the following:

* Your research (relevant links) and an overview of your testing.
* Your final successful attempt (or why you think your attempt failed).
* An estimate of the total number of hashes computed to complete this task.
* Each of the tasks above crack a hash that was not previously found.  Give a detailed description of how and why it was not found 
  previously and what your attack did differently. 

---

## Feedback

This is the first time I am trying password cracking as a lab (instead of an in class exercise).  What did you think?

### Task 1 thoughts

### Task 2 thoughts

---

## Bonus points (20!)

My testing shows using `hashcat` with `rockyou.txt` takes between 10 and 20 days to run on an Intel core i7 
processor (17 days 10 hours by my last attempt).  Finish a run before this lab is due. 

This bonus can be tackled in teams of up to 6 people.

Submit a `BONUS.md` file with a list of who was in your group and a writeup of what you found.  Each student needs to writeup their own `BONUS.md`

