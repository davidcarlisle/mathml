# Math Accessibility Explainer

## Authors
 * Sam Dooley
 * Neil Soiffer

## Abstract
[MathML 3](https://www.w3.org/TR/MathML3/) is a W3C recommendation for including mathematical expressions in Web pages. MathML has two parts: presentation MathML that describes how the math looks and content MathML that describes the meaning of the math. Presentation is by far the most commonly used part of MathML and is the focus of this document. Assuming they know the subject matter, a person reading math notation typically can understand its meaning. Although it is occasionally ambiguous, context resolves the ambiguity. One goal of MathML 4 is to allow authors provide context as part of the MathML to resolve the ambiguity.

Math accessibility has significant differences from text accessibility because math notation is a shorthand for its meaning. The words spoken for it differ from the braille that would be used for it. Furthermore, the words that are spoken need to differ based on the reader’s disabilities and familiarity of the content. Hence, enough information from MathML should be given to the assistive technology of a user so that it can generate a meaningful presentation of the math to the user. 

## Table of Contents

## Math Accessibility Background
The following are reasons why math accessibility is different from text accessibility. Details are in the next section:

* Mathematical expressions encode concepts, not words. The same concept can be spoken in many different ways. With the exception of abbreviations and a few words (e.g, “read”), words are always read the same.

* The words that should be used need to be tailored to the disability. For people who cannot see the mathematical expression, the 2D structure of math needs to be disambiguated. This can be done with words, sounds, or prosody changes (e.g., pitch or rate). For those who can see the math, such unfamiliar sounds or words make understanding more difficult.  
* Most braille systems encode the syntax of math, not the words used to speak to speak math.
* The notations and tokens taken together determine how the math is spoken. For example, the ‘4’ in <img src="/docs/tex/4199db0b0356e8ace7a77ef6b7477bab.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=26.76175259999998pt/> might be spoken as a cardinal number (“x to the fourth power”) but the ‘2’ in <img src="/docs/tex/6177db6fc70d94fdb9dbe1907695fce6.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=26.76175259999998pt/> is spoken as “squared” (“x squared”).
* Depending on context, the same notation may have different meanings. For example, “(1, 5)” could be a point in the plane or it could be the numbers from 1 to 5, exclusive of 1 and 5. Although it could be spoken syntactically (“open paren 1 comma 2 close paren”), people don’t typically say those words when speaking it. Instead they speak the meaning and listeners tend to prefer to hear math spoken by AT the way a teacher or other people typically say it.
* As one becomes more experienced with a notation, the words used to speak the notation might change. Examples are given below.


## Goals

## Non-Goals


## Background: MathML

### Presentation MathML
Brief explanation of presentation MathML.
Show an example.


### Content MathML
Brief explanation of content MathML and parallel markup.
Show an example.

Not used much.


### Examples of speech
<img src="/docs/tex/ef4740140c8741b5abffcf442f79c1c7.svg?invert_in_darkmode&sanitize=true" align=middle width=17.521011749999992pt height=21.839370299999988pt/>, special cases for <img src="/docs/tex/6177db6fc70d94fdb9dbe1907695fce6.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=26.76175259999998pt/> and <img src="/docs/tex/3c63d4517a41fc372162eaa29bc7d970.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=26.76175259999998pt/> are common

<img src="/docs/tex/863019f4cc45632fc74617cee3eff54f.svg?invert_in_darkmode&sanitize=true" align=middle width=50.279027699999986pt height=26.76175259999998pt/> -- also usually specially cased

<img src="/docs/tex/47d54de4e337a06266c0e1d22c9b417b.svg?invert_in_darkmode&sanitize=true" align=middle width=6.552545999999997pt height=27.77565449999998pt/> -- special cased?

<img src="/docs/tex/a9e181dc572cb3ed023e845d7844e89e.svg?invert_in_darkmode&sanitize=true" align=middle width=19.657639649999997pt height=27.77565449999998pt/>

### Examples of ambiguity
<img src="/docs/tex/117d5fafc41a6d9edd6fdbfec19eb2a7.svg?invert_in_darkmode&sanitize=true" align=middle width=36.52973609999999pt height=24.65753399999998pt/>

<img src="/docs/tex/aa6187664247ff6929af116a80a61803.svg?invert_in_darkmode&sanitize=true" align=middle width=27.27343409999999pt height=27.6567522pt/>

<img src="/docs/tex/8afda0bcf2f9f7e7008eadbe487e90f6.svg?invert_in_darkmode&sanitize=true" align=middle width=23.194596149999988pt height=27.94539330000001pt/> also as 2x1 matrix


## Ideas