# Understanding BODMAS equations

Some simple maths problems to learn how to use BODMAS. Working with ChatGPT and Claude to understand the following concepts:

* Brackets ( )
* Orders — powers (e.g. 3²) and roots (e.g. √9)
* Division and Multiplication — working left to right
* Addition and Subtraction — working left to right

---

## Background

This entire exploration began after a 30-second TikTok video where someone in the street asked people passing by to answer basic maths questions. I remember seeing a simple one involving addition and multiplication, and people were getting it wrong. But another was harder, and I realised I had a flawed understanding. This began many hours of exploration.

---

## Some notes on the process below

These notes were added after the completion of the work below.

1. I struggled with maths at school. This was partially due to dyslexia and dyscalculia. These types of equations were very intimidating for me, but I wanted to break them down and learn the correct process. I noticed that by breaking each equation into tiny steps, the fear faded quickly.

   I'm also very aware that ChatGPT was only giving me "friendly" examples. This was actually vitally important, as early failures or complexity could have made me quit. A lot of this work was done late at night, as I have trouble sleeping. Any failure or frustration could therefore have led to me moving on to other distractions.

   The early successes had the opposite effect: I could feel myself learning and understanding.

2. I had a vague idea that Multiplication came first and Addition came last. This idea was only partially correct, at best. Even while going through this process, the idea that "additions always came last" was something I had to unlearn.

3. My dyslexia causes me to flick over concepts and misread them. Small maths symbols between numbers are easily missed or misread. One task was to slow down — to focus on breaking long chains down into single steps.

4. I was misunderstanding powers, so I tried to invent a way to slow myself down and look at them closely.

   ```
   3³ = 3 × 3 × 3 = 27 <<-- extra step just for my brain
   ```

5. I quickly understood the order for Brackets and Orders, but had a mental blocker with additions — always assuming they were last in order. I made several mistakes in the order of Addition and Subtraction.

   So I asked ChatGPT to set me specific tests, gradually increasing in difficulty and focusing on the problem areas: Division, Multiplication, Addition and Subtraction. To help, I numbered the order of each item inside the equation.

   ```
   18 +(3) 7 -(4) 32 ÷(1) 4 ×(2) 2 +(5) 5 = ?  <<-- extra step to show order
   ```

   This helped to lock the processes into my head as a scaffold. But it also took a lot of additional time, so after two of these I did them mentally rather than "on paper". They helped set up a "visual scan" of the equations.

6. Initially, I was using square brackets to note changes in equations, but after talking to ChatGPT, I learned that these symbols could have mathematical meaning, so we switched to **bold**. I retroactively changed some of the older examples to reflect this decision.

   There was another reason for the brackets/bold. I was often doing things in other browser windows, checking my phone, or getting up from the computer. If I left in the middle of solving an equation, I would return with no idea of the current step. Seeing the bold allowed me to quickly understand that I had just solved the concept above.

7. I experienced difficulties in the set from 41 onwards. While I understand negative numbers, I would often forget to include the negative symbol. This was important, as I knew it was a negative number but simply did not annotate it correctly. This could have led to major errors. I also had a simple counting error.

8. A common slip I noticed was mixing powers. In my mind, the power number meant:

   ```
   4² = 4 × 2
   4³ = 4 × 3
   ```

   At times, I added annotations to force myself to break this pattern. However, when not focusing fully, it reappears.

9. I noticed that sometimes I skipped over concepts. This is very clear in Test 49. I initially wrote "8", then realised I'd made a mistake. I added a line above to clearly resolve a square problem and then moved on, forgetting to fix the incorrect 8.

   This is not the first time this occurred here or elsewhere. I feel it is related to my dyslexia rather than just pure laziness or sloppiness, but I have no evidence. It feels like I knew what operation to perform → I successfully performed it → something went wrong when carrying the result into the next state.

   There seems to be a danger in doing a trivial step immediately following a demanding one.

10. Later, issues seem to come mainly from transcription errors.

11. Deep inside me somewhere, there is a non-logical fear of "taking too much time". I think this stems from early childhood classroom experiences where other children could solve maths problems quickly. I could not.

It comes out in lots of places, but especially during tests. These sessions forced me to sit with a problem, explore it, and take each step one at a time. A very useful experiment.

### Later notes

12. Expanding powers, e.g. `3³ = 3 × 3 × 3 = 27`. I called this an "extra step just for my brain", but it is a normal way to calculate exponents.

13. I assumed I was cheating by breaking decimal multiplication into easier chunks, e.g. `3.5 × 4 = 4 + 4 + 4 + 2 = 14` and `3.5 × 8 = 8 + 8 + 8 + 4 = 28`. But these are normal decomposition strategies.

14. There were some ways that I calculated problems manually that could have been done more effectively. However, I have tried to preserve all decisions made at the time. This should be treated as a historical document. It records my actions and decisions as they happened.

15. In the worked examples, the `**` markers are intentionally shown literally. They indicate the value I had just changed and are not mathematical notation. Although Markdown would normally use these markers to create **bold text**, I am happy for the raw markup to remain visible because it sits outside the maths notation and records how I marked up the work at the time.

---

## A single page app

After the first night, the first 20 tests, I got AI to build me a simple single page app to run test questions myself.

This was originally written for myself, just to quickly create tests. But I decided to release it for others. At that point, I wanted to help people who also may struggle, so the hint process was created - based on the idea I had used - numbering the symbols in order. Also, the explanation breakdown, always available.

<a href="https://russmaxdesign.github.io/maths-problems/" target="_blank">Maths problems</a>

The page has test exercise forms for:

* Addition
* Subtraction, including below zero
* Times tables
* Division, including halves and quarters
* Powers
* Roots
* Two operations
* BODMAS
* BODMAS with powers and roots
* BODMAS below zero
* BODMAS with halves and quarters

This work follows a common pattern in my learning. Become fixated, dive deeply, desire to share so others can learn. Use my struggles to map journeys so that others have a smoother path.

---

## BODMAS tests

