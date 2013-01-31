corpus problems
===============
<span style="color: red;">
*NB:* This has now been inserted into the thesis and will not be updated further here. [31-01-13, 18:13]
</span>
<hr/>

this is a transcription of the a£ sheet of notes, designed as an intermediate format before writing into the thesis.

it's organised in blocks of various smaller issues, each of which might become its own document eventually.

not listed here are cognitive biases.  it's worth noting that one of the main advantages of statistical and quantitative methods are their objective properties: humans are exceptionally poorly suited to reasoning about large numbers, and our ability to digest them mathematically into smaller quantities of information is crucial.  this is embodied in my original working defintion of a corpus, that it is not meant to be read by a human.  

todo: perhaps a section listing common cognititive biases, read and evaluate the paper [here](http://link.springer.com/article/10.1007/s10822-011-9530-1) for an approach.


covariates + population specification
-------------------------------------
this category largely describes the faulty manner in which certain important covariates are selected for sampling, or sampled.  though language contains an unknown and very large number of possible dimensions of variation for study, many of them are judged to be of particular importance in describing variation across texts (see atkins, clear+ ostler list).

taking atkins, et al's recommendations for covariate selection, as well as personal judgement, i have derived the following...



### poor definition of population
see [this](http://www.natcorp.ox.ac.uk/docs/urg/)
the population for whom a corpus describes language use is relatively difficult to describe, as it is largely a self-referential problem.  though efforts are often made in speech corpora to balance content according to populations of language speakers, the same cannot be said for written samples, which are often selected from various indexes.

the utility of linguistics, and linguistic studies using corpus methods, is in their capacity to infer truths about a given population.  any well constructed sample should adequately represent each member of this population, and hence any study based upon the data is necessarily limited by the scope of this sample.  though there is doubtless great value in imperfect samples, much of that value is extracted by reasoning qualitatively about a 'typical' user who *is* properly represented.  poor definition of the population in terms used within analyses renders this reasoning unreliable.

seemingly, one reason why corpora are not specifically targeted is because their selection processes rely on lists that are compiled using data for which it is difficult to determine comparable bounds.  the bnc's policy for selecting written materials, for example, is segmented into the following sources:

 * books, selected from bestsellers, literary prices, library loans, additional texts;
 * periodicals and magazines (including newspapers);
 * other media (essays, speeches, letters, internal memoranda).

of the lists used in the books category, they specify the following criteria:

> "each text randomly chosen was accepted only if it fulfilled certain criteria: it had to be published by a british publisher, contain sufficient pages of text to make its incorporation worthwhile, consist mainly of written text, fall within the designated time limits, and cost less than a set price."

it is often difficult, using other sources of data, to establish the details of an author's nationality(or, as described in 'oh canada! towards the corpus of early ontario english', what the notion of being 'british' means), the age of a text, or the suitability of the time limits.  (indeed, it seems likely that these bounds are likely to vary according to which type of text is sampled, but this is a relatively minor issue which would complicate use of the corpus).

these issues are typically better addressed by more specialist corpora, which are subject to easier-to-determine bounds such as social role, context or text type.  examples of this include...

> todo (canadaian one above has good definitions, also check helsinki, find some more)!

note that the problem of specifying a population is quite apart from that of determining what proportion of each stratum should be included in a corpus.  the relative proportions of each of the above categories (as well as the problem of selecting proportionally from each list) are a problem of the validity of the inference made from a corpus, that is the internal consistency.  use of a corpus to evidence truths about a given population, where this is either unknown or different, leads to internally consistent, but externally irrelevant, scientific contribution.

ambiguity in population definition has a number of direct influences on other issues of corpus validity.  selection of stratum sizes, for example, must be based on the relative proportions of language used by the given population.  if a population is defined using purely internal (linguistic) properties, this becomes a purely reflexive and meaningless task---we end up selecting proportions of language to match proportions seen in language.  use of auxiliary data to augment sampling policies (such as social demographics taken from other, large-scale surveys) must also be matched to the population in question.

%-- 

speech corpora are often specified in a significantly less ambiguous manner (though not always with more proportional sampling).  i conjecture this is due to the direct nature of speech sampling, which involves the person actually performing an utterance (rather than the language use itself being a persistent and concrete artefact).  essentially, this is nothing more than a paradigm shift: there is functionally no difference in sampling a work that is synchronously "performed" and received to one asynchronously.

this difference is identified in leech (new language resources or just better old ones), and will be inspected in greater detail below [section about production/consumption]









### time effects and distribution 
largely affects replicability + representativeness.  temporal effects are hard to control for when sampling so long after text is produced. 
many corpora are defined loosely in terms of their temporal distribution---indeed, the idea of sampling a cross-section of modern language is one of the key reasons for using a corpus over other methods.  the brown and lob corpora, for example, sampled texts produced in 1961 only.

though the concept of sampling texts in a single time frame makes perfect sense when sampling language *production* only, many corpora (including, explicitly, brown and the bnc...), aim to trade-off both production and reception of texts in order to balance the zipfian popularity of many kinds of text.  for example, the vast majority of published works are seldom read, yet certain books might be read millions of times.

the differences between distribution of production and consumption of texts leads to an interesting question: *for a given population, how old are texts used on a day-to-day basis?*

this question, with its direct relation to the original ideals of corpus sampling, seems largely unaddressed in the literature.  some efforts have been made to incorporate linguistic change over time into corpus design, however, these do so in an abstract manner and under the assumption that synchronic sampling is fundamentally valid in order to represent language use (use here refers to the proportional mix of production and consumption).

todo: mention various efforts to specify this, if i can find any.  talk more about monitor copora and specifically historical/diachronic corpora.






### failure to define categories 
w.r.t. 1) external covariates, 2) language features [not statistically rigorous]
this problem is actually fairly minor, as it was well-identified in the 90's, and has had much effort spent on its minimisation.  however, issues remain when constructing new corpora regarding quite how to segment a corpus along lines of minimum entropy (in useful dimensions).

