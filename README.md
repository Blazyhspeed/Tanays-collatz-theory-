TANAY’S COLLATZ THEORY

Author: Tanay Gudadhe Date: May 2025 This is original work protected under copyright. Do not reproduce without permission.

ABSTRACT

This theory proves the collatz conjecture to be true by power of 2 , mods , logs , Contradiction  , Induction and more . This theory shows every number when followed by collatz rules -: 3n+1 when n is odd and n/2 when n is even reach 1.

INTRODUCTION

The collatz conjecture is a conjecture proposed by Lothar Collatz in 1937 . It is in the list of some of the most famous problems in mathematics.  The conjecture states that if any natural number by following the collatz rules will reach one . The collatz rules are C(n)=3n+1  n≡1 (mod 2) n/2    n≡0 (mod 2) This paper proves the collatz conjecture

DEFINITIONS

Loop-a Sequence of numbers Repeated

Even numbers-Numbers which are divisible by 2

Odd numbers-Numbers which are not divisible by 2

Collatz function C(n)-the notation that denotes rules of the collatz conjecture

Mod-Modular;remainder when divided by a number

Log-Logarithm;the base of the log is the base of power or exponent . The number is the base^a where a is any number .

Shrink-when the value of n decreases .

Shrink point-the point where the value of n starts decreasing in n like 27 which grow very large .

Loops or cycles-A pattern of numbers say we start with n and we stop at the same starting n and restarts again this continues forever .

2^k-Power of two

ℕ-set of natural numbers

+ℤ=set of positive integer

∀-For all

∃-There exists 

∃ !-There exists only 

¬-No or Not


WHY I THINK IT WORKS:

∀ n∈ℕ by following collatz rules always → 1 . it works with every +ℤ , because of ÷ and that if every digit in a number n are even⇔n≡0 (mod 2) and there is 2×even number in units place → we can n/2  2 times because if there are all even digits in a numbers if we ÷2 and there is 2×even number in units because of the 2×even digit in units place when it is ÷2 it is always even because it is 2×even so ÷2 means 2×even/2=even because ×2 and ÷2 cancel each other out  thus, [2×even]/2=even and even in units place means it is even thus It can be ÷2 2 times . C(n) is the notation for collatz functions when n is even⇔n≡0 (mod 2) or odd⇔n≡1 (mod 2) and n as any natural number . We will be using mod to define even and odd numbers .

PROOF

It works ∀ n∈ℕ because ÷ 2 →eventually 2^k which is n≡0 (mod 2) ⇔n is even so ÷2 so after ÷2 n→n≡0 (mod 2) until n→1 so it works for all numbers and odd⇔n≡1 (mod 2) →even⇔n≡0 (mod 2)  by 3n+1

C(n)= 3n+1        If n =odd. C(n)=n/2       If n=even

n=odd.      C(n)=3n+1.       3n+1=even

C(n)=n/2.     C(n)=eventually 2^k

(2^k)/2 = 2^k

until it reaches 2^k=4 =even 4/2=2/2=1

(C)n=1 When Followed by collatz rules

C(n)=3n+1     if n is odd C(n)=   n/2.    if n is even

n(even)=2k k = + ℤ

The 2  rules are:   C(n) = 3n + 1  (if n is odd)    C(n) = n ÷ 2  (if n is even)


(3n+1)/2 both steps 3n+1=n≡0 (mod 2)  and after that n/2 so combining steps = (3n+1)/2

MAIN PROOF STATEMENT

Some numbers value increases massively first but n/2 → 2^k ÷2 → 2^k-1 This continues until 2^k=2    2÷2 is 1

Now step-by-step:

1. 

Let's Take any natural number when n∈ℕ . Definition:  all ℕ =+ℤ

ℕ=1 to ∞

2. 

n where n≡0 (mod 2) or  n=2k ÷2.

n ÷ 2 = x.      2 × x = n.        n=2×x

let n be n=2k which makes an even number ⇔ when n≡0 (mod 2) where n∈ℕ        C(n)=n/2

3. 

If n is n=2k+1 or n≡1 (mod 2) in n∈ℕ it is odd , apply 3n+1.

3n + 1 always results in an n=2k or n≡0 (mod 2)⇔ when n=even .

Odd=3n+1


---

4. 

Repeat this process. In every case where any n≡0 (mod 2) , ÷ 2 applies again.

