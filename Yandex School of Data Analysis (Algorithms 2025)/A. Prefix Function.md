# A. Prefix Function

| Time Limit | 0.5 seconds |
|------------|------------|
| Memory Limit | 64 MB |
| Input | Standard input or input.txt |
| Output | Standard output or output.txt |

---

## **Description**

You are given a string **s**. You need to compute the **prefix function** of **s** — for each **i** from **1** to **|s|**:

\[
p[i] = \max \{ j : 0 \leq j < i, s[1..j] = s[i - j + 1..i] \}
\]

---

## **Input Format**

The input consists of a single non-empty string **s** of length at most **1,000,000**, consisting of lowercase Latin letters.  

---

## **Output Format**

Print **p[i]** for each **i** from **1** to **|s|**. Separate the numbers with spaces.  

---

## **Example**  

### **Input**  

    abracadabra  

### **Output**  

    0 0 0 1 0 1 0 2 3 4  