### Test 1:
```
8 + 4 × 3 = ?
Multiplication first (4 × 3 = 12)
8 + **12** = ?
Addition second (8 + 12 = 20)
Answer: 20
```

### Test 2:
```
18 ÷ 3 + 5 × 2 = ?
Division first (18 ÷ 3 = 6)
**6** + 5 × 2 = ?
Multiplication second (5 × 2 = 10)
6 + **10** = ?
Addition third (6 + 10 = 16)
Answer: 16
```

### Test 3:
```
24 ÷ 4 × 3 - 2 = ?
Division first (24 ÷ 4 = 6)
**6** × 3 - 2 = ?
Multiplication second (6 × 3 = 18)
**18** - 2 = ?
Subtraction last (18 - 2 = 16)
Answer: 16
```

### Test 4:
```
30 - 12 ÷ 3 × 2 = ?
Division first (12 ÷ 3 = 4)
30 - **4** × 2 = ?
Multiplication second (4 × 2 = 8)
30 - **8** = ?
Subtraction last (30 - 8 = 22)
Answer: 22
```

### Test 5:
```
6 + 18 ÷ 3 × 2 - 4 = ?
Division first (18 ÷ 3 = 6)
6 + **6** × 2 - 4 = ?
Multiplication second (6 × 2 = 12)
6 + **12** - 4 = ?
Addition third (6 + 12 = 18)
**18** - 4 = ?
Subtraction last (18 - 4 = 14)
Answer: 14
```

### Test 6:
```
20 - 6 + 2 × 5 = ?
Multiplication first (2 × 5 = 10)
20 - 6 + **10** = ?
Subtraction second (20 - 6 = 14)
**14** + 10 = ?
Addition third (14 + 10 = 24)
Answer: 24
```

### Test 7:
```
36 ÷ (3 × 2) + 5 = ?
Brackets first (3 × 2 = 6)
36 ÷ **6** + 5 = ?
Division second (36 ÷ 6 = 6)
**6** + 5 = ?
Addition third (6 + 5 = 11)
Answer: 11
```

### Test 8:
```
5 + 2² × 3 = ?
Orders first (2² = 2 × 2 = 4)
5 + **4** × 3 = ?
Multiplication second (4 × 3 = 12)
5 + **12** = ?
Addition third (5 + 12 = 17)
Answer: 17
```

### Test 9:
```
18 - 2³ + 12 ÷ 3 = ?
Orders first (2³ = 2 × 2 × 2 = 8)
18 - **8** + 12 ÷ 3 = ?
Division second (12 ÷ 3 = 4)
18 - 8 + **4** = ?
Subtraction third (18 - 8 = 10)
**10** + 4 = ?
Addition last (10 + 4 = 14)
Answer: 14
```

### Test 10:
```
4 + 3² × 2 - 5 = ?
Orders first (3² = 3 × 3 = 9)
4 + **9** × 2 - 5 = ?
Multiplication second (9 × 2 = 18)
4 + **18** - 5 = ?
Subtraction third (18 - 5 = 13)
4 + **13** = ?
Addition last (4 + 13 = 17)
Answer: 17
```

From ChatGPT:
Fail - your final answer is correct: 17, but your order does not follow the standard left-to-right BODMAS procedure

```
4 + 3² × 2 - 5 = ?
Orders first (3² = 3 × 3 = 9)
4 + **9** × 2 - 5 = ?
Multiplication second (9 × 2 = 18)
4 + **18** - 5 = ?
Addition third (4 + 18 = 22)
**22** - 5 = ?
Subtraction fourth (22 - 5 = 17)
Answer: 17
```

### Test 11:
```
24 ÷ 2² + 3 × 4 = ?
Orders first (2² = 2 × 2 = 4)
24 ÷ **4** + 3 × 4 = ?
Division (24 ÷ 4 = 6)
**6** + 3 × 4 = ?
Multiplication (3 × 4 = 12)
6 + **12** = ?
Addition (6 + 12 = 18)
Answer: 18
```

### Test 12:
```
40 ÷ (2 + 3) × 2² - 6 = ?
Brackets (2 + 3 = 5)
40 ÷ **5** × 2² - 6 = ?
Orders (2² = 2 × 2 = 4)
40 ÷ 5 × **4** - 6 = ?
Division (40 ÷ 5 = 8)
**8** × 4 - 6 = ?
Multiplication (8 × 4 = 32)
**32** - 6 = ?
Subtraction (32 - 6 = 26)
Answer: 26
```

### Test 13:
```
50 - 3² × 4 + 18 ÷ 3 = ?
Orders (3² = 3 × 3 = 9)
50 - **9** × 4 + 18 ÷ 3 = ?
Multiplication (9 × 4 = 36)
50 - **36** + 18 ÷ 3 = ?
Division (18 ÷ 3 = 6)
50 - 36 + **6** = ?
Subtraction (50 - 36 = 14)
**14** + 6 = ?
Addition (14 + 6 = 20)
Answer: 20
```

### Test 14:
```
72 ÷ 3² + 5 × 2 - 4 = ?
Orders (3² = 3 × 3 = 9)
72 ÷ **9** + 5 × 2 - 4 = ?
Division (72 ÷ 9 = 8)
**8** + 5 × 2 - 4 = ?
Multiplication (5 × 2 = 10)
8 + **10** - 4 = ?
Addition (8 + 10 = 18)
**18** - 4 = ?
Subtraction (18 - 4 = 14)
Answer: 14
```

### Test 15:
```
60 ÷ (4 + 2) + 2³ × 3 - 5 = ?
Brackets (4 + 2 = 6)
60 ÷ **6** + 2³ × 3 - 5 = ?
Orders (2³ = 2 × 2 × 2 = 8)
60 ÷ 6 + **8** × 3 - 5 = ?
Division (60 ÷ 6 = 10)
**10** + 8 × 3 - 5 = ?
Multiplication (8 × 3 = 24)
10 + **24** - 5 = ?
Addition (10 + 24 = 34)
**34** - 5 = ?
Subtraction (34 - 5 = 29)
Answer: 29
```

