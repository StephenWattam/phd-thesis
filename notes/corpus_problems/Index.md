Corpus Problems
===============
This is a transcription of the a£ sheet of notes, designed as an intermediate format before writing into the thesis.

It's organised in blocks of various smaller issues, each of which might become its own document eventually.


Covariates + Population Specification
-------------------------------------
This category largely describes the faulty manner in which certain important covariates are selected for sampling, or sampled.  Though language contains an unknown and very large number of possible dimensions of variation for study, many of them are judged to be of particular importance in describing variation across texts (see Atkins, Clear+ Ostler list).

Taking Atkins, et al's recommendations for covariate selection, as well as personal judgement, I have derived the following...



### Poor definition of population
See [this](http://www.natcorp.ox.ac.uk/docs/URG/)
The population for whom a corpus describes language use is relatively difficult to describe, as it is largely a self-referential problem.  Though efforts are often made in speech corpora to balance content according to populations of language speakers, the same cannot be said for written samples, which are often selected from various indexes.

The utility of linguistics, and linguistic studies using corpus methods, is in their capacity to infer truths about a given population.  Any well constructed sample should adequately represent each member of this population, and hence any study based upon the data is necessarily limited by the scope of this sample.  Though there is doubtless great value in imperfect samples, much of that value is extracted by reasoning qualitatively about a 'typical' user who *is* properly represented.  Poor definition of the population in terms used within analyses renders this reasoning unreliable.

Seemingly, one reason why corpora are not specifically targeted is because their selection processes rely on lists that are compiled using data for which it is difficult to determine comparable bounds.  The BNC's policy for selecting written materials, for example, is segmented into the following sources:

 * Books, selected from Bestsellers, Literary Prices, Library Loans, Additional texts;
 * Periodicals and Magazines (including newspapers);
 * Other media (essays, speeches, letters, internal memoranda).

Of the lists used in the Books category, they specify the following criteria:

> "Each text randomly chosen was accepted only if it fulfilled certain criteria: it had to be published by a British publisher, contain sufficient pages of text to make its incorporation worthwhile, consist mainly of written text, fall within the designated time limits, and cost less than a set price."

It is often difficult, using other sources of data, to establish the details of an author's nationality(or, as described in 'Oh Canada! Towards the Corpus of Early Ontario English', what the notion of being 'british' means), the age of a text, or the suitability of the time limits.  (Indeed, it seems likely that these bounds are likely to vary according to which type of text is sampled, but this is a relatively minor issue which would complicate use of the corpus).

These issues are typically better addressed by more specialist corpora, which are subject to easier-to-determine bounds such as social role, context or text type.  Examples of this include...

> TODO (canadaian one above has good definitions, also check helsinki, find some more)!

Note that the problem of specifying a population is quite apart from that of determining what proportion of each stratum should be included in a corpus.  The relative proportions of each of the above categories (as well as the problem of selecting proportionally from each list) are a problem of the validity of the inference made from a corpus, that is the internal consistency.  Use of a corpus to evidence truths about a given population, where this is either unknown or different, leads to internally consistent, but externally irrelevant, scientific contribution.

Ambiguity in population definition has a number of direct influences on other issues of corpus validity.  Selection of stratum sizes, for example, must be based on the relative proportions of language used by the given population.  If a population is defined using purely internal (linguistic) properties, this becomes a purely reflexive and meaningless task---we end up selecting proportions of language to match proportions seen in language.  Use of auxiliary data to augment sampling policies (such as social demographics taken from other, large-scale surveys) must also be matched to the population in question.

%-- 

Speech corpora are often specified in a significantly less ambiguous manner (though not always with more proportional sampling).  I conjecture this is due to the direct nature of speech sampling, which involves the person actually performing an utterance (rather than the language use itself being a persistent and concrete artefact).  Essentially, this is nothing more than a paradigm shift: there is functionally no difference in sampling a work that is synchronously "performed" and received to one asynchronously.

This difference is identified in Leech (new language resources or just better old ones), and will be inspected in greater detail below [section about production/consumption]









### Time effects and distribution 
Largely affects replicability + representativeness.  Temporal effects are hard to control for when sampling so long after text is produced. 
Many corpora are defined loosely in terms of their temporal distribution---indeed, the idea of sampling a cross-section of modern language is one of the key reasons for using a corpus over other methods.  The Brown and LOB corpora, for example, sampled texts produced in 1961 only.

Though the concept of sampling texts in a single time frame makes perfect sense when sampling language *production* only, many corpora (including, explicitly, Brown and the BNC...), aim to trade-off both production and reception of texts in order to balance the zipfian popularity of many kinds of text.  For example, the vast majority of published works are seldom read, yet certain books might be read millions of times.

The differences between distribution of production and consumption of texts leads to an interesting question: *For a given population, how old are texts used on a day-to-day basis?*

This question, with its direct relation to the original ideals of corpus sampling, seems largely unaddressed in the literature.  Some efforts have been made to incorporate linguistic change over time into corpus design, however, these do so in an abstract manner and under the assumption that synchronic sampling is fundamentally valid in order to represent language use (use here refers to the proportional mix of production and consumption).

TODO: mention various efforts to specify this, if I can find any.  Talk more about monitor copora and specifically historical/diachronic corpora.






### Failure to define categories 
w.r.t. 1) external covariates, 2) language features [not statistically rigorous]
This problem is actually fairly minor, as it was well-identified in the 90's, and has had much effort spent on its minimisation.  However, issues remain when constructing new corpora regarding quite how to segment a corpus along lines of minimum entropy (in useful dimensions).