this occurs in two ways.  the former of these is the problem of selecting texts according to external, non-textual, variables about which we may wish to infer findings, such as level of education of the author, nationality, target audience of text, etc.  this is perhaps the least agreed-upon, partially because of the focus on sampling using existing lists as proxies for proper demographic specification.

the latter of these is selection and stratification according to external, but textual features such as genre, text type, medium, etc.  these are fairly well agreed upon and specified in a fair amount of detail in efforts such as eagles and atkins, et al.  

todo: more!







practical issues
----------------

### copyright
copyright is one major problem with sampling large volumes of text from any source, especially those already available for-profit from large publishers (who are acutely aware their entire business model is based on their intellectual property).

this is stated in the original brown documentation as one reason for their choice of sampling unit, (though, as discussed in that section, this solves many other issues too), and often causes "black spots" in the sampling frame of a corpus, where certain publishers are known for their absolute declination in offering material.

todo: find some nice examples of people on-the-record.  the birmingham corpus building paper somewhere on my desk might have some, iirc.

### lack of a central index
the lack of a central index for a given set of documents makes tru random selection within strata difficult.  any indexes that do exist are highly heterogenous in purpose, form and extent.  digital indexes are skewed by corporate forces and are arguably even more partial.  many indexes conflate the concepts of production and consumption.


### time taken to gather data
gathering data from physical resources is expensive and difficult.  

paper documents must be scanned, ocred, manually corrected and converted into a normal form.  speech must be gathered in an ethically defensible manner, and metadata about the speakers must be gathered.  electronic documents require significant format conversion.

beyond these first efforts, any metadata and annotation must be added for the final form to be useful.

digitisation technology, especially that used for paper documents, has recently progressed significantly due to efforts to preserve historical documents, and libraries' attempts to digitise older publications.  in some cases, scanners are capable of scanning entire books without intervention.




### privacy and context (+ethics)
for speech data, and written data that is not intended for public dissemination, issues of privacy must be considered.



### cultural taboo (ethics)
some topics and contexts that ought to be represented are difficult to sample due to the cultural taboo surrounding them.  this is especially relevant for speech corpora, since speech is often used for informal transactions.