Odd→even by 3n+1 Than even apply n/2 so now repeat until it reaches 2^k Even so n/2→even until 2^k=2 than 2÷2=1

After each ÷ step: Even numbers are half of its original value.

Eventually leading towards 2^k.

3n+1. &       n/2. x times=2^k         
 when n=odd in n∈ℕ

odd=3n+1.     3n+1⇒even.     even=n/2

N>n So:

n → (after x steps) → 2^k

Repeated ÷ by 2 leads to 2^k because 2^k=2^(k) (n) and n/2 n÷2 so 2 in both equations is the same so they always reach 2^k until 2^k=2 which ÷2 is 1

PROOF ALL N REACH 2^K

This can also be proven by saying 2^k=2^(k) (f) means 2×2 n times so if we ÷ any number n÷2 = 2×y=n where y is quotient so 2 are common . These equations have a coefficient relation so ÷2 → 2^k . Numbers such as 27 reach numbers like 9000 until its value decreases but it can never be a loop (explained in section 9.) so C(n)=3n+1 when n≡1 (mod 2)         C(n)=n/2 when n≡0 (mod 2)

CONTRADICTION PROOF THAT ALL PATHS DECREASE

All paths → decrease because it will reach 2^k lets say 32 even so ÷2 =16 even so ÷2=8 even so ÷2=4 again n≡0 (mod 2) so ÷2=2 again even so ÷2=1 this works for all n in n∈ℕ and odd n in n∈ℕ become even when 3n+1 is applied . All paths go to 2^k so ÷2 will always be n≡0 (mod 2) until it reaches 1 so thus this contradicts that they will increase by this proof

5. 

Every time a n in n∈ℕ where n=2k⇔ n is even appears,  ÷2.

If n is even⇔2≡0 (mod 2): n ÷ 2

Eventually: n ÷ 2 ÷ 2 ÷ ... → 2^k

Even n=2k

even(appear)=even/2

even=(2k)/2

n= n≡0 ( mod 2) ⇒ C(n)=n/2

6. 

Eventually, numbers decrease to 2^k .

÷2 repeatedly ensures ∀ n ∃ 2^k ⇒ 2, 4, 8, 16, 32, etc. (2^k).

e÷2(x times)=2^k

SEQUENCE OF FORMULAS HOW THEY MIGHT OCCUR

n/2,  3n+1,  n/2... or. n/2,  n/2,  3n+1... or 3n+1,  n/2...

we will use log2(n)   it is important because it tells us how many times ÷2 is needed for 2^k to reach 1

Such as  log2(32)=5 because 2⁵=32


---

7. 

After reaching 2^k use log2(n) to see how many time ÷2 is needed to fully divide 2^k divisions by 2 continue. ∀ n∈ℕ ∃ 2^k by following the collatz rules

2^k ÷ 2 each time.

Eventually it becomes 2 → then 1.

Therefore, every n in n∈ℕ eventually leads to 1.

2^k÷2=1

This logic works for all n in n∈ℕ {1,2,3,4...∞}

Log2(n)=k in 2^k

8.BASE CASE

The smallest n in n∈ℕ is 1 so C(n)=1 1 is odd⇔n≡1 (mod 2) so we apply 3n+1 which is 4 . 4 is even so ÷2=2 again even so ÷2=1 4 is also 2^k which ÷2=even so 2^k÷2=even so if we keep ÷2 it will reach 1 Use log2(n) to find how many times we need to ÷ to get 1 from 2^k . Thus proved base case by solving smallest n

INDUCTIVE HYPOTHESIS

all n in n∈ℕ can be transformed into 1 by collatz rules and just assume now that it works for k number n=k because 1 reaches 1 by the following rules of the collatz conjecture

INDUCTION

