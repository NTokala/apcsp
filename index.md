---
title: 
---

Read this <span style="color: blue">5 months</span>, <span style="color: green">5 weeks</span>, <span style="color: #ffb626">5 days</span>, and <span style="color: red">5 minutes</span> before the exam :sweat_smile:

Take a look at the [official reference sheet.](https://github.com/NTokala/apcsp/blob/master/ReferenceSheet.pdf)
Make sure you are comfortable with the programming terminology presented. If anything on that sheet confuses you, **don't panic!**{: style="color: red"} I will cover every single symbol on that sheet in this guide. 

**Binary** representations can take on two possible values. A **bit**, or binary digit, is the fundamental unit of information for a computer, represented by a $$ \text{0} $$ or $$ \text{1} $$. A **byte** is a group of 8 bits.

| Kilobyte (KB) | ≈ 1000 bytes |
| Megabyte (MB) | ≈ 1000 kilobytes |
| Gigabyte (GB) | ≈ 1000 megabytes |
| Terabyte (TB) | ≈ 1000 gigabytes |
| Petabyte (PB) | ≈ 1000 terabytes |
| Exabyte (EB) | ≈ 1000 petabytes |

Binary is a system of counting. A **counting system** is defined by how many unique digits are available in that system, or the <span style="color: blue">base</span> of the system. To indicate the base of a number, write the base as a subscript e.g. $$209_{10}$$.

| System | Base | Digits | Example
| --- | --- | --- | --- |
| Binary | $$2$$ | $$ 0,1 $$ |$$ 10010_{2} $$ |
| Decimal | $$10$$ | $$ 0,1,2,3,4,5,6,7,8,9 $$ | $$ 279_{10} $$ |
| Hexadecimal | $$16$$ | $$ 0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F$$ | $$4DF_{16}$$ |

You learned in elementary school that a number has a <span style="color: green">ones</span> place, a <span style="color: red">tens</span> place, a <span style="color: blue">hundreds</span> place, and so on.
We could say that <span style="color: blue">$$2$$</span><span style="color: red">$$7$$</span><span style="color: green">$$9$$</span>$$_{10}$$ consists of $$2$$ <span style="color: blue">hundreds</span>, $$7$$ <span style="color: red">tens</span>, and $$9$$ <span style="color: green">ones</span>. Mathematically, we write this as <span style="color: blue">$$2$$</span><span style="color: red">$$7$$</span><span style="color: green">$$9$$</span> $$=$$ <span style="color: blue">$$2$$</span> $$\times $$ <span style="color: orange">$$10^{2}$$</span> $$+$$ <span style="color: red">$$7$$</span> $$\times$$ <span style="color: orange">$$10^{1}$$ </span> $$+$$ <span style="color: green">$$9$$</span> $$\times$$ <span style="color: orange">$$10^{0}$$</span>. Notice that the <span style="color: orange">orange</span> numbers are powers of $$10$$; we can write numbers of **any** base in this form, where the $$10$$ is replaced with the base of the number. 

**In general, the number** $$A_{1}A_{2}A_{3}\text{...}A_{N_B} = A_{1}\times B^{N-1} + A_{2}\times B^{N-2} + \text{...} + A_{N-1}\times B^{1} + A_{N}\times B^{0}$$, where $$A_{1}, A_{2},\text{...} A_{N}$$ are digits and $$B$$ is the base of the number. 

<span style="color: orange">$$B$$</span>$$^{N}$$ represents the amount of *unique values a number base with a maximum of $$N$$ digits can represent*. For example, a binary number with 5 digits can represent $$2^{5} = 32$$ values (from $$00000_{2}$$ to $$11111_{2}$$.) 

<span style="color: orange"> </span>




`Kramdown::Document.new(text).to_html`
