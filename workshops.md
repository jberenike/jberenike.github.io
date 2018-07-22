---
layout: default
title: workshops

---

# 2018 

## July

### Symposium “Digital Humanities @IGEL”
Symposium at <a href="http://igel2018.no/" target="_blank">Biannual Conference of the International Society for the Empirical Study of Literature and Media (IGEL) at Stavanger, Norway</a>,  Stavanger (NO), July 25-28, 2018.

List of Speakers
- Peter Boot, Huygens Institute for the History of the Netherlands (Huygens ING).
- Sissel Furuseth, University of Oslo, Department of Linguistics and Scandinavian Studies.
- Arthur Jacobs, Department of Experimental and Neurocognitive Psychology, Freie Universität Berlin.
- Karina van Dalen-Oskam, Huygens Institute for the History of the Netherlands (Huygens ING) / University of Amsterdam.
Symposium Chair J. Berenike Herrmann

While the digital scholarship symposium at the Chicago IGEL conference 2016 focused on dimensions on “textual analysis”, this year’s convention will cover digital approaches towards "cultural heritage computing". 
It will highlight how digital resources can be utilized for sound empirical research on texts, readers, authors, and contexts. The four contributions will report on trends and methods in digital approaches to literary and cultural artefacts from an array of epochs, languages, genres, and cultures. The range stretches from assessing underlying norms of contemporary Dutch user-based online book reviews (Boot) to the networks underlying Norwegian magazine culture of the 1890s (Furuseth) - from patterns of author similarities based on latent semantic analysis, lexical diversity and sentiment analysis (Jacobs) to the features and dimensions of contemporary novels written in and translated into Dutch (Van Dalen-Oskam). The methods covered are Multimethodological Reader Reception/Evaluation, Surface and Distant Reading for Transnational Periodical Archives, Quantitative Narrative Analysis (QNA), and Literary Stylometry.
 

#### Peter Boot: Online reviewers' criteria for judging books

The ODBR database of Online Dutch Book Response contains (at the time of writing) 390,000 (short) online book reviews and 510,000 other book response items, harvested from Dutch-language mass review sites and from the largest online bookseller in the Netherlands. While a resource such as this, based on self-selection of participants, can never pretend to be representative of 'the' reader, the database does bring together a very large collection of non-professional writing about literature and books more generally. My paper for the panel will look at the standards about quality in literature and reading that people explicitly or implicitly express in the reviews and other discussions that the database holds. 
Because of the size of the collection, the study of the reviews requires a tool for ‘distant reading’, a tool that can summarize the evaluative aspects discussed in reviews. As far as I know, no such tools at present exist, certainly not for Dutch. What exists are tools that determine positive or negative sentiment in a review. More advanced tools can associate sentiment with aspects of simple and standardized products, such as cameras, but certainly not for books. 
	For describing the evaluative aspects in reviews, I use a version of the coding system developed by Linders (2012). Linders distinguishes aspects of books (e.g. style, plot, characters) and characteristics that are applied to these aspects (e.g. emotion, vividness, familiarity). A vivid style can be coded as "A 4": "A" for style and "4" for vividness. Some of the characteristics represent a scale: the axis of familiarity is used both for familiarity and for unfamiliarity. I have added some characteristics to Linders’ system, and also explicitly code whether an evaluation is positive or negative and which end of a scale is applicable. 
	To create a tool that will be able to analyse the corpus I create rules that associate textual patterns with evaluative codes. For instance, the word group ‘in one sitting’ will usually indicate the book was a good read and a rule will be created that associates ‘in one sitting’ with K 18 1 p (= book in general, entertaining, positive end of scale, positive experience). Sometimes the patterns will be much more complex:  the word ‘accessible’ is not necessarily evaluative, but used within a certain distance from ‘book’ it probably is; however, if the word ‘not’ occurs in between, the evaluation is probably no longer positive. Patterns that express conditions like these can be formulated using the Corpus Query Language (CQL), as e.g. "book"[word!="not"]{0,5}"accessible". This requires a phrase beginning with ‘book’ followed by between zero  and five words unequal to ‘not’, followed by the word ‘accessible’. Patterns can also use lemmas, regular expressions (extended wildcards) and  part-of-speech tags. 
	In order to test the feasibility of this approach, I am currently working on simultaneously annotating  the reviews of works by the widely read Dutch novelist Tommy Wieringa and creating the corresponding rules. The database contains 393 reviews of Wieringa’s works. By now, 303 annotations have been made to 78 reviews. 253 rules have been created.  The average Spearman correlation between the manually applied annotations and the annotations  as computed (based on applying the rules to the text of the reviews) is 0.75. This investigation is ongoing, but the correlation suggests that, based on the textual patterns,  we can get a pretty good idea of the criteria a reviewer uses in judging a book. This also implies that it should be possible, at a later stage, to do research into e.g. how different criteria are applied in judging different genres or how different readers or reader  groups apply different criteria, without the need to manually annotate thousands of reviews. 

