Formal Sampling
===============
This section is intending to outline sampling theory and how it may apply meaningfully to the problem of corpus building.  Much of this will already have been considered by those constructing the first corpora.



Structure Notes (from [the pdf](first_thoughts.pdf))
=================================
 1. Desirable properties of a corpus (already discussed sort of above?  maybe this ought to be outlined in greater detail or moved to after this section.
   - Size
   - Randomness
   - Validity (internal)
   - Replicability/scientific issues [reliability]
   - Flexibility

 2. Comparison and statemnent of sampling structure
   - Population Definition
   - Sampling Frame
   - Sampling Method
   - Size/Power
   - Post-hoc/reweighting
   - Bias Estimation and Evaluation

The "solutions" to these options will then be discussed in a later chapter, specifically the one that deals with sample design after the specification of various problems in the DA/Personal Corpus chapter.

Actual Notes
============
Many of the problems listed in section [ref] above are fairly minor, and careful sampling easily mitigates their effect.  A number of sampling strategies are available for selection of data, and the purpose of this section is to review them in the abstract case, in order to identify their suitability for linguistic sampling.

Though I will stop short of defining, in concrete terms, the specification of an 'ideal' general-purpose corpus, this section begins with a discussion of the aims of a corpus, and how they impact desirable properties which we may wish to maximise through proper selection of a sampling strategy. 

%- this is motivation for a later chapter really, and this subsection may want moving to after the discussion of sampling policies, or the intro to that chapter.

Desirable Properties of a Corpus
--------------------------------



### Sample Size
This is a tricky but crucial property that is much discussed elsewhere relative to linguistic properties.  In seeking a sampling strategy, it is important that we are able to accurately assess the necessary size from, at worst, modest amounts of auxiliary data.  Any method that requires significant over-sampling or repeated iteration will incur the costs and efforts associated with physically gathering the data, which is most undesirable.



### Randomness
This is a particularly thorny issue that has been little-addressed by linguists.  Upon initial examination of the problem, a simple random sample (SRS) may seem like the ideal---we know little about the data we're sampling, and use of any existing corpora to improve sampling proportions will be subject to the biases in their original design.  

Though stratified, random sample designs seem to offer the most obvious way of representing populations of texts.  This method is advocated by the Brown documentation, explained at length by Evert and others [Dunning, IIRC, covers this], and samples are treated as random by those analysing text (Biber's assessments don't weight things, for example).

The problem with random sample designs remains their attempt to be proportional.  Biber, rejecting the idea of a proportional corpus says

 > "if we were to sample proportionally, we'd just get a whole load of speech" (find in '93 paper)

This sentiment is contradicted by Varadi (2001), who calls for proportional sampling in order to ease analysis, however, Biber's point is a valid one.  The complexity of language, and its distribution over other interesting covariates, may mean that it is impractical to sample a sufficiently-sized proportional corpus.

The issue of proportionality, and sample sizes needed to acquire a useful level of significance from analyses thereon, is intimately related to the problem of selecting categories for selection, and as such should be assessed in context of a particular corpus.  If non-random sampling is to be used, it should be considered carefully and explicitly based on preliminary samples and other sources of auxiliary data.]

% --
in summary:

 * *for randomness* --- easy analysis without weights, easy subsampling, clear docs on demographics, equal 'resolution' of data for each covariate
 * *for nonrandomness* --- better representation of small populations, smaller sample needed for many purposes, faster analyses, easier acquisition



### Validity
The concept of validity is only meaningful relative to a certain task, however, we may clarify the issues by breaking up the link between the theories we wish to test and their underlying physical manifestations (which we wish to sample):
 
 * *Criterion/predictive validity* --- the degree of association between the concept measured and the value of the data acquired, i.e. are we sampling in the correct way?
 * *Content validity* --- the extent to which measurement of a given 'thing' and the theory, i.e. are we sampling the correct thing?
 * *Construct Validity* --- The extent of agreement between theories and their implications and other [currently accepted] theories. todo: This should probably be removed, it's not terribly relevant.

Alternatively, from 'SAGE's dictionary of quantitative management research' (todo: find better sources before cementing this section, check library's obscenely expensive books section):

> "Internal validity is the quality of an experimental design such that the results obtained can be attributed to the manipulation of the independent variable, whereas external validity is the quality of an experimental design such that the results can be generalised from the original sample and, by extension, to the populatrion from which the sample originated."

Both of these are impossible to fully determine without first having an experimental design, however, a poorly designed corpus will yield fewer valid designs and uses than will an equivalently-specified well-sampled one.  Further to this, poor documentation of corpora may lead people to incorrectly assess the validity of their application.