### Test 16:
```
48 ÷ 2³ + (7 - 3) × 5 = ?
Brackets (7 - 3 = 4)
48 ÷ 2³ + **4** × 5 = ?
Orders (2³ = 2 × 2 × 2 = 8)
48 ÷ **8** + 4 × 5 = ?
Division (48 ÷ 8 = 6)
**6** + 4 × 5 = ?
Multiplication (4 × 5 = 20)
6 + **20** = ?
Addition (6 + 20 = 26)
Answer: 26
```

### Test 17:
```
90 ÷ (3 × 5) + 4² - 7 = ?
Brackets (3 × 5 = 15)
90 ÷ **15** + 4² - 7 = ?
Orders (4² = 4 × 4 = 16)
90 ÷ 15 + **16** - 7 = ?
Division (90 ÷ 15 = 6)
**6** + 16 - 7 = ?
Addition (6 + 16 = 22)
**22** - 7 = ?
Subtraction (22 - 7 = 15)
Answer: 15
```

### Test 18:
```
64 ÷ 2³ + 3 × (6 - 2) = ?
Brackets (6 - 2 = 4)
64 ÷ 2³ + 3 × **4** = ?
Orders (2³ = 2 × 2 × 2 = 8)
64 ÷ **8** + 3 × 4 = ?
Division (64 ÷ 8 = 8)
**8** + 3 × 4 = ?
Multiplication (3 × 4 = 12)
8 + **12** = ?
Addition (8 + 12 = 20)
Answer: 20
```

### Test 19:
```
100 - 5² + 24 ÷ 6 × 3 = ?
Orders (5² = 5 × 5 = 25)
100 - **25** + 24 ÷ 6 × 3 = ?
Division (24 ÷ 6 = 4)
100 - 25 + **4** × 3 = ?
Multiplication (4 × 3 = 12)
100 - 25 + **12** = ?
Subtraction (100 - 25 = 75)
**75** + 12 = ?
Addition (75 + 12 = 87)
Answer: 87
```

### Test 20:
```
84 ÷ (2 + 5) + 3² × 2 - 1 = ?
Brackets (2 + 5 = 7)
84 ÷ **7** + 3² × 2 - 1 = ?
Orders (3² = 3 × 3 = 9)
84 ÷ 7 + **9** × 2 - 1 = ?
Division (84 ÷ 7 = 12)
**12** + 9 × 2 - 1 = ?
Multiplication (9 × 2 = 18)
12 + **18** - 1 = ?
Addition (12 + 18 = 30)
**30** - 1 = ?
Subtraction (30 - 1 = 29)
Answer: 29
```

---

## Basic powers

```
1² → 1 × 1 = 1
1³ → 1 × 1 × 1 = 1

2² → 2 × 2 = 4
2³ → 2 × 2 × 2 = 8

3² → 3 × 3 = 9
3³ → 3 × 3 × 3 = 27

4² → 4 × 4 = 16
4³ → 4 × 4 × 4 = 64

5² → 5 × 5 = 25
5³ → 5 × 5 × 5 = 125

6² → 6 × 6 = 36
6³ → 6 × 6 × 6 = 216

7² → 7 × 7 = 49
7³ → 7 × 7 × 7 = 343

8² → 8 × 8 = 64
8³ → 8 × 8 × 8 = 512

9² → 9 × 9 = 81
9³ → 9 × 9 × 9 = 729

10² → 10 × 10 = 100
10³ → 10 × 10 × 10 = 1000
```

---

## Basic roots

Powers are easier for my brain as I can break it up visually: 

`2³ = 2 × 2 × 2 = 8`

Even though roots are just the opposite, I am finding this harder to unpack: `√9`

ChatGPT recommendation:

`√9 → ? × ? = 9 → 3`

### A quick review of some common root examples:

```
√1   → 1 × 1 = 1     → 1
√4   → 2 × 2 = 4     → 2
√9   → 3 × 3 = 9     → 3
√16  → 4 × 4 = 16    → 4
√25  → 5 × 5 = 25    → 5
√36  → 6 × 6 = 36    → 6
√49  → 7 × 7 = 49    → 7
√64  → 8 × 8 = 64    → 8
√81  → 9 × 9 = 81    → 9
√100 → 10 × 10 = 100 → 10
√121 → 11 × 11 = 121 → 11
√144 → 12 × 12 = 144 → 12
```

---

## Notes on extended roots

On paper, you would draw the root line over the whole expression, but digitally it is easier to express with brackets.

I learned from ChatGPT that anything inside the brackets is "under the root symbol":

`√(9 + 7)`

---

## More BODMAS tests

### Test 21:
```
4 + √81 × 2 = ?
= 4 + **9** × 2
= 4 + **18**
= 22
```

### Test 22:
```
10 + √(20 + 16) × 4 = ?
= 10 + √**36** × 4
= 10 + **6** × 4
= 10 + **24**
= 34
```

### Test 23:
```
7 + √(55 + 9) × 3 = ?
= 7 + √**64** × 3
= 7 + **8** × 3
= 7 + **24**
= 31
```

### Test 24:
```
72 ÷ (2 + 4) + 3² × 3 - 7 = ?
= 72 ÷ **6** + 3² × 3 - 7
= 72 ÷ 6 + **9** × 3 - 7
= **12** + 9 × 3 - 7
= 12 + **27** - 7
= **39** - 7
= 32
```

### Test 25:
```
28 ÷ 4 - 5 + 3³ = ?
= 28 ÷ 4 - 5 + **27**
= **7** - 5 + 27
= **2** + 27
= 29
```

### Test 26:
```
5 + 4² × 5 = ?
= 5 + **16** × 5
= 5 + **80**
= 85
```

### Test 27:
```
60 ÷ (5 + 5) + 4² × 2 - 1 = ?
= 60 ÷ **10** + 4² × 2 - 1
= 60 ÷ 10 + **16** × 2 - 1
= **6** + 16 × 2 - 1
= 6 + **32** - 1
= **38** - 1
= 37
```

### Test 28:
```
13 + 3² × 2 = ?
= 13 + **9** × 2
= 13 + **18**
= 31
```

