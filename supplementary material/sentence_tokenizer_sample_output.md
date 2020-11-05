## Comparison Between LAWSUM Sentence Tokenizer and NLTK Sentence Tokenizer

<b>Note:</b> LawSum tokenizer uses NLTK as base tokenizer, but includes additional pre-processing and post-processing steps for improving the tokenization.

--------------------------

### ORIGINAL TEXT

It was observed by Lord Atkin in Eshugbayi Eleko vs Officer Administering the Government of Nigeria C), that in accordance with British Jurispru dence no member of the executive can interfere with the liberty or property of a British subject except when he can support the legality of his act before a Court of justice.   <b>(1) [1924] 2 Irish Reports K. B.  104.  (2) [1931] A. C.   (62 at 670.   114 In The King vs The Secretary of State for Home Affairs(1), Scrutton LJ.  observed: "A man undoubtedly guilty of murder must yet be released if due forms of law have not been followed in his conviction. "</b> It seems very arguable that in the whole set-up of Part III of our Constitution these principles only remain guaranteed by article 21.

### LAWSUM

'It was observed by Lord Atkin in Eshugbayi Eleko vs Officer Administering the Government of Nigeria C), that in accordance with British Jurispru dence no member of the executive can interfere with the liberty or property of a British subject except when he can support the legality of his act before a Court of justice.', \
'(1) [1924] 2 Irish Reports K.  B. 104. (2) [1931] A.  C.   (62 at 670. 114 In The King vs The Secretary of State for Home Affairs(1), Scrutton LJ. observed: "A man undoubtedly guilty of murder must yet be released if due forms of law have not been followed in his conviction.  "', \
'It seems very arguable that in the whole set-up of Part III of our Constitution these principles only remain guaranteed by article 21.',

### NLTK

'It was observed by Lord Atkin in Eshugbayi Eleko vs Officer Administering the Government of Nigeria C), that in accordance with British Jurispru dence no member of the executive can interfere with the liberty or property of a British subject except when he can support the legality of his act before a Court of justice.', \
'(1) [1924] 2 Irish Reports K. B.', \
'104.', \
'(2) [1931] A. C.   (62 at 670.', \
'114 In The King vs The Secretary of State for Home Affairs(1), Scrutton LJ.', \
'observed: "A man undoubtedly guilty of murder must yet be released if due forms of law have not been followed in his conviction. "', \
'It seems very arguable that in the whole set-up of Part III of our Constitution these principles only remain guaranteed by article 21.' 

---------------------------

### ORIGINAL TEXT

One may like that right to cover a larger area, but to give such a right is not the function of the Court; it is the function of the Constitution.  <b>To read the word "law" as meaning rules of natural justice will land one in (1) (1895)L. R.  221.  A.  107.  15 15 112 difficulties because the rules of natural justice, as re gards procedure, are nowhere defined and in my opinion the Constitution cannot be read as laying down a vague standard.</b>   This is particularly so when in omitting to adopt "due process of law" it was considered that the expression "procedure established by law" made the standard specific.

### LAWSUM

'One may like that right to cover a larger area, but to give such a right is not the function of the Court; it is the function of the Constitution.', \
'To read the word "law" as meaning rules of natural justice will land one in (1) (1895)L.  R.  221. A. 107. 15 15 112 difficulties because the rules of natural justice, as re gards procedure, are nowhere defined and in my opinion the Constitution cannot be read as laying down a vague standard.', \
'This is particularly so when in omitting to adopt "due process of law" it was considered that the expression "procedure established by law" made the standard specific.'

### NLTK

'One may like that right to cover a larger area, but to give such a right is not the function of the Court; it is the function of the Constitution.', \
'To read the word "law" as meaning rules of natural justice will land one in (1) (1895)L. R.  221.', \
'A.', \
'107.', \
'15 15 112 difficulties because the rules of natural justice, as re gards procedure, are nowhere defined and in my opinion the Constitution cannot be read as laying down a vague standard.', \
'This is particularly so when in omitting to adopt "due process of law" it was considered that the expression "procedure established by law" made the standard specific.' \

--------------------------

### ORIGINAL TEXT

Similarly, it was urged that the words "territory of India" in article 19 (1) (d) may be treated as superfluous, and preventive detention would thus be an abridgement of the right to move freely.  In my opin ion, this rule of construction itself is faulty.  <b>Because certain words may be considered superfluous (assuming them to be.  so in article 14 for the present discussion) it is quite improper to assume that they are superfluous wherever found in the rest of the Constitution.</b>  On the contrary, in my opinion, reading sub-clause (d) as a whole the words "territory of India" are very important.

### LAWSUM

'Similarly, it was urged that the words "territory of India" in article 19 (1) (d) may be treated as superfluous, and preventive detention would thus be an abridgement of the right to move freely.', \
'In my opin ion, this rule of construction itself is faulty.', \
'Because certain words may be considered superfluous (assuming them to be. so in article 14 for the present discussion) it is quite improper to assume that they are superfluous wherever found in the rest of the Constitution.' \

### NLTK

'Similarly, it was urged that the words "territory of India" in article 19 (1) (d) may be treated as superfluous, and preventive detention would thus be an abridgement of the right to move freely.', \
'In my opin ion, this rule of construction itself is faulty.', \
'Because certain words may be considered superfluous (assuming them to be.', \
'so in article 14 for the present discussion) it is quite improper to assume that they are superfluous wherever found in the rest of the Constitution.'


---------------------------

### ORIGINAL TEXT

I may point out that the acceptance of the petitioner\'s argument on the interpretation of this clause will result in the Court being called upon to decide upon the reasonableness of several provisions of the Indian Penal Code and several other penal legislations as abridging this right.  <b>Even under clause (5), the Court is permitted to apply the test of reasonable ness of the restrictions or limits not generally, but only to the extent they are either in the interests of the gener al public, e. g. , in case of an epidemic, riot, etc. , or for the protection of the interests of any Scheduled Tribe.</b>  In my opinion, this is not the intention of the Constitution.

### LAWSUM

'"I may point out that the acceptance of the petitioner's argument on the interpretation of this clause will result in the Court being called upon to decide upon the reasonableness of several provisions of the Indian Penal Code and several other penal legislations as abridging this right.", \
'Even under clause (5), the Court is permitted to apply the test of reasonable ness of the restrictions or limits not generally, but only to the extent they are either in the interests of the gener al public, e.  g.  , in case of an epidemic, riot, etc. , or for the protection of the interests of any Scheduled Tribe.', \
'In my opinion, this is not the intention of the Constitution.'

### NLTK

'"I may point out that the acceptance of the petitioner's argument on the interpretation of this clause will result in the Court being called upon to decide upon the reasonableness of several provisions of the Indian Penal Code and several other penal legislations as abridging this right.", \
'Even under clause (5), the Court is permitted to apply the test of reasonable ness of the restrictions or limits not generally, but only to the extent they are either in the interests of the gener al public, e. g. , in case of an epidemic, riot, etc.', \
', or for the protection of the interests of any Scheduled Tribe.', \
'In my opinion, this is not the intention of the Constitution.',

--------------------------