Reach 1 means by following collatz rules the output eventually becomes 1 .The conjecture works for all  n=k+1 where n∈ℕ Because, it will reach 2^k so n/2 → n≡0 (mod 2) until 2^k is 2 so 2/2 is 1 or use log2(n)=k in 2^k to find how many times ÷2 Is needed to fully ÷ any 2^k and if k is even where k≡0 (mod 2) ⇔ k=2n  so k+1 will be n≡1 (mod 2) ⇔ k=2n+1  so 3n+1 which could be written as 3(k+1)+1 is N≡0 (mod 2) so ÷2 which→2^k it always→2^k because ÷2 and 2^k have a coefficient relation so they will reach each other so ÷2 will always→2^k which ÷2 until k in 2^k is 2 than ÷2 is 1 and also it can be a series of numbers and to make the process faster use log2(n) to find out how many times 2^k needs to be ÷2 to reach 1 . After 3n+1 value of n increases and n/2 halves it so it will always be smaller then the origional number . If n≡0 (mod 2) at starting follow collatz rules by starting with n/2 if n≡1 (mod 2) in starting follow by collatz rules starting with 3n+1 .so these will always reach 2^k by following the collatz rules so it always reaches 1 . The Hypothesis showed that it works for n=k where k=1 this proves that it also works for all n=k+1,n=k+2, ... so n=k has been proved in base case thus Inductive Hypothesis is also proved and n=k+1,n=k+2, ... is also proved by this step . All n increase by 3n+1 which will always be n≡0 (mod 2) so then n/2 halves the n in n∈ℕ which is smaller and there is a point where we have to ÷2  2 times so it becomes half of half so then from then it shrinks for numbers which increase in value very much first like 27but they do fall so any amount of 3n+1 is followed by n/2 which halves the value until it reaches 2^k.

n=k,n=k+1,n=k+2,n=k+3,...n=k+x

These numbers when always followed by collatz rules→1 . It always becomes 1 by following collatz rules because 3n+1=even so n/2 this will eventually lead to 2^k which ÷2 is even until 2^k=2 when ÷2 is 1 or use log2(n) .

PROOF THAT ALL NUMBERS REACH 2^k

All numbers eventually reach 2^k because 2^k=2^(k) (x) and n/2=2×x=n So they have 2 in common relation between two terms . So it always reaches 2^k

n÷2=2×x=n 2^k=2^(k) (x) Common=2 So, N/2=eventually 2^k


EDGE CASES

Some numbers like 27's value increases very much but they decrease because of 2^k and once they reach a n in n∈ℕ which has all n≡0 (mod 2) digits in it only 1 odd can also be OK and in units place there is a 2×even number then it can be ÷ 2  2 times so that is its shrinking point of all n in n∈ℕ which grow large when n in n∈ℕ hit this shrinking point they shrink in their value which reaches to 2^k

9. 

No other loops possible:

3n + 1 is not equal to n ÷ 2.

Expanded:

n + n + n + 1 is not equal to n ÷ 2.

Thus, a cycle cannot exist except the cycle  1.

If ∃ a loop like 33 it would have to be 3n+1 = even n/2=33 which cannot because 3n+1≠ n/2

¬ other loops exist than 1 because  if we apply that 3n+1≠n/2 but it is only one because [3n+1]+[n/2]=(3n+1)/2 which when n=1 becomes (3×1+1)/2=4/2=2 which ÷2=1 but it cannot exist for all n in n∈ℕ because when n=1 3n+1⇒3+1=2^k→k=2 and any other ×3 +1 ≠2^k→k=2 .

¬ complex cycles also exist because any n in n∈ℕ when ÷2→value becomes less and × by 3 and + 1→value greater then n/2 value is less this Sequence continues till numbers reach 2^k   . therefore a cycle ∃ ! when 3×1 where n=1 therefore, it only happens for 1 .

Other loops cannot exist because every n in n∈ℕ cannot be same if 3n+1 makes the value of n more and ÷2 makes the value of n ½ of n so they cannot exist unless n=1⇒3n=3

Also loops can't exist because any time we use 3n+1 than n/2 no matter how many times we do it it cannot be same because it reaches 2^k which ÷2 until 2^k→k=1  2÷2=1

CONTRADICTION OF CYCLES NOT EXISTING

A cycle in collatz is when the operations follow a pattern and never recharge one . A cycle is also sometimes called a loop . Lets just say that a cycle exists while following the collatz but because of 3n+1 the value of n increases and when ÷2 it gets halved again 3n+1 or n/2 if 3n+1 the value of n increases and if n/2 it again gets halved so by this process when it reaches a process where we can do n/2 2 times  so it is its decreasing point for n which grow very large like 27 from that point it shrinks beacsue it is ÷2 2 rimes for normal n also this doesn't happen for every n in the other case where n/2 doesn't happen 2 times only n/2 halves the number made by 3n+1 this Sequence goes on until it reaches a smaller n,  thus the assumed cycle can't happen thus this contradicts the existence of loops or cycles, for example  ∃ ! 1 loop because let's Take any n in n∈ℕ like n=18 lets just say for 18 ∃ a loop than ÷2→ value smaller lets say 18÷2=9 and 9=x for no confusion than 3x+1(because n is x) than new n so x<new n so they can never be same after n/2→ ½ of n so this also proves that numbers such as 43,34,67,etc dont have complex or normal loops . ÷2 will lead to smaller n in n∈ℕ then before so it will always→n less then before till it reaches 2^k once it reaches 2^k ÷2 will always be vwn until it reaches one so loops can never occur this contradicts the existence of loops .