### Test 29:
```
49 ÷ (4 + 3) + 2² × 2 - 3 = ?
= 49 ÷ **7** + 2² × 2 - 3
= 49 ÷ 7 + **4** × 2 - 3
= **7** + 4 × 2 - 3
= 7 + **8** - 3
= **15** - 3
= 12
```

### Test 30:
```
3 + √(9 + 7) × 3 = ?
= 3 + √**16** × 3
= 3 + **4** × 3
= 3 + **12**
= 15
```

### Test 31:
```
20 ÷ 2 - 9 + 3³ = ?

3³ = 3 × 3 × 3 = 27 <<-- extra step just for my brain

= 20 ÷ 2 - 9 + **27**
= **10** - 9 + 27
= **1** + 27
= 28
```

### Test 32:
```
63 ÷ (4 + 3) + 2² × 3 - 2 = ?
= 63 ÷ **7** + 2² × 3 - 2

2² = 2 × 2 = 4 <<-- extra step

= 63 ÷ 7 + **4** × 3 - 2
= **9** + 4 × 3 - 2
= 9 + **12** - 2
= **21** - 2
= 19
```

### Test 33:
```
48 ÷ 6 × 3 + 20 - 5 + 4 = ?
= **8** × 3 + 20 - 5 + 4
= **24** + 20 - 5 + 4
= **44** - 5 + 4
= **39** + 4
= 43
```

### Test 34:
```
72 ÷ 8 × 5 - 12 + 7 - 3 = ?
= **9** × 5 - 12 + 7 - 3
= **45** - 12 + 7 - 3
= **33** + 7 - 3
= **40** - 3
= 37
```

---

## Tests focusing on divisions, multiplications, subtractions and additions

### Test 35:
```
15 - 6 + 24 ÷ 4 × 3 - 2 = ?

15 -(3) 6 +(4) 24 ÷(1) 4 ×(2) 3 -(5) 2 = ? <<-- extra step to show order

= 15 - 6 + **6** × 3 - 2
= 15 - 6 + **18** - 2
= **9** + 18 - 2
= **27** - 2
= 25
```

### Test 36:
```
18 + 7 - 32 ÷ 4 × 2 + 5 = ?

18 +(3) 7 -(4) 32 ÷(1) 4 ×(2) 2 +(5) 5 = ?  <<-- extra step to show order

= 18 + 7 - **8** × 2 + 5
= 18 + 7 - **16** + 5
= **25** - 16 + 5
= **9** + 5
= 14
```

### Test 37:
```
40 - 6 + 36 ÷ 6 × 2 - 5 = ?
= 40 - 6 + **6** × 2 - 5
= 40 - 6 + **12** - 5
= **34** + 12 - 5
= **46** - 5
= 41
```

### Test 38:
```
12 + 30 ÷ 5 - 4 × 3 + 8 = ?
= 12 + **6** - 4 × 3 + 8
= 12 + 6 - **12** + 8
= **18** - 12 + 8
= **6** + 8
= 14
```

### Test 39:
```
50 - 18 ÷ 3 + 4 × 5 - 7 = ?
= 50 - **6** + 4 × 5 - 7
= 50 - 6 + **20** - 7
= **44** + 20 - 7
= **64** - 7
= 57
```

### Test 40:
```
21 + 48 ÷ 6 - 3 × 4 + 10 = ?
= 21 + **8** - 3 × 4 + 10
= 21 + 8 - **12** + 10
= **29** - 12 + 10
= **17** + 10
= 27
```

---

## New tests on negatives

### Test 41:
```
5 - 12 + 4 = ?
= **-6** + 4
= -2
```
Fail! Off-by-one below zero. The gap from 5 to 12 is 7, not 6.
```
5 - 12 + 4 = ?
= **-7** + 4
= -3
```

### Test 42:
```
8 - 3 × 4 = ?
= 8 - **12**
= 4
```
Fail! Forgot the negative symbol

```
8 - 3 × 4 = ?
= 8 - **12**
= -4
```

### Test 43:
```
20 ÷ 4 - 9 + 2 = ?
= **5** - 9 + 2
= **-4** + 2
= 2
```

Fail: sign correct in the step, lost in the result. -4 + 2 = -2.

```
20 ÷ 4 - 9 + 2 = ?
= **5** - 9 + 2
= **-4** + 2
= -2
```

### Test 44:
```
6 - 2³ + 5 = ?
2³ = 2 × 2 × 2 = 8 <<- working out - noticing errors above, attempting to slow down
= 6 - **8** + 5
= **-2** + 5
= 3
```

### Test 45:
```
10 - 4 × 5 + 3² = ?
3² = 3 × 3 = 9 <<- working out
= 10 - 4 × 5 + **9** 
= 10 - **20** + 9
= **-10** + 9
= -1
```

### Test 46:
```
7 - 15 + 3 = ?
= **-8** + 3
= -5
```

### Test 47:
```
12 - 36 ÷ 4 - 8 = ?
= 12 - **9** - 8
= **3** - 8
= -5
```

### Test 48:
```
4 × 3 - 20 + 5 = ?
= **12** - 20 + 5
= **-8** + 5
= -3
```

### Test 49:
```
5 - 4² + 6 = ?
4² = 4 × 4 = 16 <<- working out was done after adding "8" below, so the problem was identified
= 5 - **8** + 6
= **-3** + 6
= 3
```

Fail: wrote 8 instead of 16

```
5 - 4² + 6 = ?
4² = 4 × 4 = 16 <<- working out
= 5 - **16** + 6
= **-11** + 6
= -5
```

### Test 50:
```
30 ÷ (2 + 4) - 12 + 3 = ?
= 30 ÷ **6** - 12 + 3
= **5** - 12 + 3
= **-7** + 3
= -4
```

---

## Tests from Claude to push aspects of my learning

At this point, I switched from ChatGPT to Claude to get a different perspective:

### Test 51:
```
25 - 8 + 6 = ?
= **17** + 6
= 23
```

### Test 52:
```
12 - 5 × 4 + 3 = ?
= 12 - **20** + 3
= **-8** + 3
= -5
```

