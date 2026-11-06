**Name:**
Amanda Silva & Ally Hussey

**Collaboration Statement:**

1. Question 1 Answer

```text
    0g 0:00:00:04 69% 2/3 0g/s 22472p/s 22472c/s 22472C/s Person6..Maiden6
    0g 0:00:00:06 92% 2/3 0g/s 21814p/s 21814c/s 21814C/s grandming..babygirling
    0g 0:00:00:08 3/3 0g/s 21009p/s 21009c/s 21009C/s 192013..shymur
    0g 0:00:00:09 3/3 0g/s 21121p/s 21121c/s 21121C/s biting..binnem
    0g 0:00:00:10 3/3 0g/s 20873p/s 20873c/s 20873C/s beles1..buro10
```
This output shows that John the Ripper is testing many potential passwords. In the output, at the end of each line there are words (Maiden6, grandming..babygirling, shymur, etc) these are examples of possible passwordsnthat John is trying. 

2. Question 2 Answer

(https://www.cyberhub.blog/topic-cards/understanding-md5-vulnerabilities)

https://www.rfc-editor.org/info/rfc6151/

We would not use the MD5 hashing algorithms as it is no longer considered secure. This algorithm is vulnerable to collision attakcs where different inputs could result in the same hash values. According to both the articles we found researching, this weakness makes MD5 a poor option for modern security applications such as password storage. As a system administrator, I would not use MD5 becaause attackers can quickly crack its hashes using newer hardware. 

3. Question 3 answer

```text
raspberry        (?)
1g 0:00:00:11 100% 0.08354g/s 21643p/s 21643c/s 21643C/s rampsman..rassled
```
4. Question 4 Answer

    0g 0:00:00:06 0% 0g/s 21364p/s 21364c/s 21364C/s idocrases..ihrams
    0g 0:00:00:07 0% 0g/s 21251p/s 21251c/s 21251C/s ladlewood..lammie
    0g 0:00:00:08 0% 0g/s 21304p/s 21304c/s 21304C/s miscegenation..misguggle
    0g 0:00:00:09 0% 0g/s 21324p/s 21324c/s 21324C/s occluded..odelet
    0g 0:00:00:10 1% 0g/s 21199p/s 21199c/s 21199C/s pericristate..peristrumitis

    1. Shortening Words 
    occluded -> odelet : these are different words but John appears to be moving through modified words that are shorter than the original. 

    2. Letter Subsitution
    miscegenation -> misguggle
    pericristate -> peristrumitis 
    are words being transformed rather than testing the original form. 

    3. Creating Derived Forms of Words
    The outputs are not always correct / real words. Johns rule generates different spellings and variety of differences from the original word. 
John is testing vaariations of dictionary words rather than exact words, he is not explicitly using numbers, capitalization, or special characters. 

5. Question 5 Answer

John the Ripper took approximately 1 minute and 1 second to crack the mangled password raspberry1. The start time was 05:52:25 UTC and the finish time was 05:53:26 UTC, which is 61 seconds. The password was quickly cracked because it is a dictionary word with one common modification (1) added at the end. 
 
    Fri Nov  6 05:52:25 UTC 2026
    Loaded 1 password hash (md5crypt [MD5 32/64 X2])
    Will run 2 OpenMP threads
    Press 'q' or Ctrl-C to abort, almost any other key for status
    raspberry1       (?)
    1g 0:00:01:01 100% 0.01639g/s 21810p/s 21810c/s 21810C/s ranunculaceous1..ratton1
    Use the "--show" option to display all of the cracked passwords reliably
    Session completed
    Fri Nov  6 05:53:26 UTC 2026





   