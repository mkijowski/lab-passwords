# CEG 3400 - Lab 2 - Password cracking

Name: 

---

## Task 1 - `hashcat`

* Describe what the `-a 0` flag does when used with `hashcat`.  Be verbose and explain its greatest strength and weakness.

* How many passwords were you able to crack using `hashcat` with the `500_passwords.txt`?

* Describe what would be needed to crack all hashes in the `/data/sha512.hashes` file.

* What is the difference between our two hash files in `/data`?

* What benefit would `john` bring us when trying to crack *all* of the hashes provided (both the yescrypt and sha512 hashes)?

---

## Task 2 - `john`

* How many passwords were you able to crack using `john` with the `500_passwords.txt`?

* What would be the maximum number of hashes `john` would compute assuming a 
  stragiht dictionary attack, `500_passwords.txt`, and the list of yescrypt hashes?

---

## Task 3 - Choose your own task:

Choose ***one*** of the following tasks and document your progress ***well***.

1. Crack one `sha512.hashes` hash or `yescrypt.hashes` with `500_passwords.txt` using a rule based attack.
2. Crack one `sha512.hases` hash or `yescrypt.hashes` with `rockyou.txt` that was not found using `500_passwords.txt` (this one is possilbe within the time limit)
   * `rockyou.txt` can be downloaded with: `wget https://github.com/mkijowski/passwords/raw/master/dictionaries/rockyou.txt.gz`
   * Do ***NOT*** include `rockyou.txt` or `rockyou.txt.gz` anywhere in this repository.  I will deduct many points for doing so...

For whichever you chose write a report below documenting the following:

* Which task you chose.
* Your research (relevant links) and an overview of your testing.
* Your final successful attempt (or why you think your attempt failed).
* An estimate of the total number of hashes computed to complete this task.
* Each of the tasks above crack a hash that was not previously found.  Give a detailed description of how and why it was not found 
  previously and what your attack did differently. 

---

## Task 3 report

---

## Bonus points (20 lab points)

My testing shows using `hashcat` with `rockyou.txt` takes between 10 and 20 days to run on an Intel core i7 
processor (17 days 10 hours by my last attempt).  Finish a run before this lab is due. 

Submit a `BONUS.md` file with a count of how many passwords and a brief writeup of how you accomplished this task.
You may work in a team of 3 students on the bonus (and only the bonus).  Each student needs to submit their own 
writeup and potfile with all found passwords. 

