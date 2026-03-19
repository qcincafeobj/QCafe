See the first 03 lines of t.cafe

```
    -- input ../qc.cafe .
    input ../qc-no-redundancy-old.cafe .
    -- input ../qc1.0.11.cafe .
```

to know why fixing lemmas in the meeting
can make t.cafe run perfectly
while g.cafe can't

The fixed file is the file that was not input

That mistake is now corrected, which shows that
ceq bkzero * KET1 + KET2 = KET2 if (bkzero * KET1 ==== KET2) .
can't be removed in this specification as it was in the meeting

Basically, the other lemmas are fine,
except the twos

```
    eq ((BK x BB) * M) x (BK1 * KET) = ((BK x BB) x BK1) * (M x KET) .
    eq I x KET = KET .
```

needs 01 more lemma which is 

```
    eq ((BK x BB) * I) x BK1 = (BK x BB) x BK1 .
```

An idea to remove ==== (equality of number of qubit):

```
    eq bkzero * KET1 + KET2 = KET2 .
    O(K) * BK * KET = O(K + 1) * KET .
```