### Test 53:
```
5 + 3² - 8 = ?
3² = 3 × 3 = 9 <<-- working out
= 5 + **9** - 8
= **14** - 8
= 6
```

### Test 54:
```
40 - 12 + 7 - 5 = ?
= **28** + 7 - 5
= **35** - 5
= 30
```

### Test 55:
```
7 - √49 × 2 + 4 = ?
= 7 - **7** × 2 + 4
= 7 - **14** + 4
= **-7** + 4
= -3
```

### Test 56:
```
9 - 24 + 6 = ?
= **-15** + 6
= -9
```

### Test 57:
```
20 - 5² + 12 = ?
5² = 5 × 5 = 25 <<-- working out
= 20 - **25** + 12
= **-5** + 12
= 7
```

### Test 58:
```
18 - 5 + 9 - 2 = ?
= **13** + 9 - 2
= **22** - 2
= 20
```

### Test 59:
```
30 ÷ 5 - 14 + 2 = ?
= **6** - 14 + 2
= **-8** + 2
= -6
```

### Test 60:
```
6 × 2³ - 50 + 4 = ?
2³ = 2 × 2 × 2 = 8 <<-- working out
= 6 × **8** - 50 + 4
= **48** - 50 + 4
= **-2** + 4
= 2
```

---

## Decimals from Claude to move away from friendly numbers

### Test 61:
```
9 ÷ 2 + 5 = ?
= **4.5** + 5
= 9.5
```

### Test 62:
```
15 ÷ 2 - 10 = ?
= **7.5** - 10 
= -2.5
```
Note: This last step made me think a bit!

### Test 63:
```
3 + 7 ÷ 2 × 4 = ?
= 3 + **3.5** × 4
3.5 × 4 = 4 + 4 + 4 + 2 = 14 <<-- working out (cheating?)
= 3 + **14**
= 17
```

### Test 64:
```
5 ÷ 2 + 3² - 8 = ?
3² = 3 × 3 = 9 <<-- working out
= 5 ÷ 2 + **9** - 8 
= **2.5** + 9 - 8 
= **11.5** - 8 
= 3.5
```

### Test 65:
```
20 - 25 ÷ 2 = ?
= 20 - **12.5**
= 7.5
```
Note: I initially wrote 8.5

### Test 66:
```
11 ÷ 2 + 4 - 12 = ?
= **5.5** + 4 - 12
= **9.5** - 12
= -2.5
```

### Test 67:
```
2 × 9 ÷ 4 + 6 = ?
= **18** ÷ 4 + 6
= **4.5** + 6
= 10.5
```

### Test 68:
```
30 ÷ 4 - 10 + 2 = ?
= **7.5** - 10 + 2
= **-2.5** + 2
= -0.5
```

### Test 69:
```
7 ÷ 2 × 2³ - 20 = ?
2³ = 2 × 2 × 2 = 8 <<-- working out
= 7 ÷ 2 × **8** - 20
= **3.5** × 8 - 20
3.5 × 8 = 8 + 8 + 8 + 4 = 28 <<-- working out (cheating?)
= **28** - 20
= 8
```

### Test 70:
```
1 + 13 ÷ 2 - 9 = ?
= 1 + **6.5** - 9
= **7.5** - 9
= -1.5
```

---

## More tests from Claude

Claude suggested wrapping negative numbers in brackets to help maintain the minus symbol - to see if this helps. I tried it, let it lapse but then picked it up again later. I did not go back and "fix" instances where brackets were missing as this shows a clear indication when I did and did not use this method.

### Test 71:
```
3 × 8 ÷ 4 + 5 = ?
= **24** ÷ 4 + 5
= **6** + 5
= 1
```

Fail: dropped a digit

```
3 × 8 ÷ 4 + 5 = ?
= **24** ÷ 4 + 5
= **6** + 5
= 11
```

### Test 72:
```
6 × 5 ÷ 3 - 12 = ?
= **30** ÷ 3 - 12
= **10** - 12
= (-2)
```

### Test 73:
```
2 × 7 ÷ 4 + 3 = ?
= **14** ÷ 4 + 3
14 ÷ 4 → 4 + 4 + 4 + 2 = 14 → 3.5 <<-- working out
= **3.5** + 3
= 6.5
```

### Test 74:
```
20 ÷ 4 × 3 ÷ 5 = ?
= **5** × 3 ÷ 5
= **15** ÷ 5
= 3
```

### Test 75:
```
9 × 4 ÷ 6 - 10 + 3 = ?
= **36** ÷ 6 - 10 + 3
= **6** - 10 + 3
= **(-4)** - 10 + 3
= **(-14)** + 3
= (-11)
```
Fail: the (- 10) should have been removed

```
9 × 4 ÷ 6 - 10 + 3 = ?
= **36** ÷ 6 - 10 + 3
= **6** - 10 + 3
= **(-4)** + 3
= (-1)
```

### Test 76:
```
5 × 2³ ÷ 4 = ?
2³ = 2 × 2 × 2 = 8 <<-- working out
= 5 × **8** ÷ 4
= **40** ÷ 4 <<-- originally wrote 48
= 10
```

### Test 77:
```
3 × 6 ÷ 4 - 8 = ?
= **18** ÷ 4 - 8
18 ÷ 4 → 4 + 4 + 4 + 4 + 2 = 18 → 4.5 <<-- working out
= **4.5** - 8
= (-3.5)
```

### Test 78:
```
12 ÷ 2 × 5 ÷ 4 + 1 = ?
= **6** × 5 ÷ 4 + 1
= **30** ÷ 4 + 1
30 ÷ 4 → 4 + 4 + 4 + 4 + 4 + 4 + 4 + 2 = 30 → 7.5 <<-- working out
= **7.5** + 1
= 8.5
```

### Test 79:
```
4 × √36 ÷ 3 - 12 = ?
= 4 × **6** ÷ 3 - 12
= **24** ÷ 3 - 12
= **8** - 12
= (-4)
```