Linders, Y. (2012). Argumentation in Dutch literary criticism 1945–2005. In C. Perry & M. Szurawitzki (Eds.), Sprache und Kultur im Spiegel der Rezension (pp. 261-268). Frankfurt am M.: Peter Lang.


#### Sissel Furuseth: Mapping the Global Networks of Periodicals 

In the twentieth century, the niche of periodical studies was taken care of by a small dedicated group of modernist scholars. During the last fifteen years, however, the field of periodical studies has expanded tremendously, especially at the English departments worldwide, thanks to extensive digitization of magazines and newspapers. The development of digital archives allows for more systematic studies of the rich variety of periodicals, old as well as new ones, small as well as mass-market magazines, giving us access to the past in ways not explored before. For instance, digitization has made it easier to map the underlying infrastructure that connects magazines and writers together in their transnational networks. Thus, scholars are encouraged to combine close reading and surface reading with new techniques of distant reading (cf. Moretti, Cohen, Collier, and others). In my presentation I will address some possible lines of investigation in today’s periodical studies, based on my recent research on the Norwegian magazine culture of the 1890s.


#### Arthur M. Jacobs: The Gutenberg English Poetry Corpus (GEPC): Exemplary Quantitative Narrative Analyses

This paper describes a corpus of about 3,000 English literary texts with about 250 million words extracted from the Gutenberg project
that span a range of genres from both fiction and non-fiction written by more than 130 authors (e.g., Darwin, Dickens, Shakespeare).
Quantitative Narrative Analysis (QNA) is used to explore a cleaned subcorpus, the Gutenberg English Poetry Corpus (GEPC; Jacobs, 2018)
which comprises over 100 poetic texts with around 2 million words from about 50 authors (e.g., Keats, Joyce, Wordsworth). Some exemplary
QNA studies show author similarities based on latent semantic analysis, significant topics for each author or various text-analytic
metrics for George Eliot’s poem ‘How Lisa Loved the King’ and James Joyce’s ’Chamber Music’, concerning e.g. lexical diversity or
sentiment analysis. The GEPC is particularly suited for research in Digital Humanities, Computational Stylistics, or Neurocognitive
Poetics, e.g. as training and test corpus for stimulus development and control in empirical studies.

Jacobs AM (2018) The Gutenberg English Poetry Corpus: Exemplary Quantitative Narrative Analyses. Front. Digit. Humanit. 5:5. doi: 10.3389/fdigh.2018.00005 

#### Karina van Dalen: Moving beyond authorship. Literary stylometry

Computational approaches to literary texts are becoming more visible and are drawing more attention than ever. In stylometry, the focus is moving to topics beyond authorship alone. I will give an overview of what kind of topics could be addressed with stylometric methods that may shed more light on what literary texts are and how they are being received by readers, editors and publishers.



## April
At Le Mans University (invited by <a href="http://3lam.univ-lemans.fr/fr/membres/enseignants-chercheurs/ouvry-vial-brigitte.html">Prof. Brigitte Ouvry-Vial </a> and <a href="http://www.anne-baillot.eu/Home">Prof. Anne Baillot</a>) I will give an interactive lecture <a href="http://www.msh.univ-nantes.fr/96280119/0/fiche___actualite/&RH=ACCUEILhttp:/" target="_blank"> the Atelier Numérique "Gérer et explorer les données textuelles"</a> on 10 April 2018. Here is my abstract:

### Text mining for cultural heritage: A very short intro to measures of readability and metaphor
This lecture is an interactive report on two core indicators of textual style, readability and metaphor. In two consecutive parts, I will introduce standardized methods for gauging the degree of textual complexity (the Flesch Index) and identifying metaphorical language use in a reliable way (MIPVU). As a minimal formal measure of style, the Flesch Index is relatively easily applied to digital data and facilitates pattern finding. Its interpretation, however, needs to be informed of factors such as textual genre and audience. By contrast, the metaphor identification procedure requires annotator training and iterative validity control, but may feed into procedures of Machine Learning. Both methods may be applied to various languages.
The methodological introduction will comprise a practical part in which the participants try out the Flesch-measure and evaluate its implications. This practical experience will be supplanted by my research results for the transition between Literary Realism and Modernism in German Literature (ca. 1860-1930) and a brief introduction to the literary dataset used, the Corpus of German Literary Modernism (KOLIMO). The aim of the lecture is to give participants an hands-on experience of applying formal measures of textual style before the background of the workflow and theoretical modeling of a well-rounded DH-project.


# 2017

## December 
In December, I ran the <a href="https://github.com/jberenike/kolipos/wiki" target="_blank">Hackathon KOLIPOS</a> for advancing POS-annotation in <a href="https://kolimo.uni-goettingen.de/index.html" target="_blank">KOLIMO, the Corpus of Literary Modernism</a>. I was able to invite Thomas Proisl (Erlangen-Nuremberg), student assistants from my former research group and from the Campus Lab Digitization from Göttingen as well as new collaborators from Basel. The event was kindly hosted by <a href="http://dhlab.unibas.ch/DH" target="_blank"> DHLab Basel</a> and supported by <a href="http://www.ub.unibas.ch/ub-hauptbibliothek/" target="_blank">University Library Basel</a>.

# 2016 

## July
Together with Francesca Frontini, I organized the Symposium "The Power of Digital Text Analysis #IGEL2016" <a href="https://sites.google.com/site/igelchicago2016/program" target="_blank"> at the Biannual Conference of the International Society for the Empirical Study of Literature and Media (IGEL)</a>

Here is the program:

# Summary
IGEL is probably best known for supporting psychological approaches to literature / empirical aesthetics.  However, it also has a tradition of quantitative/digital literature studies (e.g., van Peer, 1989; Kuiken and  Miall, 2001; Louwerse et al., 2008; Louwerse and van Peer, 2002; and more recently, Biber, 2011;  Egbert, 20012; Jannidis and Lauer, 2014; Pennebaker and Ireland, 2011). Given the steady progress in literary and media data digitization and the availability of increasingly powerful tools (e.g., Jockers, 2014; Manovich, 2015), IGEL now aims at invigorating this tradition with new perspectives from the thriving  communities of Digital Humanities, computational linguistics, and corpus stylistics. 
The symposium features four invited papers that report on digital methods of analysis applied to literary texts. Gerhard Lauer will open the symposium by situating ‘the digital approach’ historically and epistemologically, introducing key questions, concepts, methods, and resources of digital text analysis for literary data. The other three papers are exemplary studies documenting the diversity and power of digital approaches within the broad field of literary studies. Their research questions and methods tap into  linguistic, social-psychological, and cultural-studies backgrounds: First, Gabi Kirilloff (co-author  Matthew Jockers) will report on a large-scale analysis of 19th century novels from British and American  contexts, examining verb-pronoun pairings as an indicator of characterization. The contribution by Taleen Nalabandian (co-author Molly Ireland) will focus on using digital text analysis of scripts to determine if they are aligned with theory (i.e., Narrative Art Theory). The paper by Richard Jean So applies a digital socio-cultural approach to literary discourse, modeling broader patterns of racial inequality in the US literary field. It interlaces close reading and broader, macro scale methods. The symposium reflects the potential and spectrum of a new generation of digital literary analyses with regard to empirical, methodological and conceptual perspectives. Besides examples of research design and questions about corpus building, the symposium will give insight on how the newest digital studies approach domains such as: style, plot, characterization and gender, as well as perspective-taking, social cognition, and questions of socio-cultural patterns.

 
Saturday July 9th, 8:30-10:35 am, Honore Room

8:35-8:55 AM
## Sorry, I have Digitized my Scholarship. A Short Introduction into Computer-Based Literary Studies
Gerhard Lauer

The talk will address three main issues of digital text analysis in literary studies: the need for formalization, the main computer-based methods, and the basic resources. In a first step, the talk explains the necessity and method of translating cultural objects (like texts) into computational corpora. Secondly, chief methods of text analysis, from word counting to sentiment analysis, are introduced. And thirdly, I will introduce hands-on examples of textual analysis using principled collections of digitized texts.