### ephemera and lack of record-keeping
many documents encountered in everyday life are designed to be discarded.  this means that many are difficult to obtain.  also, the presumption that out-of-date ephemera are difficult to obtain forms a significant part of the privacy people take for granted, raising further ethical concerns (indeed, this concept is inshrined in law in germany, who have 'the right to be forgotten').


stratum selection [external validity?]
--------------------------------------

### most covariates not considered, or considered in a haphazard manner
though it is clearly impossible to stratify a sample according to all of its main covariates (especially in the case of language, where this set is both large and unknown), the selection of covariates upon which to stratify a selection is somewhat haphazard and seldom justified in terms of the research value of the corpus.

in some cases, one part of a corpus is stratified one way (books, for example from index lists), with another part (typically speech, sampled demographically) being stratified another.  this must clearly lead us to cast suspicion on the validity of any comparisons between these parts (and the relevance of subsamples from each to the original corpus documentation's statement of representativeness and purpose).

### non-mutually-exclusive categories used
though a problem for categorisation and taxonomy selection, the 'fuzzy edges' of genre, medium, popularity and other covariates often leads to ambiguity surrounding which stratum a text should be sampled within.

though this will always persist in some form, a reasonable solution is to precisely specify objective conditions for selection.  these may then be inspected by a researcher in order to assess the value of the sample to their particular questions.


### lack of variability/saturation analysis/multi-phase
biber, and subsequently many others [who!] recommend that sampling should occur in an iterative process, with the contents of a corpus being used as evidence to weight selection of strata from the next version.

as varadi (2001) notes, this simply doesn't happen.  indeed, the simpler option of using a previous corpus to guide one's stratum selection is also ignored.  reasons for this may include the structure of funding and scientific work, or the time required to re-code and align a previous corpus' annotation structure to that which is to be built.  

having acquired a first iteration of a corpus, there are many methods for assessing the 'completeness' of a sample.  some of these are explored by biber, and others (including evert, greis) go on to describe further internal measures (such as frequency of hapax legomenon).

note that this is quite aside from the problem of assessing corpus proportions using external variables, which is easier to inform using other studies in a multi-phase fasion, and subject to less bias in terms of errors in the original (1st iteration) sample.


### incomplete coverage of population 
(definitely external validity)
an issue of external validity, and distinct from the problem of specifying a population.  having specified a population, there is often little connection between this stated group and the content that is actually sampled.

this is mainly a problem of ensuring that the strata selected, in whatever proportions, cover all language use in the given population.  this is distinct from the quality of each stratum, or the relevance of its weighting, and is a problem of omission: the opinions of a group of middle-class researchers (though skilled) are unlikely to fully cover language use of highly disparate social groups.

i would posit that auxiliary data from social surveys may be used as a rough indicator for this, though in reality no data source exists that can describe, in social terms, the 'types' of language used (w.r.t. the primary dimensions of sampling for corpora).  questionnaires, ethnography, and/or direct sampling may be the only ways to establish a ground truth for this, but for now it remains an open research question [until the personal corpus section ;-)]





### insufficient consideration of external demographic information
this is a problem of weighting strata to fit the population.  

in the case of speech data, there is often some attention given to the deompographics of the ext producers.  in the case of written data, the popularity of items on an index is often taken as a proxy for this.  

check: brown and lob, iirc, 'balance' their demographics by choosing equal proportions of some major variables, which is not really balancing.  the bnc may also do this.  there is simply unknown balance for the books, and it's worth noting that different people buy books vs. go to libraries, making the populations for each quite hard to compare scientifically.



### no minimum sizes of categories, or analysis thereof.
this problem can be seen two ways, depending on the sampling policy.  in an ideal world, strata are entirely proportional, and the problem of identifying the minimum size is one of ensuring that all variability within the smallest stratum is adequately represented.  in practice, one of the reasons for stratified sampling is to, with philosophical rather than mathematical justification, boost the prevalence of a stratum by artificially oversampling it.