[todo: include discussion on transferrability/generalisability; decide which of the above formalisms to use (probably internal/external, the former offers little but might be handy for discussing links between proxy variables and sample selection)]




### Replicability and Reliability
The replicability of studies based on the same corpus is one main reason for using general-purpose corpora.  One major concern with the use of larger corpora is that they are quickly rendered out of date for certain purposes: those studying technology-related neologisms, for example, are likely to call upon web corpora and more recent publications, rather than look to more established works, because their hypotheses centre on a rapid change which is poorly represented by a decade-old corpus, however balanced.

[perhaps it'd be nice to look through some journals and count who's using corpora of what age here, might be handy]

Synchronic corpora are also, given their very narrow temporal distribution, more likely to represent fashions and short-term affectations.  Whilst this may initially be desirable, the relevance of its data to other corpora, and to everyday life, diminishes in a difficult-to-predict fashion (indeed, change through time is a whole area of inquiry in its own right).

[ talk about how technology might help, but link to future sections instead of going too far into it]




### Flexibilty/Generality
One of the aims of a general purpose corpus is to foster re-use of data for all those studying a given population, across a multitude of research questions.  Though, as the above discusses, it is necessary to restrict the useful domain of a corpus during the design stages, care should be taken to sample a sufficiently general population of language users (and a sufficiently general set of variables on each one) so as to be useful in many different study designs.

Efforts in this area have primarily centred around two foci---the former of these is the proper selection of corpus variables and sampling, discussed in collaborative efforts to standardise corpus design:

> There's a quote from EAGLES where they say, in effect, "one of the major contributions of this is that we've got people talking about standardisation and collective use"

[ todo: also see efforts to cover corpus design in general, seek from Bibtex list. ]

The latter of these surrounds subsampling corpora for given uses.  Subsampling is a relatively common operation for general purpose corpora, and many commonly-used corpus analysis tools such as SketchEngine and CQPWeb [bncweb?] support simple mechanisms for constructing subcorpora.

The representation of the [ahrg, can't find the paper, austrian? national] corpus was designed such that text was stored in "chunks", aligned with powers of two.  This, along with an interface that allowed selection of these chunks to form a subcorpus, allowed a user to subsample the corpus with high levels of granularity for each of the variables he was interested in.  Perhaps due to the focus on having fairly large text samples, this approach does not seem to have caught on [yet...].




Sampling Strategy
-----------------
*NB: I don't wish for this to get too prescriptive.  It's intended as an overview of an idealised procedure, rather than a "how to", which will basically come later in a far more practical form*

### Population Definition
Defined in terms of

 * aim of corpus & science, who would find a given set useful for study?
 * External validity justification
 * Causal systems of language, variation within them

How: Population estimation methods

 * Applications to language (not sure of any in the abstract, todo: find some.)
 * Applications to the web (google/yahoo estimation papers from DA bibtex)




### Sampling Frame

 * Enumeration/definition
    - taxonomy specification work, p'raps?  this is possibly too 'linguistic' for this section though
 * Subsampling with/without weights
 * Using auxiliary information to weight strata
 * artificial inflation of interesting sections of the population (modelling, stratification)



### Sampling Method
A discussion of what each does, and where it seems to be used, split up into nonrandom:

 * Snowball sampling (web crawlers)
 * 'Purposive' in general (applies slightly to many things, perhaps worth mentioning but not really labouring)

and random:

 * SRS (more special purpose focus, mention use in re-sampling)
 * Stratified (focus on this, mention IPW, use of external data to find proportions, primary dimensions of variation and link to taxonomic stuff)
 * Multi-stage (link to above, perhaps belongs in that section)
 * Cluster (may simplify some practical issues)
 * Adaptive (possibly introduce later since it's a plausible solution to some issues, but not currently used.  Some parallels with the iterative method)


### Size
Methods for selecting sample sizes, stratum sizes, sampling unit sizes [last of these is mainly linguistic, but might be worth mentioning].

 * Criteria for selection
   - purpose-based models [should be big enough for x]
   - sufficiency/internal measures [should contain n xs]
   - breadth/variation [should contain n types of x]
 * Big data's approach
 * Size of auxiliary data for multi-stage designs


### Post-hoc/Reweighting(/representation)
Methods for upping weights in line with auxiliary data, even of existing corpora.

 * Establishing weights using auxiliary data
    - possible sources of valid data
    - existing manual resampling by selection of categories (compare to above method)


### Bias Estimation/Evaluation
Methods for evaluating and comparing corpora

 * Bootstrapping
 * Comparison to other corpora (validity, meaning, can we trust previous corpus to be a gold standard?)
 * Comparison to humans (heuristics, summarising, "getting to know your corpus")