9:00-9:20 AM
## Understanding Gender and Character Agency in the 19th Century Novel
Matthew L. Jockers and Gabi Kirilloff

The authors employ dependency parsing and machine learning in order to identify and study the relationship between verbs and pronoun gender in a corpus of 3,000 19th century novels. Verbs are demonstrated to be a strong predictor of pronoun gender with classification accuracies ranging between 90-95% in cross validation testing. The authors argue that these verb-pronoun pairings serve as a reasonable proxy for character agency and allow us to study and explore 19th characterization. Trends in pronoun gender and verb pairing are shown to be consistent across the century, with no measureable impact associated with either novelistic genre or author gender. Several works are identified as outliers and are discussed briefly.  

9:25-9:45 AM 
## What Makes a Narrative (Great)?
Taleen Nalabandian and Molly E. Ireland

In an extension of Narrative Arc Theory (NAT), we analyze dramatic film scripts (N=509) with LIWC to determine whether elements of NAT play a role in shaping the typical structure of scripts and if these elements are favored by professional critics versus lay audiences. Results indicated the general form of NAT was replicated for scripts with a few noteworthy deviations. Further, audiences seem to prefer typicality within films, whereas, critics prefer more complex, mood-changing narratives.  


9:50-10:10 AM
## Modeling Racial Discourse and Inequality in the Literary Field
Richard Jean So

This paper attempts to quantitatively and computationally model racial discourse in the US novel (1880- 2000), and in doing so, model broader patterns of racial inequality in the US literary field. It draws on  both qualitative theories in minority discourse (Gates, Baker, Lloyd) as well as quantitative methods in  text analytics and economics (Schelling) to create a model that pivots between close reading/qualitative  notions of racial language/discourse and broader, macro scale dynamics of racial hegemony in the cultural field.  


10:10-10:35 AM
## General Discussion
What is the potential and spectrum of a new generation of digital literary analyses? 

How do apply them in studies of textual characteristics, including literary history, but also to the dimensions of reader, author – and society?


## References
<br>Biber, D. (2011). Corpus linguistics and the study of literature: Back to the future? Scientific Study of Literature, 1(1), 15–23. http://doi.org/10.1075/ssol.1.1.02bib
<br>Egbert, J. (2012). Style in nineteenth century fiction: A Multi-Dimensional analysis. Scientific Study of Literature, 2(2), 167–198. http://doi.org/10.1075/ssol.2.2.01egb
<br>Jannidis, F., & Lauer, G. (2014). Burrows’s Delta and its use in German Literary History. In M. Erlin & L. Tatlock (Eds.), Distant Readings. Topologies of German Culture in the Long Nineteenth Century (pp. 29–54). Rochester, New York: Camden House.
<br>Jockers, M. L. (2013). Macroanalysis: Digital methods and Literary History. Urbana: Univ. of Illinois Press.
<br>Kuiken, D., & Miall, D. S. (2001). Numerically Aided Phenomenology: Procedures for Investigating Categories of Experience. Forum: Qualitative Social Research, 2 (1). http://www.qualitative-research.net/index.php/fqs/article/view/976/2129
<br>Louwerse, M., Benesh, N., & Zhang, B. (2008). Computationally discriminating literary from non-literary texts. In S. Zyngier, M. Bortolussi, A. Chesnokova, & J. Auracher (Hrsg.), Directions in Empirical Literary Studies (pp. 175–191). Amsterdam: John Benjamins.
<br>Louwerse, M., & Van Peer, W. (Eds.). (2002). Thematics: interdisciplinary studies. Amsterdam: Benjamins.
<br>Manovich, L. (2015). Data Science and Digital Art History. International Journal for Digital Art History, 0(1). https://journals.ub.uni-heidelberg.de/index.php/dah/article/view/21631
<br>Pennebaker, J. W., & Ireland, M. E. (2011). Using literature to understand authors: The case for computerized text analysis. Scientific Study of Literature, 1(1), 34–48. http://doi.org/10.1075/ssol.1.1.04pen
<br>Van Peer, W. (1989). Quantitative studies of literature. A critique and an outlook. Computers and the Humanities, 23, 301-307.
</p>

## Organizers
<a href="https://jberenike.github.io/" target="_blank">Berenike Herrmann - Georg-August-University of Göttingen, Department of German</a>

<a href="https://sites.google.com/site/francescafrontini/" target="_blank">Francesca Frontini - Istituto di Linguistica Computazionale, CNR</a>