both approaches are correct from their respective viewpoint, but neither are done.  algorithms for internal saturation/sufficient sample size may be used for both the formar and latter, though it's worth noting that the sample is less random if used in the latter way.  the highly zipfian distribution of language will, for most practical purpose, necessitate the use of inflated stratum sizes for small strata.



randomness [internal validity?]
-------------------------------

### most covariates not considered (see stratum selection)
see 'insufficient consideration of external demographic information' for a specific case of this.  

one of the key reasons for using stratification is that it allows one to correct for the biases implicit in sampling technique which may be caused by difficult-to-predict practical concerns such as patterns of behaviour through time (a classic example being the disproportionate sampling of women through going door-to-door during working hours).  ignoring a multitude of covariates relinquishes them from this control, meaning that we should generally stratify according to any we believe to be particularly crucial to corpus integrity and purpose.

whereas some covariates, such as genre, date of authorship, etc, are well considered in the design of corpora, many are selected in accordance with availability or legality.  this is one cause of the large disparity between spoken and written corpora in most general-purpose offerings (for example, the bnc is just [n%] spoken).  if we were to control for this proportion, analyses relating this to other important variables would be possible.

practically speaking, the importance of variables to the 'balance' of a corpus may be seen as zipfian: a few key features, such as genre or formality, are going to heavily influence content and vary widely across the population in ways we wish to investigate, whereas most variables are going to exert only a small influence on the resultant selection of linguistic data.  much of this decision must be made in a qualitative manner, and there will always be a small population of variables we *should* have sampled for a given study.  this problem is one of degree.



### oversampling of easy but homogenous groups 
(i.e. book lists)
the pragmatic issues surrounding corpora do not apply equally to all genres, media, social demographics, or settings.  interactions between the key variables of interest and the sampling method cause gross over-sampling of things that are easy to access.  technically speaking, this is a composite of many other biases, and may be seen as second-order.

a prime example of this is the proportions of written and spoken texts in many corpora, and even the proportion of elicited spoken vs. 'natural' spoken texts, due to the disparity in difficulty in acquiring consent (and grammar!)