Loops than 1 also can't exist because  all numbers when 3n+1 it's value becomes bigger than the original value . And ÷2 makes the value half or ½ of n . Means after 3n+1 we have to do ½n which makes n smaller so thus the values of n never natch so this rules out normal loops now complex loops , complex loops can never occur because all number reach 2^k which ÷2 is 2^(k-1) then 2^(k-2) until k is 0 so use log2(n) to know how many times to divide by 2 ro reach one this rules out complex loops

LOOPS EXISTENCE BY MODS

Loops also don't exist because 3n+1 makes N and N/2 makes x so N>x so a loop can never exist and complex Loops also can't exist because when 3n+1 where n≡1 (mod 2) which makes N even so N≡0 (mod 2) so N/2 this can never make a loop because remainders are different so it can never be same numbers every time

Formula for numbers which hit the same 2^k

I the author have made these formulas to show in collatz which numbers hit a specific 2^k . So we will see a formula for which numbers hit specific 2^k which is

Term (n)=n1+(n2-n1)n

which says numbers which hit a specific power of two (denoted as term (n) ) is the first number which hits it + (second-first number) × number   which says that what numbers reach a specific 2^k let's say 2^k=16 than 2⁵=9+(13-9)n=9+4n this is the formula for 2^k=2⁵ . Thus this formula shows which numbers hit a specific 2^k (in this case , 16) .

MY DECREASING FUNCTION IN COLLATZ

My decreasing function is (3n+1)/((3n+1)/2) ÷2 if n is odd . This always reaches 1 and for even convert to odd then apply this formula , so numbers always reach 1 by the collatz rules .

PROOFS



MAIN PROOF

All odd numbers⇒even by 3n+1 this happens every time because 3 is odd  n×3=odd+1=even

1st PROOF:

Every n in n∈ℕ when n=2k which is even can be  ÷2 because 2×k=x where x is even so we transpose 2 it becomes k=x÷2 where x is even means x=2k so every even number can be  ÷2.

Even numbers are built from 2 × 2^k:

Even = e.       Even = e ÷ 2.    2 × 2^k = even numbers

Even=e.      e=e/2



2nd PROOF:

All even numbers are multiples of 2, so they can be expressed as:

Even = 2 × k Even ÷ 2^k

Eventually reaching 1.

Multiples of 2 = 2×x

3rd PROOF:

All even numbers are divisible by 2 which  creates 2^k:

Even = e.                                       Even = e ÷ 2. 2 × 2 × 2 × ... × 2 = 2^k

PROOF FOR 1,2,3 PROFES

Numbers such as 27 value grow very much before decreasing but it's value always decreases because n/2 which leads to 2^k which ÷2 repeatedly because 2^k÷2=even always because they are made by 2×2...×2 and 2×x=2k (even) becomes 1

PROOF IT WORKS FOR ALL NUMBER  SAME

It doesn't behave differently for any number because every number when 3n+1 is 2k (even) and than n/2 which always eventually 2^k which repeatedly ÷2 =1


Collatz conjecture rules are 3n+1→even after that n/2 if we combine⇒(3n+1)/2 and 3n+1 always will be divisible by 2 because when an odd number is ×3 it is odd because it is × odd number and +1 makes n even so always it is ÷ by 2 so this formula has a meaning the upper when solved always is an even number so after solving it becomes a number n so now 3n+1=n So (3n+1)/2=N/2  simplified where n in n∈ℕ can be both n=2k and n=2k+ especially n=2k+1 so again applies 3n+1 this process repeats so it seems like a infinite cycle but it cannot be possible because this process gets 2^k as an answer eventually which ÷2=1 this is how every number which is in n∈ℕ by following these rules reaches 1 and by following these rules it always reaches 2^k because 2^k=n(even)/2 Because n(even)/2=Q(x) Q is for quotient So Q=2^k Eventually as 2 is common in both ÷2 and 2^k and let's assume a number x when ÷2 it becomes half of its original value and then 3n+1=n then again n is half of its original value so eventually 2^k=1/2×n(even) so it becomes 2^k