### Test 80:
```
2 × (7 - 3) ÷ 4 × 5 - 15 = ?
= 2 × **4** ÷ 4 × 5 - 15
= **8** ÷ 4 × 5 - 15
= **2** × 5 - 15
= **10** - 15
= (-5)
```

---

## Division chains - plus some extras thrown in

### Test 81:
```
48 ÷ 4 ÷ 2 = ?
= **12** ÷ 2 
= 6
```

### Test 82:
```
90 ÷ 3 ÷ 6 = ?
= **30** ÷ 6
= 5
```

### Test 83:
```
72 ÷ 6 ÷ 2 + 5 = ?
= **12** ÷ 2 + 5
= **6** + 5
= 11
```

### Test 84:
```
36 ÷ 3 ÷ 2 - 15 = ?
= **12** ÷ 2 - 15
= **6** - 15
= 9
```
Fail: Dropped the negative again. Lesson: add brackets as soon as I encounter a negative number, not later.

```
36 ÷ 3 ÷ 2 - 15 = ?
= **12** ÷ 2 - 15
= **6** - 15
= (-9)
```

### Test 85:
```
18 ÷ 4 ÷ 3 = ?
= **4.5** ÷ 3
4.5 ÷ 3 → 1.5 + 1.5 + 1.5 = 4.5 → 1.5 <<-- working out
= 1.5
```
Note: this one was harder for me, dividing 3 into 4.5

### Test 86:
```
24 ÷ 6 × 2 ÷ 4 = ?
= **4** × 2 ÷ 4
= **8** ÷ 4
= 2
```

### Test 87:
```
60 ÷ (2 + 3) ÷ 4 = ?
= 60 ÷ **5** ÷ 4
= **12** ÷ 4
= 3
```

### Test 88:
```
64 ÷ 2³ ÷ 2 = ?
2³ = 2 × 2 × 2 = 8 <<-- working out
= 64 ÷ **8** ÷ 2
= **8** ÷ 2
= 4
```

### Test 89:
```
7 + 96 ÷ √16 ÷ 6 = ?
= 7 + 96 ÷ **4** ÷ 6
96 ÷ 4 → 24 + 24 + 24 + 24 = 96 → 24 <<-- working out
= 7 + **24** ÷ 6
= 7 + **4**
= 11
```

### Test 90:
```
80 ÷ 4 ÷ 5 - 9 + 2 = ?
= **20** ÷ 5 - 9 + 2
= **4** - 9 + 2
= **(-5)** + 2
= (-3)
```

---

## Back to basics - learning how to add and subtract

I realised I can now do quite complex BODMAS equations - with friendly numbers. The reason, it is just about getting the order right.

But I can't do basic addition, subtraction, multiplication or division.

So, I'm going back to absolute basics.

Here is how I would tackle two-digit additions with decomposition:

```
83 + 25 = ?
80 + 20 = 100
3 + 5 = 8
100 + 8 = 108
```

Here is how I would tackle two-digit subtractions:

```
56 - 32 = ?
50 - 30 = 20
6 - 2 = 4
20 + 4 = 24
```

Claude suggested a simpler way for both - "Jump Strategy" over "Split Strategy".

- Lower cognitive load
- Fewer steps
- Safer for subtraction

```
83 + 25 = ?
83 + 20 = 103
103 + 5 = 108
```

```
56 - 32 = ?
56 - 30 = 26
26 - 2  = 24
```

This becomes much easier when dealing with higher numbers at the right:

```
56 - 38 = ?
56 - 30 = 26
26 - 8  = 18
```

So, some two two-digit additions:

### Test 91:
```
68 + 25 = ?
68 + 20 = 88
88 + 5 = 93
```

### Test 92:
```
47 + 36 = ?
47 + 30 = 77
77 + 6 = 83
```

### Test 93:
```
68 + 29 = ?
68 + 20 = 88
88 + 9 = 97
```

### Test 94:
```
77 + 46 = ?
77 + 40 = 117
117 + 6 = 123
```

### Test 95:
```
47 + 35 = ?
47 + 30 = 77
77 + 5 = 82
```

### Test 96:
```
68 + 24 = ?
68 + 20 = 88
88 + 4 = 92
```

### Test 97:
```
19 + 56 = ?
19 + 50 = 69
69 + 6 = 75
```

### Test 98:
```
12 + 83 = ?
12 + 80 = 92
92 + 3 = 95
```

### Test 99:
```
27 + 49 = ?
27 + 40 = 67
67 + 9 = 76
```

### Test 100:
```
43 + 96 = ?
43 + 90 = 133
133 + 6 = 139
```

Now some two two-digit subtractions:

### Test 101:
```
73 - 46 = ?
73 - 40 = 33 <<-- this was still a struggle - not sure why - got confused
33 - 6 = 27
```

### Test 102:
```
82 - 57 = ?
82 - 50 = 32
32 - 7 = 25
```

### Test 103:
```
64 - 28 = ?
64 - 20 = 44
44 - 8 = 36
```

### Test 104:
Note: this was thrown in as a three-digit problem:
```
234 - 78 = ?
234 - 70 = 164 <<-- literally counted on my fingers
164 - 8 = 156
```

### Test 105:
```
59 - 25 = ?
59 - 20 = 39
39 - 5 = 34
```

### Test 106:
```
59 - 48 = ?
59 - 40 = 19
19 - 8 = 11
```

### Test 107:
```
39 - 15 = ?
39 - 10 = 29
29 - 5 = 24
```

### Test 108:
```
34 - 16 = ?
34 - 10 = 24
24 - 6 = 18
```

### Test 109:
```
74 - 51 = ?
74 - 50 = 24
24 - 1 = 23
```

### Test 110:
```
94 - 86 = ?
94 - 80 = 14
14 - 6 = 8
```

---

## 20 addtions

### Test 111:
```
42 + 35 = ?
42 + 30 = 72
72 + 5 = 77

```

### Test 112:
```
61 + 27 = ?
61 + 20 = 81
81 + 7 = 88

```

### Test 113:
```
54 + 23 = ?
54 + 20 = 74
74 + 3 = 77
```