[ interestingly, corpus builders seem to be willing to spend umpteen hours manually coding a book, yet refuse to properly sample something if it doesn't already have a centralised index.  perhaps this is because they can hire grad students for the former ;-) ]


### lack of variance/saturation analysis (see stratum selection)
see 'size#no methods for saturation/internal measures'


### nonrandom sampling of stuff 
(i.e. web crawls)
though much effort is made to randomly sample where possible, some forms of corpus are particular surceptible to the siren-like call of availability sampling.

in many cases, such as web crawling to find wac data, nonrandom sampling strategies are often used due to the lack of an authoritative (or reliable) central index.  in others, such strategies may be the result of practical issues, such as the location of researchers or legal concerns surrounding certain contexts.

notably, it's possible to augment and correct for a lot of the problems that are introduced through nonrandom sampling, and schafer+bildhauer do this in their web-scraping corpus building tools, which attempt to stratify their samples by top-level-domain after selection (the extent to which this actually works is debatable, and will be discussed in greater detail in the wac section).

nonrandom sampling is an unavoidable pragmatic truth of corpus building in almost all contexts, and with care should not unduly influence the result of a corpus building effort.  with proper stratification, this problem is guaranteed to be of equal or lesser magnitude to that of omitting some variables from stratification efforts.



### incomplete coverage within each stratum [use of proxy vars]
note that this is distinct from specifying the population, or ensuring that the strata cover the population.

ignore the blockquote below, it's a bit conflated.:
> a prime example of this is the sampling of books from the bnc (as stated above, perhaps re-paste?).  this strategy selects from a number of different lists under requirements of the books being popular and written in a given year.  though the bnc aims to represent language use in britain synchronically, this portion of it could more accurately be described as a sample of authors' language use in that year.  it seems irrational to suppose that authors are representative of the general british-english speaking population, or even that those *reading* the works (who may or may not 'agree' with the language used within) are representative of that wider population.  indeed, if we believe the taboids, the percentage of people who read books is fairly small.  further to this, among book readers, it is important to consider that many of them will be reading classics or mixing their reading through time, something deliberately excluded by the bnc's sampling strategy.







size
----

### no overall size established 
(w.r.t strata, and randomness above)

### no methods for saturation/internal measures
(see randomness)
within strata, no efforts are made to ensure that we have sufficient data to represent linguistic variation.  the obstacles to constructing such an internal measure are great, since they relate back to problems of establishing the limits of variation within language.

evert's (zipfr) lnre models offer possibly the most advanced method for this, and can be seen as a progression upon biber's variation analyses of the early nineties.  the issues with using such models to determine corpus variability sit neatly in two categories:

 1. selection of interesting variables to measure sufficiency (this, in reality, would be part of the corpus documentation: we can say it is sufficiently representative for frequency counts, grammatical analyses up to n tokens, etc. with little risk)
 2. decisions on how much data is enough data.  this is fairly easy to approximate with a sufficiently accurate language model, and even simple binomial approximations prove useful in judging the likely frequency of features.

in spite of the practicality of the techniques surrounding measures of internal feature saturation, few currently do such analyses.  this is perhaps because the linguistic researcher himself must usually perform the analyses, rather than the corpus builder.

notably, [someone, ahrg, mentioned in greis 'exploring variability' iirc], has looked into applying these methods to corpus stuff... find+review paper.



### no multi-phase/iwp design
*todo: this really belongs elsewhere, since this point repeats some of the others and the discussion would suit there instead*
perhaps due to biber's dismissal of the design, little work has been done on constructing truly proportional corpora.  biber's primary objections were phrased in statistical terms:

> ""

yet are motivated by entirely practical considerations.  since his description of representativeness served to flatter many corpora of the time, it seems to have been widely accepted by those without particular interest in statistics.  nevertheless, some have challenged particularly this assumption.  varadi (2001) flat-out rejects his definition, stating that it is particularly unwise to re-approriate such a widely used and recognised term.  [check greis' discussion, get quote from leech's paper].

ultimately, i am willing to entertain biber's point in relation to stratified sampling in the general case: it is often desirable and necessary to inflate the smaller strata in order to properly represent the variation within.  this, however, is purely a *practical* issue, and should not be confused with the ideal case of pure random sampling.

biber goes on to advocate a watered down (non-proportional) multi-phase design, including the figure:

[figure from p256 biber93]

which has been seen by many (and recommended by eagles) as a wise strategy for corpus building.  nevertheless, as is noted above, it is seldom followed even roughly.


sampling unit
-------------

### too large sampling unit damages corpus coverage
i.e. for a given corpus size in words, the size in units may be too small.
any sample is, strictly speaking, best measured in terms of its sampling unit.  this issue has been inspected many times, as it is particularly visible during corpus analyses.

biber's initial assessments of language variation in 1988 assessed the suitability of the 2000-word sampling unit by splitting each sample and comparing the relative frequency of features in each half.  he determined that, if they were the same, then the sampling unit size was sufficient to represent a given feature.  this lead to the conclusion that corpora were adequate for inspection of 'small-scale grammatical features', something that seems to be bourne out by the success of corpus methods in this area (pos tagging, etc.).

this issue is often phrased in terms of dispersion, i.e. the tendency for a feature to be represented evenly in all documents throughout the corpus.  dispersion is something that manual inspection of concordances and corpus data makes particularly egregious, as it is often possible to see that all instances of a particular idiom are tracable to a given author, or all coverage of a certain topic is from one publication.  this is a prime example of the unit of analysis being far smaller than the sampling unit, a problem that is receiving increasing recognition.

evert, with his library mataphor, describes a sampling policy for corpus linguistics that touches upon this distinction.  in it, he describes randomly sampling progressively smaller units in a virtual library, moving from books through pages to sentences.  todo: check if he stops short of words, iirc he does.

since most statistical problems arise from the disparity between sampling and analysis units, a particularly problematic instance of this issue is the use of bag-of-words (frequency) models.  these model language without taking into account order, and as such would be best applied to a corpus sampled at the word level---any section of text beyond this is going to exhibit 'clumpiness' effects that are beyond the comprehension of the model.

the prevalence of bow models is such that many people choose to phrase their objections in terms of the accuracy of binomial models of language frequency [kilgarriff, evert's lnre stuff again].  undoubtedly they have a significant point---more complex lnre models are capable of far more useful inferences, however, it's worth noting that only a model that can integrate the linguistic influence of word 1 upon word 2000 in a sample will truly justify a 2000-word sample.

%--

one part of the problem is caused by a fixation on word lengths.  a given corpus, 100,000 words in length, may comprise just 50 texts.  for the purposes of many analyses involving person-person variation, it can be said that we really only have 50 data points.  though care if often taken to sample these texts broadly, the idea of targeting a corpus in terms of its word length, rather than the number of samples, leads to extremely poor suitability for analysis of many small-scale features.

the problem of quite what sample size to choose is a trade-off: if we were to sample single sentences for our 100,000 word corpus, we would soon require thousands of samples, each from a randomly selected and carefully-stratified source.  if we wish to perform a complex analysis of narrative structure within those sentences, we'd find there isn't sufficient data.

except in certain cases, there is a plateau of difficulty for sample size: sampling 1000 words from a book incurs very similar levels of practical obstacles than does sampling 100.  sampling units should be chosen in accordance with the complexity required by researchers of the time---i would estimate that those working in ir and nlp fields will demand relatively large sample units by comparison to many researchers in linguistics.

if there's one lesson to learn from this, it's that you should define your corpus in terms of sample points, *not* words.




### conventionalised to a weird/large number 
(2k) (biber)
as mentioned above, the sampling unit for general-purpose corpora is conventionalised to a figure of 2000.  this figure has undergone almost no refinement since it was originally determined by the brown designers, and has (again, as mentioned above) been reinforced by biber's determination that it is sufficient to represent small-scale grammatical features.

though 2000 words is far from an unsuitable selection, people's targeting of word lengths, and use of word-frequency analyses, leads me to believe that it should be significantly shorter in order to maximise the utility of a corpus.



### heterogenous between corpora 
(see comparison.  as mentioned there, this isn't much of an issue really)



### "clumpiness" of language is not considered
see discussion on "too large" above.  this is merely another way of phrasing it.


### not formally specified or justified using semantic models
as discussed in "too large", the sampling unit should be selected according to, ideally, the internal properties of language.  philosophically speaking, language is a set of conventionalised symbols with which we may communicate with other people---the limit beyond which one word no longer meaningfully associates with others should be the point at which we draw the sampling unit.

given context of a document, this may be un-nervingly large.  strictly speaking, it probably encompasses the whole history of the universe (in a manner similar to bayesian priors), however, that's only if we reason ad nauseum.

a more practical limit, at least until neurolinguistics establishes the latter in a meaningful manner, is to sample at the maximum size for which we have models of language that may practically be applied.  for many black-box nlp techniques, this means we wish to have large sampling units in order to tease apart subtle interactions.  for many manual inspections of corpora for [especially qualitative] linguistic research, we will want to select a shorter sampling unit.



comparability
-------------

### sampling unit
see also 'sampling unit'
the differing size of the sampling unit between corpora renders many of them incomparable.  this is a fairly minor point, since many use the brown-standard 2k-word unit, chosen randomly from the text.

### poor documentation of intent, sampling policy, population bounds
see 'population'

in order to perform scientifically meaningful comparisons, one must be sure that the populations between corpora differ in known ways.  though it is often possible to identify corpora that claim to be comparable in this manner, and use strikingly similar selection policies due to this, the smaller undocumented assumptions made by builders often cause minor differences, which may be crucial to certain forms of inquiry.

prime examples of this are sampling from index lists compiled by different companies, or using different cultural definitions of formality.  more with some proper examples...

the issue with this is not that corpora are very heterogenous and likely to be incomparable at a conceptual level, but that the lack of documentation on things such as the objective bounds of strata (see stratum selection) makes reasoned comparison by a user of the corpus impossible.