GRAPH  EXPLANATION

Let's assume a graph which contains odd even  1 3n+1 n/2  2^k  and a equation 2x+y substitute any value to make number 2 to infinite to show natural number set use 2x+y to form any number such as 2 , 3, 4 , 5 ... n if it's 2^k it will go to 1 and if 3n+1=even and n/2=odd or even it will always reach 1 for all 2x+y because of that point on the graph 2^k so when it reaches that point ÷2 will always be even until it reaches 2 so 2÷2 is 1 so this is how all positive integers reach 1 by following the collatz rules


ALGEBRAIC  EXPLANATION

2x+y=n  So, n/2 when even so n/2= eventually reaching 2^k   so every number can be made by 2x+y and it can also be made by 3x-y so 2x+y= all n and 3x-y=all n so thus following and substituting values of x and y as anything so one equation that has any constant(coefficient) and any values of x and y can make up all n so we can denote n as one equation 2x+y so 3n+1=3(2x+y)+1=n(even) So after that even so n/2 and as n=2x+y it becomes n/2=(2x+y)/2 Or 1/2×(2x+y) which is odd or even


DEEPER  PROOF  OF  NUMBERS  REACHING 2^k

All n in n∈ℕ reach 2^k before getting to 1 because 2^k÷2 always is even so until it reaches 2 It will always be n≡0 (mod 2) so 2÷2=1 because numbers when n/2 they become half of their original value and 2^k also reach when even numbers are half of their original value so eventually every number reach 2^k to become 1 So if we ÷ even numbers by 2 and relations of two terms n/2 and 2^k have 2 in common so dividing by 2 leads to 2^k . They also have a coefficient relation that is really important . Like in balancing Algebraic equations to solve for values of variables we have tk transpose ÷2 if there is and it will make ×2 so 2^k is 2×2×2...×2 k times so ÷2 always reach 2^k and 2^k ×2 always reaches a numbers divisible by 2 so m when followed by collatz rules reach 2^k which ÷2 k times is 1


ALGEBRAIC NOTATION OF 2^k AND RELATION IN VARIABLES OF  n/2

2^k can be expressed as a rational number 2^k/1 and expansion of 2^k is 2×2...×2(x times ) 2^1 2^2 2^3 ... 2^k so expansion of 2^k is 2^1 ,2^2,2^3,...,2^k and n/2 is n÷2=Q and n division is n=divisor(x)×quotient(x)+remainder(x) or n=D(x)×Q(x)+R(x) where D is always 2 so n=2×Q(y)+R(z) so they have a coefficient relation 2 that tells us 2^k÷2=even and n/2= eventually 2^k . The odd numbers after 3n+1 even than n/2 becomes odd or even mostly odd so after some steps the odd number always is half of the new even number generated from 3n+1

Σn∈ℕ=∞  this shows that this works for all natural numbers till infinity 1 to ∞

−−−−−−−−−−−−−−−−−−−−−−−−−−−−−−−−−

This logic works ∀ n in n∈ℕ or +ℤ or {1 , 2 , 3 , 4 , 5 ,... , ∞} or it works for ∑ℕ₁ or ℕ₁∩+ℤ we can also say that all n in collatz reach 1 by following collatz rules and also not only because that n÷2 and 2^k have a coefficient relation but also ÷2 means factor of that n which ×2 is n so we can say in (n÷2)=new n where new n=(n÷2)×2 and 2^k is 2^(k) (f) or simply 2×2...×2 they have ×2 in common so each will reach another if followed by an operation so ÷2 will lead to 2^k.

----------‐---------------------------------------------------------

CONCLUSION

Thus this paper proves the Collatz conjecture by proving that all n reach 2^k by ÷2  because of their coefficient relation and that no cycles or loops exist because of Contradiction and that the procedure doesn't go to infinity . This paper proves the collatz by 2^k , mods , logs , Contradiction,  Induction and more .

ORIGINALITY STATEMENT

I tanay gudadhe confirm this title TANAYS COLLATZ THEORY is my own original work . The ideas , equations , symbols , logic and proofs are all my work .

This statement is originally the work of Tanay gudadhe on April 2025 theory created and development since than all math symbols equations and logic are mine only formatting has been done by ai (chatgpt)


PEER REVIEW STATEMENT 

This paper suggests a proof for the collatz conjecture and it is open for peer review . Thank you for your time .



 