This occurs in two ways.  The former of these is the problem of selecting texts according to external, non-textual, variables about which we may wish to infer findings, such as level of education of the author, nationality, target audience of text, etc.  This is perhaps the least agreed-upon, partially because of the focus on sampling using existing lists as proxies for proper demographic specification.

The latter of these is selection and stratification according to external, but textual features such as genre, text type, medium, etc.  These are fairly well agreed upon and specified in a fair amount of detail in efforts such as EAGLES and Atkins, et al.  

TODO: MORE!







Practical Issues
----------------

### Copyright
Copyright is one major problem with sampling large volumes of text from any source, especially those already available for-profit from large publishers (who are acutely aware their entire business model is based on their intellectual property).

This is stated in the original Brown documentation as one reason for their choice of sampling unit, (though, as discussed in that section, this solves many other issues too), and often causes "black spots" in the sampling frame of a corpus, where certain publishers are known for their absolute declination in offering material.

TODO: find some nice examples of people on-the-record.  The birmingham corpus building paper somewhere on my desk might have some, IIRC.

### Lack of a central index
The lack of a central index for a given set of documents makes tru random selection within strata difficult.  Any indexes that do exist are highly heterogenous in purpose, form and extent.  Digital indexes are skewed by corporate forces and are arguably even more partial.  Many indexes conflate the concepts of production and consumption.


### Time taken to gather data
Gathering data from physical resources is expensive.


### Privacy and context (+ethics)

### Cultural taboo (ethics)

### Ephemera and lack of record-keeping


Stratum Selection [external validity?]
--------------------------------------

### Most covariates not considered, or considered in a haphazard manner

### Non-mutually-exclusive categories used

### lack of variability/saturation analysis/multi-phase

### Incomplete coverage of population 
(definitely external validity)

### Insufficient consideration of external demographic information

### No minimum sizes of categories, or analysis thereof.




Randomness [internal validity?]
-------------------------------

### Most covariates not considered (see stratum selection)

### Lack of variance/saturation analysis (see stratum selection)

### Oversampling of easy but homogenous groups 
(i.e. book lists)

### Nonrandom sampling of stuff 
(i.e. web crawls)

### Incomplete coverage within each stratum [use of proxy vars]


Size
----

### No overall size established 
(w.r.t strata, and randomness above)

### No methods for saturation/internal measures

### No multi-phase/IWP design


Sampling Unit
-------------

### Too large sampling unit damages corpus coverage
i.e. for a given corpus size in words, the size in units may be too small.

### Conventionalised to a weird/large number 
(2k) (Biber)

### Heterogenous between corpora 
(see comparison)

### "clumpiness" of language is not considered

### Not formally specified or justified using semantic models


Comparability
-------------

### Sampling unit

### Poor documentation of intent, sampling policy, population bounds