### Test 114:
```
72 + 16 = ?
72 + 10 = 82
82 + 6 = 88
```

### Test 115:
```
35 + 42 = ?
35 + 40 = 75
75 + 2 = 77
```

### Test 116:
```
48 + 25 = ?
48 + 20 = 68
68 + 5 = 73
```

### Test 117:
```
67 + 18 = ?
67 + 10 = 77
77 + 8 = 85
```

### Test 118:
```
39 + 44 = ?
39 + 40 = 79
79 + 4 = 83
```

### Test 119:
```
56 + 37 = ?
56 + 30 = 86
86 + 7 = 93
```

### Test 120:
```
28 + 65 = ?
28 + 60 = 88
88 + 5 = 93
```

### Test 121:
```
47 + 38 = ?
47 + 30 = 77
77 + 8 = 85
```

### Test 122:
```
59 + 26 = ?
59 + 20 = 79
79 + 6 = 85
```

### Test 123:
```
68 + 27 = ?
68 + 20 = 88
88 + 7 = 95
```

### Test 124:
```
74 + 39 = ?
74 + 30 = 104
104 + 9 = 113
```

### Test 125:
```
86 + 47 = ?
86 + 40 = 126
126 + 7 = 133
```

### Test 126:
```
57 + 68 = ?
57 + 60 = 117
117 + 8 = 125
```

### Test 127:
```
79 + 46 = ?
79 + 40 = 119
119 + 6 = 125
```

### Test 128:
```
88 + 57 = ?
88 + 50 = 138
138 + 7 = 145
```

### Test 129:
```
67 + 89 = ?
67 + 80 = 147
147 + 9 = 156
```

### Test 130:
```
96 + 78 = ?
96 + 70 = 166
166 + 8 = 174
```

I noticed sometimes I still have blockers like an example below.
Is breaking it down further ok? Adding additional steps:

```
87 + 77 = ?
87 + 70 =  <<-- small mental block trying to add 80 and 70 in my head
87 + 20 = 107 <<-- immediately solvable as I know 80 + 20 = 100
107 + 50 = 157 <<-- remainder of the bigger number, I know 100 + 50 = 150
157 + 7 = 164 <<-- last digit
```

ChatGPT: If the normal tens jump feels immediate, use it. If it causes a mental block, break that jump into friendlier chunks.

---

## 20 subtractions

### Test 131:
```
68 - 24 = ?
68 - 20 = 48
48 - 4 = 44
```

### Test 132:
```
75 - 32 = ?
75 - 30 = 45
45 - 2 = 43
```

### Test 133:
```
89 - 45 = ?
89 - 40 = 49
49 - 5 = 44
```

### Test 134:
```
57 - 23 = ?
57 - 20 = 37
37 - 3 = 34
```

### Test 135:
```
96 - 51 = ?
96 - 50 = 46
46 - 1 = 45
```

### Test 136:
```
72 - 38 = ?
72 - 30 = 52 <<-- initial attempt
72 - 30 = 42 <<-- fixed
42 - 8 = 34
```

### Test 137:
```
81 - 46 = ?
81 - 40 = 41
41 - 6 = 35
```

### Test 138:
```
63 - 27 = ?
63 - 20 = 43
43 - 7 = 36
```

### Test 139:
```
94 - 58 = ?
94 - 50 = 44
44 - 8 = 36
```

### Test 140:
```
76 - 49 = ?
76 - 40 = 36
36 - 9 = 27
```

### Test 141:
```
85 - 67 = ?
85 - 60 = 25
25 - 7 = 18
```

### Test 142:
```
71 - 54 = ?
71 - 50 = 21
21 - 4 = 17
```

### Test 143:
```
92 - 76 = ?
92 - 70 = 22
22 - 6 = 16
```

### Test 144:
```
64 - 48 = ?
64 - 40 = 24
24 - 8 = 16
```

### Test 145:
```
83 - 69 = ?
83 - 60 = 22 <<-- wrote 22, but mentally continued with the correct 23
23 - 9 = 14
```

### Test 146:
```
91 - 74 = ?
91 - 70 = 21
21 - 4 = 17
```

### Test 147:
```
73 - 58 = ?
73 - 50 = 23
23 - 8 = 15
```

### Test 148:
```
82 - 67 = ?
82 - 60 = 22
22 - 7 = 15
```

### Test 149:
```
95 - 78 = ?
95 - 70 = 25
25 - 8 = 17
```

### Test 150:
```
84 - 59 = ?
84 - 50 = 34
34 - 9 = 25
```

---

## nnn + nnn

### Test 151:
```
247 + 136 = ?
247 + 100 = 347
347 + 30 = 377
377 + 6 = 383
```

### Test 152:
```
384 + 257 = ?
384 + 200 = 584
584 + 50 = 634
634 + 7 = 641
```

### Test 153:
```
562 + 319 = ?
562 + 300 = 862
862 + 10 = 872
872 + 9 = 881
```

### Test 154:
```
438 + 475 = ?
438 + 400 = 837 <<-- transcription error
837 + 70 = 907
907 + 5 = 912
```
Fixed:
```
438 + 475 = ?
438 + 400 = 838
838 + 70 = 908
908 + 5 = 913
```

### Test 155:
```
691 + 248 = ?
691 + 200 = 891
891 + 40 = 931
931 + 8 = 939
```

### Test 156:
```
357 + 586 = ?
357 + 500 = 857
857 + 80 = 937
937 + 6 = 943
```

### Test 157:
```
724 + 169 = ?
724 + 100 = 824
824 + 60 = 884
884 + 9 = 893
```

### Test 158:
```
483 + 397 = ?
483 + 300 = 783
783 + 20 = 803
803 + 70 = 873
873 + 7 = 880
```

### Test 159:
```
615 + 278 = ?
615 + 200 = 815
815 + 70 = 885
885 + 8 = 893
```

### Test 160:
```
746 + 185 = ?
746 + 100 = 846
846 + 60 = 906
906 + 20 = 926
926 + 5 = 931
```

One thing I found interesting, for the first step, you are only adding to one number, the hundreds column.
So it is literally adding two single numbers. It makes it so easy:

```
384 + 257 = ?
(3)84 + (2)00 = (5)84
```

Oddly, I was feeling that the middle one that is harder.
But I was thinking about two digits in both cases: 

```
384 + 257 = ? 
384 + 200 = 584
5(84) + (50) = 634
634 + 7 = 641
```

But really, it should have been the same again - focus on one number

```
384 + 257 = ?
384 + 200 = 584
5(8)4 + (5)0 = 634
634 + 7 = 641
```

Brackets added here just to help identify numbers I am focussing on.

---

## nnn - nnn

### Test 161:
```
684 - 231 = ?
684 - 200 = 484
484 - 30 = 454
454 - 1 = 453
```

### Test 162:
```
752 - 348 = ?
752 - 300 = 452
452 - 40 = 412
412 - 8 = 404
```

### Test 163:
```
913 - 476 = ?
913 - 400 = 513
513 - 10 = 503
503 - 60 = 443
443 - 6 = 437
```

### Test 164:
```
845 - 329 = ?
845 - 300 = 545
545 - 20 = 525
525 - 9 = 516
```

### Test 165:
```
671 - 258 = ?
671 - 200 = 471
471 - 50 = 421
421 - 8 = 413
```

### Test 166:
```
936 - 487 = ?
936 - 400 = 536
536 - 30 = 506
506 - 50 = 456
456 - 7 = 449
```

### Test 167:
```
804 - 376 = ?
804 - 300 = 504
504 - 70 = 434
434 - 6 = 428
```

### Test 168:
```
725 - 468 = ?
725 - 400 = 325
325 - 20 = 305
305 - 40 = 265
265 - 8 = 257
```

### Test 169:
```
882 - 597 = ?
882 - 500 = 382
382 - 80 = 302
302 - 10 = 292
292 - 7 = 285
```

### Test 170:
```
763 - 584 = ?
763 - 500 = 263
263 - 60 = 203
203 - 20 = 183
183 - 4 = 179
```

Another observation. It is late. I am tired. And complex numbers are hard at the best of times. I found that choosing something that was easy for my tired brain, actually helped.

```
203 - 80 = 123 <<-- too hard when it is late and I'm tired
```

```
263 - 60 = 203 <<-- easy
203 - 20 = 183 <<-- easy
```

---

## A mix of additions and subtractions

I intend to use the following formula.
1. Left to right, regardless of the operator.
2. Break each part down so it is not overwhelming

For example:
```
56 - 34 + 97 = ?

56 - 34 = ?
56 - 30 = 26
26 - 4 = 22

22 + 97 = ?
22 + 90 = 112
112 + 7 = 119
```

### Test 171:
```
56 - 34 + 27 = ?
56 - 34 = ?
56 - 30 = 26
26 - 4 = 22
22 + 27 = ? <<-- this is one I could have actually done in one step
22 + 20 = 42
42 + 7 = 49
```

### Test 172:
```
42 + 18 - 25 = ?
42 + 18 = ?
42 + 10 = 52
52 + 8 = 60
60 - 25 = ?
60 - 20 = 40
40 - 5 = 35
```

### Test 173:
```
75 - 23 + 14 = ?
75 - 23 = ?
75 - 20 = 55
55 - 2 = 52 <<-- transcription error: should have written 55 - 3 = 52
52 + 14 = 66
```

### Test 174:
```
63 + 16 - 29 = ?
63 + 16 = ?
63 + 10 = 73
73 + 6 = 79
79 - 29 = ?
79 - 20 = 59
59 - 9 = 50
```

### Test 175:
```
88 - 40 + 12 = ?
88 - 40 = 48
48 + 12 = 60 <<-- very quick as both calculation were easy to see
```

### Test 176:
```
54 + 25 - 31 = ?
54 + 25 = 79
79 - 31 = ?
79 - 30 = 49
49 - 1 = 48
```

### Test 177:
```
67 - 15 - 22 = ?
67 - 15 = 52
52 + 22 = 74 <<-- fail. Switched - to +
```
Fail.

```
67 - 15 - 22 = ?
67 - 15 = 52
52 - 22 = 30
```

### Test 178:
```
72 - 30 - 18 = ?
72 - 30 = 42
42 - 18 = ?
42 - 10 = 32
32 - 8 = 24
```

### Test 179:
```
38 + 27 - 15 = ?
38 + 27 = ?
38 + 20 = 58
58 + 7 = 65
65 - 15 = 50
```

### Test 180:
```
91 - 50 + 26 = ?
91 - 50 = 41
41 + 26 = 67
```

### Test 181:
```
46 + 32 - 28 = ?
46 + 32 = 78
78 - 28 = 50
```

### Test 182:
```
84 - 21 + 35 = ?
84 - 21 = 63
63 + 35 = 98
```

### Test 183:
```
59 - 17 - 24 = ?
59 - 17 = 42
42 - 20 = 22
22 - 4 = 18
```

### Test 184:
```
33 + 45 - 26 = ?
33 + 40 = 73
73 + 5 = 78
78 - 20 = 58
58 - 6 = 52
```

### Test 185:
```
76 - 24 + 31 = ?
76 - 24 = 52
52 + 31 = 83
```

### Test 186:
```
48 + 36 - 42 = ?
48 + 30 = 78
78 + 6 = 84
84 - 42 = 42
```

### Test 187:
```
95 - 32 - 21 = ?
95 - 32 = 63
63 - 21 = 42
```

### Test 188:
```
61 - 20 + 38 = ?
61 - 20 = 41
41 + 38 = 79
```

### Test 189:
```
27 + 54 - 33 = ?
27 + 50 = 77
77 + 4 = 81
81 - 30 = 51
51 - 3 = 48
```

### Test 190:
```
83 - 41 + 25 = ?
83 - 41 = 42
42 + 25 = 67
```

---

## Next

- 
- Two and three number divisions
- Two and three number multiplications
- Negatives inside brackets: `5 × (3 - 8)`
- Two negatives multiplied: `-4 × -3`
- Nested brackets: `2 × (3 + (4 × 2))`

---
