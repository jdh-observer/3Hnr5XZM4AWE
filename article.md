---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: markdown
      format_version: '1.3'
      jupytext_version: 1.18.1
  kernelspec:
    display_name: Python 3 (ipykernel)
    language: python
    name: python3
---

<!-- #region editable=true slideshow={"slide_type": ""} tags=["title"] -->
# Digital History and the Epistemology of Artificial Intelligence: New Frontiers in Historical Inquiry
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["contributor"] -->
 ### Salvotore Spina [![orcid](https://orcid.org/sites/default/files/images/orcid_16x16.png)](https://orcid.org/0000-0001-6367-8183) 
Università degli Studi di Catania
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["copyright"] -->
[![cc-by](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/) 
©<AUTHOR or ORGANIZATION / FUNDER>. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY](https://creativecommons.org/licenses/by/4.0/)

<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["copyright"] -->
[![cc-by-nc-nd](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/) 
©<AUTHOR or ORGANIZATION / FUNDER>. Published by De Gruyter in cooperation with the University of Luxembourg Centre for Contemporary and Digital History. This is an Open Access article distributed under the terms of the [Creative Commons Attribution License CC-BY-NC-ND](https://creativecommons.org/licenses/by-nc-nd/4.0/)

<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["keywords"] -->
Digital Ecological Niche, Digitality, Historiography, Computational Methodology, Artificial Ally
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} tags=["abstract"] -->
This article critically examines the evolution of Digital History (DHy) as both a methodology and historiographical framework, engaging with the epistemological challenges posed by the digital turn in historical research. The text argues that, while digitisation and computational tools offer new possibilities for analysis, these technologies have not yet fully transformed the historian’s craft. Digital History must transcend mere data collection and archival access, incorporating Artificial intelligence tools and Machine Learning into its interpretive processes. By exploring the limitations of current digital platforms and the lack of fully integrated AI systems for historical analysis, the article proposes a vision where historians, in collaboration with computer scientists, develop semantic ontologies and computational models capable of replicating historical reasoning. Through this interdisciplinary approach, DHy promises to augment historiographical practices, enhancing the capacity to interpret vast datasets and uncover previously hidden patterns in historical research. The article concludes by urging historians to embrace this transformation, acknowledging that Digital History is not just a methodological innovation but an epistemological necessity for the future of the discipline.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
## Introduction
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Discussing History, historical research, and research methodology is no straightforward task; or rather, it might appear artificial to question the foundational principles of History’s epistemological status—principles that theoretical and philosophical inquiry has long attempted to define within a paradigmatic structure.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Nevertheless, the advent of Digitality (Spina 2024b) and its ‘innovative’ (yet centuries-old) presence prevents us from drawing definitive boundaries around such debates or from ‘subscribing’ to a final and immutable statute—regardless of the monumental insights that have shaped the ‘discourse on History’. As Reinhart Koselleck observed, the “theory of history,” while adopting the methodology of the natural sciences, maintains a critical asymmetry that sustains ongoing debate. At the same time, even as historiography may yield increasingly truthful information—“more and more truthful” (Koselleck 2002)—History remains fundamentally interpretative, perpetually open to renewed inquiry. This assumption also underlies the approach of histoire sérielle (Chaunu 1964; 1983), a methodology in which sources are embedded within a series that may grow and evolve through continuous investigation. Koselleck would further assert that “the concept of History includes a concept of historical knowledge that knows itself to be always provisional and open to revision.” This necessary tension is exemplified in the well-known debate between Fernand Braudel, the proponent of the longue durée as the sole methodological lens capable of accessing the deeper structures of society, and Carlo Ginzburg, who advocates for the epistemological validity of the event-based approach. This methodological divergence, and the differing levels of historical inquiry it entails, underscores the restless and unresolved nature of the “theory of history”: it seeks a project of objectification while remaining grounded in the most intimate and subjective of reflections, where even the briefest occurrences may emerge as indelible historical signs.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Assuming the legitimacy of both approaches, it becomes even more evident that “Digitality” reopens long-standing theoretical dilemmas—issues once thought to be resolved through dialectical synthesis—revealing the enduring difficulty of privileging one interpretative axis over another. Chief among these is the longstanding quantitative–qualitative divide (Darcy and Rohrs 1995; Dollar and Jensen 1974; Furet 1971), which now resurfaces with renewed urgency. Historians today find themselves inevitably drawn to the appeal of Big Data (Graham, Milligan, and Weingart 2015; Kaplan and di Lenardo 2017; Santoro 2015; Schiuma and Carlucci 2018), stemming from the proliferation of digitisation projects targeting archival corpora. These developments have catalysed a new awareness: data now exists in the billions—gigabytes upon gigabytes—unmanageable in scope, yet each fragment demands rigorous analysis to reconstruct past events. Even more crucially, such analysis must address the epistemological challenge of validating these data as historical sources capable of supporting the historian’s research questions.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The discourse surrounding digital and Digitality permeates the theoretical fabric of all sciences—especially the historical disciplines. Despite the seminal reflections offered in the first half of the twentieth century by figures such as Le Roy Ladurie (1968; 1973), Chabod (1969), Bush (1945), and Furet (1968; 1971; 1981), the field is still, even thirty years after the advent of the Web and early theoretical explorations into the use of artificial intelligence in historical research (Ennals 1986), in search of a coherent direction for Digital History. The question remains whether to formulate a clear manifesto, and whether (or not) to accept that methodology—whether in the natural sciences or the humanities—is a product of its time. The methodology reflects the technological threshold reached by humanity, both as a tool of self-understanding and as a historical phenomenon in itself—thus becoming a source that self-analyses under the critical guidance of the digital historian.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
## Digital History: A Historiography of Digitality or merely a Methodology?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
If, as Marc Bloch (2016) contended, time constitutes the essential “dimension” within which the historians’ craft is to be situated, it is even more accurate to assert that time—once a Kantian a priori category (Kant 1820)—becomes a malleable concept in the hands of historians, who possess the ability to compartmentalize time, meticulously dividing it into fragments that are tailored to the epistemological need to describe a phenomenon, an event, or even a single human action.
According to Thomas Mann, time is not divided internally into units that possess independent significance. Similarly, the concept of natural time bears little resemblance to historical time (Koselleck 2002). On the other hand, according to Lord Acton (1906), the chronological segmentation of time serves as a methodological principle underpinning the analysis of historical problems. Hence, Braudel dissects time into three strata—short-term, medium-term, and long-term duration—, while Ginzburg fragments it into an increasing number of event-based intervals.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The scholarly reflection on Digital History (DHy) must begin with this premise: the need to first define its temporal coordinates—and, by necessity, its spatial ones. Indeed, conceptions of temporality are deeply embedded in spatial metaphors, as illustrated by Braudel himself when aligning his temporal schema with the "liquid continent" of the Mediterranean. In this “hinc,” Braudel reveals the linkage between durations and events that are, by extension, also spatial:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
> “What is the Mediterranean? A thousand things at once. Not a single landscape, but countless landscapes. Not a single sea, but a sequence of seas. Not a single civilisation but overlapping civilisations. To travel in the Mediterranean is to encounter Roman ruins in Lebanon, prehistory in Sardinia, Greek cities in Sicily, Arab presence in Spain, Turkish Islam in Yugoslavia. It is to plunge deep into centuries, from the megalithic temples of Malta to the pyramids of Egypt. It is to encounter ancient things still alive alongside the ultramodern.” (Braudel 2017)
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In a manner akin to the Mediterranean's embodiment of layered spatialities and temporalities, the digital realm also manifests such complexity.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The terms "digital," "digitisation," and "information revolution" are frequently invoked in academic discourse, yet their application is often anchored in the technological developments of the past half-century. This tendency suggests a tendency to conceptualise these terms within a short-term memory framework, potentially obscuring a broader historical and technological context. Yet, Digitality reveals itself as a long durée phenomenon (Spina 2024b), with computing merely the latest manifestation of a process whose roots stretch back centuries. Computer science enables us to (re)digitise—and thereby (re)encode—language, allowing us to formulate instructions and prompts for computational systems.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, such a focus risks relegating technological infrastructures to a secondary role—despite their undeniable impact on our interactions with the world, other humans, and machines. Artificial intelligence tools, for instance, embody the notion of “interaction,” presenting themselves as entities capable of far exceeding the functionalities traditionally associated with classical computing. This is not a novelty: historians have engaged with these tools since their inception. In 1986, Richard Ennals published a seminal work addressing the necessity of methodological reflection on the application of computing, especially AI, to historical research: Artificial Intelligence. Applications to Logical Reasoning and Historical Research.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The advent of the Web and algorithmic innovation has inaugurated a radically new epistemological landscape. Yet, despite a growing awareness of these shifts, a coherent theoretical appraisal of the fundamental question remains elusive: What is Digital History?
The digital turn has prompted historians to reevaluate the very concept of History, affixing to it the adjective "digital." This association, though born of intense and often agonistic reflection, has produced a rich historiographical corpus (as outlined in Spina, in printing). Still, the resulting labels—such as “Digital History” and “Digital Humanities”—raise the critical issue: do they denote an actual methodological transformation, or merely the replacement of pen, paper, and typewriter with the computer?
This shift has effectively driven Digital History away from philosophy, thereby severing its connection to the traditions that once sought to re-anchor historical inquiry within a philosophical paradigm (Spina 2024b). The "discourse on History" has, in many ways, slipped from the hands of historians, and its disciplinary nature is now challenged from multiple perspectives—perhaps, as Barraclough (1955) suggested, due to a prevailing sense of inadequacy. Consequently, its fundamental characteristics are progressively diminished into labels that frequently mirror concerns that are not associated with the historical discipline or the inquiry at hand.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This disciplinary disengagement is further compounded by the absence of historians from major philosophical debates and digital research initiatives—what Milligan (2019, 240) terms the failure to "meet the bar." Consequently, history has been reduced to a container of disconnected past events, severed from the existential depths and longue durée processes that give them meaning.
A renewed epistemological reflection might have been expected to emerge from an engagement with Computer Science, prompting a critical reassessment of the reliability and validity of knowledge produced by digital tools. Nonetheless, this engagement remains constrained, even in the face of widely used generative artificial intelligence (AI) platforms, such as ChatGPT. The interpretation of data through computational methods raises serious concerns—not about the objectivity of History per se, which has long rejected such notions, but about the objectivity of algorithmic procedures and the biases they may encode.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The AI black box is trained on an extensive array of web-sourced data points, predominantly from open-access datasets and collaborative encyclopaedias such as Wikipedia. Above all, archival sources are missing. There exists no comprehensive body of archival Big Data on which to train AI models. These systems possess no authentic historical knowledge, save for what is drawn (often ineffectively) from sources like Wikipedia (Maleki, Padmanabhan, and Dutta 2024; Salvagno, Taccone, and Gerli 2023).
These limitations are exemplified by even rudimentary prompts. For instance, when queried about the final wish of Louis XVI before his execution, ChatGPT yields ambiguous and non-specific responses (see Figure 1). The model seems to lack the incorporation of freely available primary sources, such as Mémoires de M. l'abbé Edgeworth de Firmont (Firmont 1815), notwithstanding their accessibility via online resources.
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["King Louis XVI\u2019s last wish"]}} slideshow={"slide_type": ""} tags=["figure-louis-XVI-*"]
from IPython.display import Image, display

display(Image("./media/01a.png"))
```

```python editable=true slideshow={"slide_type": ""}
display(Image("./media/01a.png", width=1000))
```

<!-- #region editable=true slideshow={"slide_type": ""} -->
Another critical issue is scalability. AI often fails to maintain performance consistency when analysing historical texts, especially those requiring Named Entity Recognition (NER) of ambiguous or context-specific terms. For instance, when presented with the task of extracting entities from a 15th-century notarial deed from 1452 that makes reference to "Terra nigrorum" (a term denoting sub-Saharan Africa), ChatGPT demonstrated an inability to recognise the term. The entity was correctly identified only after additional training using TensorFlow (see figures 2 and 3).
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["NER on undefined places"]}} slideshow={"slide_type": ""} tags=["figure-ner-undefined-places-*"]
display(Image("./media/02a.png", width=1000))
display(Image("./media/02b.png", width=1000))

```

```python editable=true jdh={"object": {"source": ["TensorFlow training on \u2018Terra Nigrorum\u2019"]}} slideshow={"slide_type": ""} tags=["figure-tf-training-terra-nigrorum-*"]
display(Image("./media/03a.png", width=1000))
display(Image("./media/03b.png", width=1000))

```

<!-- #region editable=true slideshow={"slide_type": ""} -->
This underscores the fundamental challenge of achieving comprehensive data coverage. Not all historical sources exist in digital form. This constitutes a fundamental bug in digital historical analysis, compelling scholars to reflect on how to integrate digital with traditional sources to arrive at a fuller analytical understanding. The success of digitisation projects can be misleading, masking the fact that only a fragment of relevant historical materials may be accessible via any given database or platform. As a result, computational workflows often fail to revise historical judgments about a phenomenon or event, despite their innovative frameworks.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
History still resides in physical, analogue archives. Even if, in some future yet to be defined, the entirety of our archival heritage is digitised—thus concluding the long phase of acquisition and encoding that we are only beginning—we must still confront a pressing question: What is Digital History?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Notwithstanding the recent upsurge of literature on this topic, there has been a paucity of efforts to reorient the discourse on the subject of History itself. Any satisfactory answer must move beyond mere technological possibilities, such as the sourcing of images or the navigation of online archives and interrogate the true epistemic value of DHy.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
1.	Digital History as a historiography of Digitality, that is, a historical-philosophical inquiry into the emergence of the digital condition.
2.	Digital History as a methodological moment, i.e., the application of technology within research practices.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The initial approach is oriented towards the societal transition towards digitality. Digital technologies have profoundly influenced our perception of life, and the field of History has sought to explore the internal structure of human existence. In this context, Digital History must strive to narrate the formation of the Digital Ecological Niche (Spina 2023b), which has reconfigured human interaction systems. In this theoretical framework, historians investigate the causes and consequences of the digital transition, the formation of the digital "realm", and the redefinition of life itself.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In this context, "Digital History" is defined as a distinct disciplinary subfield, akin to Economic, Political, or Religious History, with a focus on the genesis and evolution of Digitality. It is evident that computing technologies, encompassing software, operating systems and networks, as well as platforms, have the potential to become historical sources in their own right. Chabod (1969) once argued in his discussion of cinema and radio, such tools offer unparalleled insight into the mass psychology of their age.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In accordance with Chabod's logic, Digital History's Historiography asserts the indispensability of every computer, mainframe, software, operating system, programming language, website, email, instant message (via WhatsApp, Telegram, iMessage), AI platform, database and social media profile as a historical source for the narration of the history of digitality. These findings provide a clear foundation for the study of a new interactive system, a Big Data–based economy, the anthropology of cognitive transformation (Homo-Loggatus) (Spina 2023b), and the altered human perception of technological environments.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In this context, Computer Science becomes both a source and the sole tool capable of analysing itself. The employment of artificial intelligence (AI) will be essential for the archiving of instant messaging, the utilisation of data extraction tools for the analysis of websites, and the implementation of algorithms for the interpretation of technological records. The evolution of computing technology has transformed computers and code from mere instruments to vehicles for documenting human expression. As Giuseppe Galasso (2010) asserts, these phenomena necessitate adaptation by memory in response to the advancements in scientific knowledge.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
## Digital History as Methodology?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Turning now to the second scenario—the consideration of Digital History (DHy) as a purely methodological approach—the discussion necessarily returns to the role of technology and the real implications (both positive and negative) of its integration into the historical research workflow.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Despite the plethora of studies and the results published in various scholarly journals, the discourse on History—and thus on DHy—has not yet triggered a significant process of disciplinary innovation. The techniques and practices underlying the "craft of the historian" have remained largely unchanged. The outcome of academic debates and digital initiatives is a methodology that, despite being proclaimed as a novel perspective , still closely mirrors traditional approaches. Digital atlases and critical editions, for instance, still lack a truly computational dimension.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In essence, the field remains grounded in "close reading"—the foundation of conventional historical inquiry. The practice of historians engaging with archival documents by physical means, including reading, touching and analysing them, is a persistent endeavour. This approach is undertaken to extract information and resolve research questions. However, the majority of historical scholarship and interpretations of past events are still based on a limited (albeit representative) set of sources. The corpus of knowledge pertaining to pandemics, for instance, is predominantly derived from administrative documents. The present study is predicated on the recognition that there is an absence of first-hand testimonies from individuals who lived through these dramatic experiences. The capacity to comprehend the extent of their suffering is, by necessity, constrained by the limitations of analogy, a tool which Droysen (1868) contended was among the most efficacious interpretative instruments in the historian's armoury. The anthropological response of a community that has been struck by an event, documented through direct sources, is an exceedingly rare occurrence. Even our reconstructions—for example, Thucydides' account of the Plague of Athens—rely on narrative mediation. Literary works, such as Boccaccio's Decameron, similarly reflect the author's perspective rather than voices from within the affected communities.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Now, consider a research project, a day in the future, conducted by historians (digital or not) aiming to study and reconstruct the COVID-19 pandemic that struck the globe in 2019. These scholars would likely be seated at a computer, confronted by a vast array of online information, including social media posts, YouTube videos, and WhatsApp messages. These digital traces would become the "new" historical sources, used to document both governmental and individual responses. The utilisation of video recordings has the potential to offer insights into contentious issues pertaining to vaccines, as well as the conditions that prevail within hospital wards. Government websites may contain precise records of decrees, lockdown regulations, and the underlying rationales.
This naturally gives rise to complex issues surrounding the archiving of websites and data stored on institutional smartphones—presidents', governors', and ministers' devices—topics that demand broader reflection. However, in the event of the establishment of a future "archival order" for web-based documentation, the question arises as to how the historian's approach should be defined. The question arises as to whether this could still be classified as “close reading”.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The predominant perspective among digital historians is to characterise Digital Humanities (DH) as a series of methodologies that employ computational tools and the dissemination of information across the Internet—approaches frequently aligned with “distant reading”. In accordance with the aforementioned logic, historical research in a digital context should be characterised by "distance" due to the inexistence of tangible digital data, which instead exists as encoded, networked objects. This principle should arguably mark a key departure from traditional historical methodology.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The validity of this conclusion is questionable. This is improbable. It is important to note that even when sources are accessed via the internet or digitised, they are ultimately "interpreted" in the historian's mind. In this sense, Digital Humanities remains firmly anchored to the scholar's subjectivity, thereby rendering it a broader expression of close reading rather than a departure from it. The experience of reading "on screen" is not substantially different from reading in the archive. The core phase of historical research, namely analysis and interpretation, remains under the authority of the historian, who continues to extract meaning from documents and data.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The discussion becomes more nuanced when ICT (Information and Communication Technologies) is considered not merely as neutral tools, but as epistemological agents. It is evident that there is a deficiency in the philosophical discourse when the primary function of ICT is disregarded; namely, the facilitation of intellectual and reasoning activities. The World Wide Web, for instance, is not merely a portal to documents indexed by Google; it is a semantic infrastructure capable of linking data to provide increasingly detailed and coherent answers, a feat difficult to achieve through traditional methods. In the field of computer science, the web is regarded as a semantic space, conceived to interconnect information and return meaningful responses. However, when historians consult websites or digital libraries, they rarely exploit this potential.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The approach adopted by these scholars remains firmly anchored in the practice of meticulous textual analysis. The responsibility for this situation does not lie solely with the parties concerned. To date, approximately 92% of historical heritage remains undigitized, stored in the silence of archives. The knowledge that scholars accrue frequently remains confined to their personal desktops. Consequently, the application of innovative technologies to obtain meaningful insights about the past is rendered extremely difficult. Despite the extensive nature of these collections, they have not been examined from semantic or computational perspectives. Contemporary historians do not anticipate that technology will "perform" historical research. Nevertheless, a significant number of projects involving the collection of historical sources are labelled as DHy.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The majority of contemporary historians are engaged in the creation of datasets, the "invention of archives," and the aggregation of sources, practices that bear resemblance to Histoire sérielle. A distinctive feature of DHy is that ICT facilitates the collection of all sources in a single place (Itzcovich 1989), whether on a hard drive or in cloud storage. This prompts us to consider a fundamental question: who is responsible for the analysis of these datasets?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Information and Communication Technologies (ICTs) were originally conceived to facilitate human analytical processes, albeit in a mechanical sense and not yet in a semantic capacity. It is therefore reasonable to argue that historians' reasoning can be augmented by integrating computational tools and algorithms into the research workflow. These technologies have the capacity to facilitate the analysis of sources, the extraction of hidden information, and the provision of a multi-layered, alternative pathway through which historians may reconstruct past events.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Despite the simplicity of this premise, it gives rise to a number of concerns. Many historians continue to hold the conviction that no machine can surpass the human intellect, a belief that is not entirely unfounded. However, this assumption places digital historians in a liminal space between "History" and "non-History". The results of computational methods are frequently perceived as falling outside the domain of historiography, and digital historians are often derided as "clowns in regal purple" (Judt 1979).
It is evident that a significant challenge confronting traditional historians pertains to their inability to effectively navigate the digital landscape, thereby impeding the potential for a fruitful collaboration between the fields of computer science and history. The absence of mutual understanding in this interdisciplinary interplay serves to restrict possibilities, thereby hindering the formation of the "historian of tomorrow" as envisioned by Le Roy Ladurie (1968). Furthermore, the persistent reluctance to acknowledge the merits of quantitative methodologies or Histoire sérielle is noteworthy. However, as Daumard and Furet (1973) have observed, these methodologies have the potential to become powerful tools for the study of social and economic history. The application of computational methods to notarial records, for instance, has the potential to challenge long-standing historical narratives built on limited material, thereby revealing more complex and meaningful social landscapes.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Nevertheless, this very approach risks marginalising event-based historiography, which may struggle to justify the historical value of individual data points, thereby flattening singularities. The question thus arises as to whether a dataset would contain space for a "Menocchio," the miller studied by Ginzburg (1976). The question arises as to whether the cosmogonies of ordinary people would lose their historical significance, or whether they might, precisely because they belong to a "series," help uncover new visions of past life—ones that give equal narrative weight to the commoner and the king.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Adding to this complexity—perhaps the most significant critique levelled by traditional historians—is the fundamental question: can algorithms 'do' History?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Whilst a negative response might appear to be an appropriate course of action, the question demands a more nuanced analysis in light of the digital methodological paradigm and the recent advances in artificial intelligence. The fundamental premise of this inquiry is predicated on the primary function of computational technology, which is the analysis of data, the execution of tasks, and the delivery of results.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
At present, a significant proportion of the endeavours categorised as 'digital history' are concerned with the establishment of digital archives, interactive maps, databases, and websites that are designed to collate documentation pertaining to particular events or pivotal figures. Historians, for instance, may engage in the process of collecting, whereby analogue sources are converted into digital formats.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, in all these cases, the semantic layer is absent, and the interpretation of these (digital) documents is thus left entirely to the viewer or user.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Nevertheless, the challenge remains compelling. In the context of the preservation of complex documentary legacies in digital form, there is a clear need for a focus on codification. This involves the creation of collections that are easily accessible to both future historians and non-historians, particularly in an era where the internet is becoming the primary source of information. The fundamental question guiding this research is whether the digital texts being created today will be as effective in transmitting meaning as the prehistoric cave drawings were for researchers without digital tools.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The question of whether future historians will regard us as "historians" or merely as "collectors" is a pertinent one. The question arises as to whether they will interpret our historiography as a meaningful expression of our present—a present they seek to reconstruct and comprehend—or merely as a set of instructions for navigating websites replete with digitised documents? This raises the question of whether future historians, who are likely to be fully digital, will regard us as "ancestors" or "forerunners" of the digital historical craft.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Despite their appeal, digitisation projects have not modernised or "digitised" the work of historians. The methodology employed by these organisations remains anchored in an analogue model. Whilst the historical purpose of these projects is indisputable, the historiography—the interpretive framework that should accompany them—remains incomplete and is rarely grounded in a truly computational approach in which the computer becomes a genuine research ally.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
DHy occupies a wholly separate dimension—one that can be meaningfully attained only when methodological frameworks empower machines to execute analytical instructions, not merely in quantitative but also semantic terms. It is imperative to acknowledge the role of the computer as a tool capable of producing historical knowledge when discussing DH. Failure to do so not only entails a reluctance to embrace digital transformation, despite advocating for its potential and allocating resources to its development, but also highlights the profession's inability to modernise. This phenomenon elucidates the computational limitations of scholars, which engender their reluctance to adopt a transformation that would profoundly impact both the research workflow and the organisational structure of academic departments. Consequently, the "old model" of the historian might become obsolete in such a scenario.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
## Digital Historical Method
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
During the 13th International Congress of Historical Sciences in Moscow in 1970, a participant observed that the utilisation of computers by historians was not merely advantageous but would ultimately become indispensable within a few years (Itzcovich 1993). At the time, such a perspective was somewhat isolated, much like the unheeded suggestion by Emmanuel Le Roy Ladurie to introduce historians to computer science by incorporating it into university curricula. In the contemporary era, this state of affairs is no longer tenable. Nevertheless, discourse pertaining to computational languages and algorithmic thinking persists in its remote and inaccessible character. The paucity of training centres is a matter of concern, particularly given that the majority of students enrolled in the Humanities have no meaningful connection with computational systems, despite being born into the digital age.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Indeed, the convergence of History and Informatics has yet to yield the transformative outcomes once envisioned. In the majority of cases, the computer is regarded as a storage device or as a portal to online archival repositories. However, a computer is not inherently an archive; paradoxically, it becomes one only when filled with documents arranged in tree structures reminiscent of archival systems. It is important to note that this environment is not inherently a data-processing environment; however, it is transformed into such through the utilisation of software and algorithms. It is not, itself, a document, although it may be regarded as a source, as Labuda (1957) observed, when considered a "human creation" and thus a "psychotechnical document".
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
From a methodological perspective, however, the question remains: what characteristics must a computer possess to be considered a true "collaborator" in the context of historical research?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In contradistinction to other human inventions, which are generally limited to a single function or purpose, the computer operates across multiple domains simultaneously. For instance, it can control machinery while concurrently recording and analysing its output, thus managing both the mechanical process and the administrative accounting. This versatility positions the computer as a foundational technological system, underscoring the necessity of discipline-specific training for its effective use. In the domain of historical research, the identification of a computational paradigm that aligns with the specific epistemic and methodological demands of the discipline remains a formidable challenge. The computer is only capable of producing meaningful results when it is given clear and precise instructions.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
It is imperative to acknowledge that the adaptability inherent in Information and Communication Technologies (ICTs) does not supersede the foundational principle that machine-human communication is contingent upon the conversion of content into discrete, machine-readable formats. This necessitates a decoding of the historian's craft and its reconfiguration into a structured set of computational instructions. Furthermore, as in other research domains, the object of study must be accurately described to the machine—a task that is particularly challenging in the historical field. For instance, the machine must be made to "understand" that its subject is the human being, and that every historical "event" corresponds to an action initiated by an individual that had tangible repercussions on themselves and their community.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
As Ennals famously stated:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
> “If we want the computer to be useful to us in the study and teaching of History we will have to be prepared to tell it what it is that we do. Computers can follow the guidance of experts who have been prepared to describe the nature of their expertise. The computer itself is not the problem. Its use should be a consequence of the view that we take of our subject and the role that we assign to the computer as a powerful tool” (Ennals 1986, 13).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, achieving this objective necessitates a rigorous formalisation of historical documentation, particularly in contexts involving computational tools. In the absence of such formalisation, digital interventions risk producing results that are inadequate from a historiographical standpoint. Consequently, it is challenging to assert that historical methodology has been genuinely digitalised, or that the foundations of contemporary research projects are authentically "digital" in the sense of computationally derived methodologies.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Digital History demands an introspective effort by historians — one that embraces not only technical skills but also the epistemological and philosophical frameworks required for full integration into the Digital Ecological Niche (DEN). This concept encompasses the engagement with Digitality, the Homo-Logged-in, and the processes of digitisation and digital transformation. That is to say, it concerns systems capable of managing knowledge.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This new paradigm inevitably gives rise to fundamental questions regarding the conceptualisation of "Knowledge" (What is knowledge?) and "Reasoning" (How is knowledge attained?). The subject under discussion is, in essence, the design of Knowledge-Based Intelligence Systems. These issues become even more pressing in light of the most consequential computational innovation to date: generative Artificial Intelligence (AI).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
AI, as a technology, has a well-established history. The definition and architectural design of the subject are not novel. The intellectual underpinnings of this paradigm can be traced back to the 1950s, particularly with the seminal inquiry posed by Turing: The question of whether machines are capable of thought processes is a subject of considerable interest and debate within the field of artificial intelligence (Turing 1950). Subsequent to this, developments in the field of computer science and engineering have given rise to the creation of neural networks that emulate the structure and functionality of the human brain. These developments have been accompanied by the emergence of other forms of semantic computation, including deep learning and machine learning. At this pivotal moment, the course of Digitality was permanently altered, and despite their scepticism, historians could no longer deny that their discipline would eventually have to engage with this technology.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
It was Ennals who first attempted to sketch guidelines for adapting AI tools to historical inquiry, more than three decades after Turing. However, beyond quantitative approaches and the influence of "social mathematics" (Braudel 2003, 53), AI was not yet sufficiently developed to address the complexity of historical research. The digital revolution of the late 20th century thus failed to meet its ambitious goals, thereby deepening the epistemological divide between historians and the foundational philosophy of Computer Science.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In recent times, despite the historical reluctance to engage with digitalisation, historians have initiated the establishment of a more productive relationship with technology. This shift has been marked by the beginning of a "long acquisition phase", which has been characterised by the large-scale digitisation of paper-based archives and the construction of hypertexts (Aarseth 1997) and linked data frameworks designed to interconnect documents across the web.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This reconfiguration of historical sources demands two critical responses. On the one hand, it calls for an intensified process of formalisation, requiring historians to re-evaluate their understanding of sources and contextual information. Conversely, as Topolski contends, the utilisation of contextual metadata is imperative for the effective contextualisation of documents within their designated historical frameworks. In this scenario, digital historians must rely not only on intuition but also on structured epistemologies that can no longer be disregarded.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In this redesigned methodological landscape, the historical source no longer serves merely as a potential solution to the historian's interpretative puzzle. The significance of this paradigm is derived from its interconnectedness with other sources, within the overarching logic of Big Data. The digital source is intricately interwoven with a complex network of semantic relationships, thereby bestowing upon it an array of interpretive layers that extend beyond the confines of the historian's solitary reading. It is precisely as a "node" in a broader network of information that it acquires relevance and meaning, a fact that historians cannot afford to ignore.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
To reiterate the fundamental premise of this discourse, digital historians adopt a methodological approach that is predicated on formalisation, intending to ascertain and objectify the research workflow into discrete, structured phases. Each of these phases can be computationally modelled and, consequently, emulated by a machine.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
According to Ennals (1986), researchers have identified three key phases in the digital approach to historical inquiry. Firstly, intelligent information retrieval is employed. Secondly, modelling and simulation are used. Finally, explanation and advice are given (Ennals 1986, 14). The process of historiography involves the extraction, analysis, modelling and interpretation of data, which is then communicated to the academic community through the medium of an acceptable interpretive paradigm (Curry 1939). The objective is to construct a plausible, often quasi-objective narrative capable of addressing the core historical question underpinning the research project. In the context of digital environments, these stages—extraction, analysis and modelling—can be translated into prompts and executed by tools and algorithms.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
While such a statement may appear to reduce complexity, the underlying point is that certain aspects of human intellectual labour are, in fact, mechanical and repetitive. When historians seek to extract entities such as "persons" and "places" from historical documents, they first identify these elements through close reading and then record them in lists. The advent of personal computing saw the emergence of spreadsheets (e.g. Excel) as essential tools, allowing scholars not only to list these elements but also to visualise and explore relationships among them—hitherto unavailable capabilities. In this context, historians analyse documents to extract data points and explain the relationships among them.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In the contemporary era, the automation of these operations has become a prevalent practice. The utilisation of dedicated software facilitates the extraction, structuring, and interrelation of data with enhanced speed, precision, and analytical rigour. Named Entity Recognition (NER) tools, for instance, have been shown to facilitate these processes with greater efficiency than manual methods. These capabilities are well-known across both the humanities and the sciences.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Among the most powerful platforms for textual analysis, including historical texts, is Python (https://www.python.org). The versatility of this programming language is well established, yet a crucial gap remains in equipping humanists with the necessary training to use it effectively for specific tasks, such as entity extraction (Todorov, Colavizza, and 1st Workshop on Computational Humanities Research 2020; Dinarelli and Rosset 2012). As with all programming languages, Python demands specialised knowledge to ensure meaningful outcomes. Consequently, digital humanists, including historians, must acquire technical training. Proficiency in programming languages is not merely a technical skill, but a condition sine qua non for the digital historian. This view was prophetically expressed by Le Roy Ladurie (1968) in his seminal statement: “L'historien de demain sera programmeur ou ne sera pas”.
Nevertheless, this very requirement has long been a contributing factor to a schism between scholars who utilise traditional methods and those who employ digital methodologies in their historical research. In the contemporary era, the historian who peruses online archives to locate historical documents may be considered as a digital historian in a relatively narrow sense.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, this gap is increasingly being addressed by the development of generative AI and a new form of digital literacy. It is now possible for historians to receive training in two distinct areas. Firstly, they can be instructed in the construction of effective prompts for task-oriented machine execution. Secondly, they can be taught to generate Python code to carry out advanced tasks, such as data extraction and named entity recognition. The advent of tools such as ChatGPT has enabled historians to undertake entire analytical workflows autonomously, encompassing activities ranging from data extraction to network construction, visualisation, and the creation of interoperable Excel and CSV files, without the prerequisite of programming expertise (see figure 4). The true power of generative AI lies not merely in its ability to produce coherent text, but in its capacity to perform more advanced and meaningful tasks, including data analysis, pattern recognition and historical interpretation.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This technological evolution suggests a major epistemological shift: the digital historian is no longer defined exclusively by technical mastery but also by the ability to integrate digital processes into historical reasoning, interpretation, and methodological design.
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["From Python to the Graphical Network Representation"]}} slideshow={"slide_type": ""} tags=["figure-python-network-*"]
display(Image("./media/04a.png", width=1000))
display(Image("./media/04b.png", width=1000))

```

<!-- #region editable=true slideshow={"slide_type": ""} -->
The essay's central theme is the unfortunate incompleteness of the digital evolution of the historical profession. This discrepancy necessitates a reconfiguration of the concept of Digital History (DHy) to redirect the "discourse on History" and to restore the centrality of information technology within the historian–ICT relationship. The fundamental premise underlying this redefinition is the necessity to reaffirm the epistemic utility of digital technologies and to establish a renewed trust in computational tools. It is imperative to acknowledge that, at their current stage of development, these tools cannot be reasonably excluded from historical methodology.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
ICTs, and more specifically Artificial Intelligence (AI), have advanced significantly beyond the developmental stage they were at when Ennals wrote his influential work. It is evident that contemporary artificial intelligence (AI) systems have the capacity to provide effective assistance to historians in their scholarly endeavours, provided that historians themselves receive the requisite training to utilise these platforms appropriately. The historian is now charged with the responsibility of training AI systems to accurately execute all functions related to historical research.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
As Ennals poignantly stated, “The purpose of work in artificial intelligence is to extend our power of thinking and understanding” (Ennals 1986, 19). These words emphasise the imperative for historians to apply every available technology, technique, and form of knowledge to fulfil the ultimate objective of historical inquiry: the exploration of human thought through a research process that begins with the analysis of human action. Collingwood echoes this sentiment: 
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
> “Historical knowledge is the reenactment in the historian’s mind of the thought whose history he is studying.” For Collingwood, true history is the history of thought; “there are no mere ‘events’ in History: what is miscalled an ‘event’ is an action, and expresses some thought (intention, purpose) of its agent; the historian’s business is therefore to identify this thought” (Collingwood 1964).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
If this is indeed the purpose of historical research, then it becomes even more evident that a data-driven, statistical-analytical approach—capable of identifying the motivations behind human actions—can find its most powerful investigative instruments in ICTs and AI.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Consequently, historians must utilise digital tools and programming languages beyond a mere capacity for data collection, classification, and digital archiving, which now represent the linguistic common ground across the sciences. It is imperative that the collection and structuring of historical information is oriented towards enabling historians and AI systems that they train to approach the underlying reasons and thoughts that shape human experience.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Consequently, historians are required to develop AI systems capable of reasoning and generating outcomes in a manner comparable to that of human historians. This necessitates the development of complex historical ontologies, schemas, models, and domain-specific GPTs that, in the future, may facilitate AI to reach the same interpretive conclusions as a trained historian. The development of these ontologies and models must be undertaken under the direct supervision of historians, who are tasked with the translation of their methodological workflows into protocols that can be followed by machines. This process of training AI to apply the analogy of Droysen correctly (1868; 1994; Ries 2010) is of paramount importance. This is imperative to ensure that the accuracy of an event-driven approach and the explanation of historical facts are achieved through contextual analysis and an understanding of long-, medium-, and short-term historical processes.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Such training processes will prevent AI from generating outcomes based solely on the chronology of events—outcomes derived from its internal black-box processing—by encouraging instead the development of models capable of identifying the underlying motivations behind events and approximating the reasoning of historical actors.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Consequently, data stored in numerous digital databases must be enriched with semantic complexity, which serves as the substrate upon which AI computational processes must operate. Consequently, the "long acquisition phase" must commence from wholly distinct premises, chiefly, it must guarantee that AI attains comprehensive access to digitised documentation through a process that initiates with exhaustive digitisation, namely complete transcription. Subsequent to the completion of transcription, it is imperative to train AI to not only identify all entities present in the text, but also to extract meaning. This task cannot be fulfilled through recognition alone; rather, it necessitates deep interpretive structuring. At this juncture, the historian must assume a pivotal role: by formalising information, historians can create machine-readable documents and train AI systems to develop (through machine learning) the capacity to deduce meaning from them.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
As far as full transcription is concerned, modern Handwritten Text Recognition (HTR) technologies have proven capable of automating this process on large batches of archival documents. Today, historians can rely on platforms such as Transkribus (https://www.transkribus.org) (Kahle et al. 2017; Erwin 2020; Milioni 2020; Muehlberger et al. 2019; Spina 2023a) and eScriptorium (https://www.sofer.info), which allow the creation of complete digital copies of archival records.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
It is important to note, however, that the training of HTR models remains a highly non-trivial task and must be guided by precise scholarly criteria. The primary challenge resides in the necessity to develop increasingly sophisticated recognition models, a process which is contingent upon the active involvement of domain experts, including philologists, historians, linguists and paleographers. The effectiveness of training processes is directly proportional to the number and quality of transcriptions utilised. Within the Italian context, there is a striking absence of interest among the scholarly community in developing a model capable of recognising and transcribing the diverse array of archival documents produced across the peninsula. To date, there have been no large-scale projects aimed at improving transcription models or developing language resources in this direction. This methodological lag risks becoming irreparable.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Following the transcription phase, historians must then proceed to the "explanation" of the document, thereby enriching the digital edition with interpretive layers that extend far beyond basic tagging. At this critical juncture, there is a pressing need to understand the concept of knowledge representation, i.e. the principle that information must undergo a process of standardisation and formalisation (Spina 2024b) before it can be integrated into the digital ecological niche.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This is the issue that most urgently fuels our reflection, and that often drives the disillusionment of so-called "analogue" historians: the semantic dimension and the problem of interpretation.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The following research questions have been identified: firstly, how can we train AI in semantics, and, more crucially, how can we formalise the meanings of History?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
While Fernand Braudel emphasised the potential of applying methodologies from Social Mathematics—such as statistical analysis—and Richard Ennals encouraged historians to explore simulation as a means to extract and model "typical behaviours," computer scientists were simultaneously enhancing the capabilities of artificial intelligence (AI). Artificial intelligence has been conceptualised as the pinnacle of computational tools. It has been argued that this has resulted in the validation of ideas that were previously considered visionary. In the contemporary era, these technologies possess functionalities that have the potential to elevate historical research to a radically innovative level. The sole remaining challenge pertains to the surmounting of the complexity that McCarthy and colleagues had previously identified in their 1955 proposal:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
> “The speeds and memory capacities of present computers may be insufficient to simulate many of the higher functions of the human brain, but the major obstacle is not lack of machine capacity, but our inability to write programs taking full advantage of what we have” (McCarthy et al. 1955).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In the context of historical research, there is an absence of AI systems that have been expressly designed for this purpose. The preponderance of AI technologies presently in existence incorporates functionalities that have been adapted for historical purposes, including text processing, linguistic analysis, entity recognition, and topic detection. These functionalities have their origins in the domain of computational linguistics and are presently utilised by historians, predominantly within the non-interpretive phases of their workflow. In the absence of AI tools capable of supporting the full complexity of historical inquiry, historians are left with no option but to go beyond this threshold. It is therefore essential to "explain" to the machine what historical work entails, granting it access to the full spectrum of information—historiographical narratives and archival documentation—that human historians rely upon, and then instructing it in how to perform the core practices of the craft.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
An initial step in this direction might be to revisit Social Mathematics, which enables historians to work not on numbers per se, but on relationships (edges), that is, defined relational links. It is imperative that these signs are constructed with meticulous care to ensure that they can be interpreted with clarity and precision. The validity of any interpretive conclusions is contingent on the quality of these signs. This preliminary phase enables historians to distinguish the fundamental relational components and ascertain the social, political, or cultural connections between historical actors.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The subsequent stage of the research would be to simulate historical conditions, identify the actions performed by individuals, and determine what motivations guided them. In this respect, historians enjoy a crucial advantage over scholars in the natural sciences. While the exact intentions of historical actors may be unknown, the results of their actions are fixed and observable. Historians are able to commence their research with the advantage of hindsight, being cognisant of the sequence of events, how these events transpired, and the eventual outcomes that ensued. If this scenario were to be described in formal, logical terms, the following formulation might be employed:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
K(C) ∧ K(R) ∧ ¬K(M)
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
That is (ossia K(φ)) , the historian knows the initial conditions (C) and the result (R) but does not know the motivations or mental processes (M) that produced the chain  of events. In computational terms, the advantage of knowing R, coupled with the structured encoding of C, allows for the potential inference—based on probabilistic models and historical patterns—of the intentions (M) that led to specific actions. Once inferred, these inferred motivations further refine the model, consistent with the principles of machine learning (Alpaydin 2020; Bishop 2006; De Mauro 2019; Gori 2018).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Yet this formula demands further qualification. Since historians often know only a portion of the initial conditions, the framework of certainty must be adjusted to reflect this partial knowledge. We therefore introduce a function Csub(p, a), which expresses the known subset of the initial conditions:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
K(Csub) ∧ ¬K(C) ∧ K(R) ∧ ¬K(M)
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This yields a more complex structure:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
∀p∀a { A(p, a) → [K(Csub(p, a)) ∧ ¬K(Ctot(p, a)) ∧ K(Res(p, a)) ∧ ¬K(Mot(p, a))] }
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Where:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
- Csub(p, a) denotes the known part of the initial conditions;
- Ctot(p, a) represents the total set of initial conditions (which remain partially unknown);
- K[Res(p, a)] confirms that the result is known;
- ¬K[Mot(p, a)] indicates that the motivations remain unknown.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In sum, it can be posited that for each individual and each action, only a proportion of the initial conditions is known. The outcome is known, but the motivations remain obscure.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In this context, AI can provide historians with a virtual laboratory in which events can be reconstructed from the actors' perspective and historical data can be encoded and objectified for use in computational processes that increasingly approximate the explanatory power of human interpretation.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The training to which the machine must be subjected should follow the guiding principle articulated by Collingwood:
“For History, the object to be discovered is not the mere event, but the thought expressed in it. To discover that thought is already to understand it. What are the rules for acting in this kind of situation? If you want to know why a certain kind of thing happened in a certain case, you must ask, ‘What did you expect?’. You must consider what the normal development is in cases of that kind. Only then, if the thing that happened in this case was exceptional, should you try to explain it by appeal to exceptional conditions” (Collingwood 1964).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
To approximate such interpretive reasoning, historians must encode patterns of “normal” historical development and instruct AI systems on how to distinguish between expected and exceptional outcomes. In doing so, they would equip AI not merely with the ability to process data, but with the epistemological framework necessary to engage in historical reasoning.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Consequently, historians are tasked with the responsibility of constructing and refining models that facilitate the identification of the underlying motivations behind human actions by artificial intelligence systems. These models also serve to provide interpretive frameworks for these actions. This process enables historians to evaluate the various conclusions that may be drawn from their research. This is based on the premise that AI has the capacity to elucidate why one explanatory "reason" is more plausible than another. This is derived from contextual and semantic analysis.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In order to provide a concrete example, the following discussion will draw upon a common historical source: a deed of sale. This particular document is designed to formalise the transaction whereby one individual sells an asset to another. The information it contains is explicit and seemingly self-explanatory. The two parties involved are defined as the seller and the buyer. The place where the act was signed is also specified, as is a specific date. The seller received a sum of money, and the buyer acquired ownership of the item or property in question.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Now, imagine applying the journalistic “Five Ws” framework:
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
- Who? The buyer and the seller.
- What? A sale transaction.
- When? A date in the past.
- Where? A specific place in the world.
- Why? … But why?
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The first four "Ws" (Who, What, When, Where) facilitate the construction of a concise and objective narrative of a historical event, a task that can now be fully replicated in a digital environment. It is possible to train AI to identify and respond to the aforementioned four questions by extracting entities, dates, and locations and assigning roles, meanings, and correlations. This process gives rise to the development of relational networks with the capacity to "visualise" the data associated with individuals and their actions. It is important to note that this process initiates a network analysis (Wetherell 1998; Spina 2022), the primary objective of which is to delineate the objective framework upon which historical interpretation is to be built. As illustrated in Figure 5, ChatGPT-4.0 was prompted to generate a network diagram that would illustrate the connections between individuals, places and events during the French Revolution.
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["Network graph of the French Revolution"]}} slideshow={"slide_type": ""} tags=["figure-network-revolution-*"]
display(Image("./media/05a.png", width=1000))
display(Image("./media/05b.png", width=1000))
display(Image("./media/05c.png", width=1000))

```

<!-- #region editable=true slideshow={"slide_type": ""} -->
It is evident that software such as Python is already capable of performing this type of analysis; however, Large Language Models (LLMs) have the potential to accomplish this task with even greater efficacy. The employment of targeted prompts has been demonstrated to enhance the model's capacity to extract entities and retrieve a more extensive array of relevant data, a feat attributable to its distinctive computational configuration.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This is precisely why LLMs are regarded as among the most powerful allies in historical research today. They can assist in the structuring of prompts, the organisation of data, the generation of datasets, and the writing of custom scripts (e.g., in Python) to process and analyse that data. Furthermore, it is possible to request that AI explain an event based on historical information retrieved online, even in cases where the internet does not yet offer a robust or comprehensive historical corpus.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The training of AI models is currently undertaken on Wikipedia and other websites that permit access to their repositories. However, there is a paucity of access to archival collections and scholarly historiography, the majority of which is protected by copyright and therefore not accessible via the open web. It is evident that even open-access historical research remains "invisible" to the majority of AI systems. This is due to the fact that these models are unable to access journal repositories, perform file downloads, or "read" full texts in any meaningful way.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
To illustrate this point, consider the following example: in 1782, Michele Maria Paternò, Prior of Messina, wrote a letter to Anna Maria Morso Bonanno, Princess of Biscari, in which he mentioned that the Emperor of Austria had instructed the Pope to suspend his journey through the Holy Roman Empire due to a revolt in Vienna (Spina 2024a). This prompts the historian to pose the following question: Why was the Pope travelling through the Empire? We requested that ChatGPT collate all extant data that could facilitate the reconstruction of the context (see figure 6).
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["The History of Europe in the black box"]}} slideshow={"slide_type": ""} tags=["figure-history-blackbox-*"]
display(Image("./media/06.png", width=1000))
```

<!-- #region editable=true slideshow={"slide_type": ""} -->
Utilising its web browsing function, ChatGPT directed us to two websites containing extensive contextual information, which revealed that the Pope's journey was linked to his efforts to counteract the Emperor's religious reforms within his territories. The underlying rationale for this phenomenon is elucidated therein.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The deed of sale will now be revisited. The rationale behind the transaction, whereby property owner A sold their property to property owner B, is a key question to address. The motivation behind person B's decision to acquire it is a subject that merits further investigation. The only method by which to approach such inquiries is to pose them explicitly. Collingwood (1964) emphasised the pivotal role of inquiry in historical research, characterising it as "the prevailing factor in History, as it is in all scientific endeavours," advancing the concept that historians engage with sources from a position of critical inquiry, having already determined the objective of their investigation.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Unfortunately, it is not possible to interrogate historical actors from centuries or millennia past. The objective is to locate documents signed by the relevant individuals, which may include information pertaining to their financial condition or motivations. In contradistinction to the case of Pope Pius VI, it is exceedingly difficult to ascertain the motivations behind private notarial acts.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In order to address such impasses, traditional methodology—following Droysen—has long relied on the application of analogy as a means to reconstruct plausible motivations based on similar events for which reasons are explicitly documented. This enables the historian to formulate a "reasonable description" of a novel occurrence. Consequently, our understanding of the past is fundamentally derived from reconstructions that are, in essence, reasonable descriptions. Consequently, what is reasonable, in turn, can be formalised, encoded, and computerised — thereby providing a dataset from which AI can learn.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The advent of ICTs has enabled historians to operate within a simulated environment, wherein they are able to hypothesise behaviours that would render certain actions more or less probable. By employing simulation in lieu of analogy, it may be possible to identify the most probable rationale behind an event.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In instances where primary sources do not disclose the motivations behind a particular action, historians may resort to logical reconstructions of the event. For instance, what are the factors that motivate individuals to establish churches? The preponderant response, as deduced via the "analogical approach", is of a religious or pastoral nature (cf. Figures 7–8).
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["Query on the foundation of churches"]}} slideshow={"slide_type": ""} tags=["figure-query-churches-*"]
display(Image("./media/07.png", width=1000))
```

```python editable=true jdh={"object": {"source": ["The outcome of the ChatGPT IA 4"]}} slideshow={"slide_type": ""} tags=["figure-outcome-chatgpt-*"]
display(Image("./media/08.png", width=1000))
```

<!-- #region editable=true slideshow={"slide_type": ""} -->
This approach, situated at the intersection of semantic formalisation and logical modelling, points towards a new horizon in Digital History. In this new paradigm, historians will no longer merely curate sources; rather, they will also code motivations, reconstruct context, and train AI systems to engage in interpretive historical reasoning.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, there exist numerous other motivations that must be encoded and employed to train AI models to allow them, within simulated environments, to identify alternative contexts and prompt historians to explore different interpretive pathways. In the present illustrative case, it is evident that AI currently lacks the data necessary to enumerate the economic motives behind the establishment of religious institutions. For instance, consider the establishment of the Church of the Holy Letter (Chiesa della Sacra Lettera) in Riposto (Italy, Sicily, in the province of Catania). This was not only established for devotional purposes, but also to enable agricultural workers (coloni) from the surrounding hinterland to settle permanently in the area and give rise to a new urban community (Amico e Statella 1757). The founder, Giovanni Calì, was the proprietor of numerous plots of land cultivated by these workers and had a vested interest in their continued presence. The "logical" solution, therefore, was to provide them with access to sacraments (Spina 2011).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The utilisation of TensorFlow has facilitated the codification and integration of such information into the training phase of AI systems, thereby enabling them to enhance their analytical capabilities and identify those aspects that are indispensable for historical research, which extend beyond simple inferential reasoning (e.g., church foundation = devotion) (Fig. 9).
<!-- #endregion -->

<!-- #region editable=true jdh={"object": {"source": ["Training with TensorFlow on the reasons for founding churches"]}} slideshow={"slide_type": ""} tags=["figure-tensorflow-churches-*"] -->
display(Image("./media/07.png", width=1000))
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In all cases, what historians require is an AI platform that has been trained to think and act like a historian. That is to say, an AI that recognises human beings as the sole proper subject of history, a discipline founded upon the axiom that every event originates from an action, and each action must be attributed to a subject, even in the case of collective agency. It is evident that phenomena such as crime and political parties do not exist in abstracto; rather, they are defined by specific individuals whose decisions and actions shape them. This suggests that in order to train a model on the phenomenon of criminality, it is necessary to encode the criminal behaviours of each actor. It is not possible to digitise a phenomenon in the absence of a comprehensive process that encompasses all relevant data, which might be termed the 'Big Data' of the phenomenon.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Similarly, the digitisation of the history of Communism would necessitate the encoding of the actions and decisions of figures such as Lenin, Stalin, Chernenko, Gorbachev, and Castro. The digitisation of the history of urban planning would require the formalisation of the theories of the scholars who defined its disciplinary parameters. The composition of a historical account of a city necessitates the digital representation of the lives of the individuals who physically constructed it. The examples could be continued ad infinitum.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
As early as 1975, Jerzy Topolski recognised that the analysis of the consequences of action was the only reliable tool available to traditional historians for understanding the motivations of historical actors. The definition of an event is predicated on the occurrence of that event. For Topolski, however, an event is not necessarily linked to the personal motivations or circumstances of its participants, since its occurrence is, first and foremost, a matter of objectified reality. Nevertheless, it engenders consequences—effects—that, while not necessarily causally determined, allow for retrospective identification of motives embedded in those effects.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Donald Davidson (1968; 1976) articulated a closely aligned philosophical position, maintaining that "a reason rationalises an action only if it leads us to see something the agent saw, or thought he saw, in his action—some feature, consequence or aspect of the action the agent wanted, desired, prized, held dear, thought dutiful, beneficial, obligatory or agreeable" (Davidson 1968, 79). However, Davidson cautions against misinterpreting pattern recognition as a true explanation.
<!-- #endregion -->

<!-- #region editable=true raw_mimetype="" slideshow={"slide_type": ""} -->
> “It is an error to think that, because placing the action in a larger pattern explains it, therefore we now understand the sort of explanation involved. Talk of patterns and contexts does not answer the question of how reasons explain actions, since the relevant pattern or context contains both reason and action” (Davidson 1968, 89).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Therefore, an event may be defined as the result of a series of causes and circumstances which subsequently lead to a specific outcome. This outcome is then investigated by historians. To illustrate this point, one may consider the consequences that would have ensued had Napoleon's coup against the Directory failed and the Consulate had never been established. In such a scenario, historians would be discussing the alternative consequences and the factors that led to them, rather than the formation of the Consulate.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In this context, it can be argued that every event, irrespective of the absence of explicit documentation, represents an articulation of rationality. This reflection is foundational for the integration of AI into historical inquiry: with adequate training, AI systems should evolve beyond simple data collection and analysis, towards interpretive reasoning. Digital historians are required to embody innovation in the profession, in contrast to their analogue counterparts.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This perspective is neither utopian nor sterile; it is grounded in the intrinsic potential of AI and, more importantly, in the nature of historical knowledge itself, which may be conceived as a complex dataset suitable for training generative AI systems.
History is predicated on explanation. In order to provide an answer to the question "Why did this happen?", historians rely on certain reasonable, objective, and verifiable facts. For instance, when analysing Luther's concept of predestination—particularly in his treatise De Servo Arbitrio—historians must consider the significant impact of Augustinian theology. In the context of his opposition to the doctrine of Pelagius, Augustine had ruled out the possibility of human self-redemption. A millennium later, Luther reaffirmed the centrality of predestination, having been intellectually shaped by that same theological tradition.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In the context of computational analysis, the investigation of Luther's concept of predestination necessitates the incorporation of several pivotal elements. These include the formative context, the definition of the concept itself, and, most notably, the historically irrefutable fact that Luther was the author of De Servo Arbitrio. These objective premises form the basis for referring to Luther as an "Augustinian monk," despite his temporal distance from Augustine.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
It is posited that, with the requisite training, an AI system endowed with the aforementioned facts could respond effectively to questions regarding Luther. Of greater significance is the potential for the development of a coherent analytical framework, which would facilitate engagement with analogous interpretive inquiries.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This premise is analogous to Topolski's inquiry: The question is posed as to whether an understanding of the past necessitates its explanation. The author's objective was to shift the focus from "understanding History" to History as an explanation, thereby positioning historians as observers incapable of discerning the innermost intentions of historical agents. This, in turn, limits historians to uncovering causes and describing them.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, in an era of increasing interconnectedness, it is possible to provide a more precise explanation of the underlying motivations. It is evident that generative AI systems, in virtue of their architectural design, possess the capacity to establish an analytical bridge between extrospective and introspective reasoning. As Nowak (1965) contends, the comprehension of an occurrence may be predicated on the identification of conscious, intentional behaviours, which are indicative of psychological states. It is conceivable that, with sufficient training, an AI could acquire this introspective dimension, which historians already utilise intuitively and which is widely applied in disciplines such as economics, where the psychological profiling of consumer groups guides market strategies.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The establishment of such a framework would facilitate the construction of ontologies and models upon which AI could develop historical explanations that transcend static conceptions of human nature.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In this scenario, the task of explaining events—that is, the enduring traces of human activity, whether individual or collective—requires historians to assume the role of interpreters of the psychological states of historical actors. This necessitates not only the analysis and reconstruction of external factors but also the translation of internal human processes into ontologies and formal models, through which AI can be enhanced. In this conceptualisation, historians assume the role of active architects in the development of the Human Digital Twin process, which entails the codification of "the inner state of humans" (Okegbile, Cai, and Yi 2024; Gräßler et al. 2023).
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
This paradigm shift, in the field of Digital History, and the training of digital historians, signifies a transition from a focus on data accumulation to a novel interpretation of the historian's craft, which must embrace the concept that historical research is a dynamic flow of data and meaning, which demands new semantics. This has attracted the attention of AI developers.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
# A Conclusion Framed as Perspective and Invitation
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
On 12 September 2024, the world's leading artificial intelligence company introduced ChatGPT-o1—now evolved into the "o3-mini" version—a suite of GPT-based models designed to enhance cognitive processing and enable more "reasoned" responses (OpenAI 2024). The objective of this latest release is to construct AI systems around a "futuristic" hypothesis: namely, that artificial intelligence can "reason... in ways analogous to human thinking... to solve more complex problems" (Fig. 10). Even though the term 'futuristic' may not be the most accurate, within the context of the Digital Ecological Niche (NED), it signifies not merely a projection, but a concrete direction that is actively pursued and methodically realised.
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["ChatGPT-1o Reasoning perspective"]}} raw_mimetype="" slideshow={"slide_type": ""} tags=["figure-chatgpt-reasoning-*"]
display(Image("./media/10.png", width=1000))
```

<!-- #region editable=true slideshow={"slide_type": ""} -->
The future is now. The next generation of scholars will be inherently digital and in constant dialogue with these cognitive allies. However, the methodology employed and the relationship with the historical discipline are contingent on the epistemic frameworks that are constructed in the present moment. This is a period of irreversible transformation, akin to scholarly inquiry.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
As OpenAI has observed, the model exhibits performance that is commensurate with that of PhD students across a range of benchmark tasks in the domains of physics, chemistry and biology. Evidence has demonstrated a high level of aptitude in mathematics and coding. In a qualifying round for the International Mathematical Olympiad (IMO), GPT-4o achieved a 13% success rate, while a dedicated reasoning model attained 83%. In the context of competitive coding tasks, it attained an 89th percentile ranking in Codeforces challenges (see Figure 11).
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["ChatGPT-1o tables and percentages"]}} raw_mimetype="" slideshow={"slide_type": ""} tags=["figure-chatgpt-tables-*"]
display(Image("./media/11a.png", width=1000))
display(Image("./media/11b.png", width=1000))

```

<!-- #region editable=true slideshow={"slide_type": ""} -->
A comparison of the “o1 version” with GPT-4o reveals that the former outperforms the latter on 54 out of 57 MMLU benchmarks, particularly in subcategories such as Global Facts, Chemistry, Mathematics, Law, Public Relations, Econometrics, and Formal Logic. However, one might also pose the question of the role of History within this landscape. The absence of historians from this discourse is glaring. The reasons for this reluctance to engage in collaboration with the fields of Computer Science and software development remain unclear. The reluctance to contribute to the creation of models, GPTs and ontologies capable of capturing the nuances of human behaviour is a matter of concern.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
It is evident that to achieve optimal functionality, artificial intelligence must be endowed with a comprehensive database of human actions. This database must encompass the various meanings attributed to such actions, the underlying motivations that guide their performance, and the historical contexts within which they are situated. The database should span the entire spectrum of human history, extending from antiquity to the present era. It is imperative to liberate the concept of History from the outdated assumption that it is intrinsically incompatible with psychological inquiry. This shift would facilitate the development of conceptual frameworks to enhance historical research and foster the emergence of more sophisticated explanatory models.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, this vision necessitates a fundamental reevaluation. Digital History (DHy) must align with the data-driven epistemologies of computational sciences. The full extent of its revolutionary potential remains to be realised within the historical community. Whilst the advent of digitisation and the concomitant proliferation of digital archives have undeniably resulted in enhanced access to a plethora of sources, such initiatives nevertheless frequently fail to leverage the full analytical capacities of digital technologies. It is imperative that historians adapt to technological transformation by acquiring the necessary competencies and rethinking traditional methodologies.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Standardisation and semantic enrichment of historical documentation are imperative. In order to achieve this, it is necessary for historians and technologists to collaborate actively to design ontologies, models and AI systems capable of replicating key aspects of historical reasoning. These aspects include, but are not limited to, Droysen's concept of analogy, contextual analysis and long-term temporal processes.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The capacity for AI to engage in sequential reasoning, termed "chains of thought", has been demonstrated. This cognitive architecture mirrors human problem-solving and decision-making processes. In large language models (LLMs), a thought process is constituted by a sequence of intermediate steps that connect an input to an output, thereby enhancing interpretability and accuracy. Cognitive science demonstrates that humans frequently disaggregate complex problems into smaller, more manageable sub-tasks. This sequential reasoning facilitates thorough analysis and reduces cognitive load.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The integration of this process into LLMs facilitates their ability to perform multi-step reasoning, encompassing mathematical calculations, logical inference, and contextual understanding. The "chain of thought" structure has been demonstrated to improve reasoning abilities by accounting for every step in the problem-solving process (1), enhance interpretability by providing insight into the model's decision-making (2), and reduce error rates by promoting a methodical, layered approach to analysis (3).
Undeniably, both the historian and the developer face considerable challenges, and long-term collaboration will be paramount. ChatGPT is a remarkable AI system; however, as of its knowledge cut-off in October 2023, it has not been trained on any historically significant corpora. Despite incorporating data from academic articles, books, and encyclopedias, its access to primary source materials and historiographical discourse remains limited.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, with comprehensive training, AI could offer explanations of historical events, figures, and trends that are increasingly nuanced, synthesising vast amounts of information. Its capacity to contextualise cultural, political, economic, and social factors could enable more sophisticated analyses and comparative insights across historical epochs. The multilingual capabilities of the inquiry further enhance its global scope.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Nevertheless, current limitations persist. It is important to note that AI is unable to access real-time data, nor can it incorporate research published after October 2023. The capacity to conduct original research and generate primary data is absent, with the functionality being confined to the materials contained within its training corpus. Consequently, there is a possibility of persistent gaps and inaccuracies. However, when prompted to provide a detailed account of Napoleon Bonaparte's rise and fall, ChatGPT is capable of producing a comprehensive chain-of-thought analysis, illustrating how interconnected decisions, external reactions, and unintended consequences shaped his fate (see Figures 12–13).
<!-- #endregion -->

```python editable=true jdh={"object": {"source": ["Chain-of-thought preliminary process"]}} raw_mimetype="" slideshow={"slide_type": ""} tags=["figure-chain-process-*"]
display(Image("./media/12.png", width=1000))

```

```python editable=true jdh={"object": {"source": ["Chain-of-thought outcome"]}} raw_mimetype="" slideshow={"slide_type": ""} tags=["figure-chain-outcome-*"]
display(Image("./media/13a.png", width=1000))
display(Image("./media/13b.png", width=1000))
```

<!-- #region editable=true slideshow={"slide_type": ""} -->
This approach sheds light on the potential of AI to model "historical causality" and to offer nuanced insights into leadership, modern statecraft, and the contingencies of power.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
The fundamental challenge confronting historians is to devise methodologies that enable machines to "think historically." This necessitates the development of complex datasets and interpretive models capable of revealing insights that may elude traditional methods. The integration of AI into historical research should not be conceived as a replacement for the human scholar's judgment; rather, it should be regarded as a means of augmenting interpretive capacity through the application of tools that are capable of managing vast quantities of data.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In this sense, DHy is not merely a method for preservation or dissemination; it is a laboratory for methodological innovation. Historians must therefore overcome resistance to change and embrace interdisciplinary collaboration. It is only through engagement with computer scientists that we can develop GPTs that are aligned with the integrity and rigour of historical inquiry.
Consequently, academic programmes must be reimagined to incorporate advanced digital and computational competencies. Scholars must develop the ability to communicate with machines in a manner that is specific to their respective domains of expertise. This is necessary for them to function effectively within the context of a technological landscape that is in a state of constant evolution.
This transformation also necessitates ethical reflection with regard to data stewardship, source representativeness, and information accessibility. It is incumbent upon historians to ensure that digital technologies do not perpetuate historical bias or inequality; rather, they should promote more inclusive understandings of the past. The overarching principles guiding this endeavour must be transparency in analytical processes and awareness of methodological consequences.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
A further consideration is the function of digital sources themselves. It is important to note that not all historical knowledge exists in digital form. This phenomenon gives rise to interpretative discrepancies, which may potentially compromise the accuracy of the results. In order to achieve a comprehensive methodology, it is imperative to incorporate both digital and analogue sources. The issue of source representativeness is inextricably linked to the problem of algorithmic bias. The efficacy of AI is contingent upon the quality of the training data to which it is exposed. In the event of incomplete or historically biased data, the model's outputs will also be incomplete and biased.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Interdisciplinary collaboration is therefore not a matter of choice; it is an essential component of academic practice. The establishment of productive dialogue and shared vocabulary between historians and technologists is of crucial importance for the development of common ground. It is imperative that academic curricula undergo restructuring to reflect this new reality, with a view to equipping students with the skills necessary to operate as digital historians.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
It is imperative to emphasise that this does not entail the disregard of the foundational principles that underpin historical scholarship. Instead, it necessitates the integration of novel tools that broaden the scope of interpretation and research, aligning with established historiographical standards.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Furthermore, DHy possesses the capacity to appeal to a broader audience. Digital tools have rendered historical knowledge more accessible and interactive through various means, including platforms, visualisations, and multimedia. This democratisation has the potential to enhance public understanding and strengthen the relationship between historians and society.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
Notwithstanding the challenges encountered, the potential of DHy is considerable. It is now possible for historians to pose research questions that were previously unanswerable. To illustrate this point, consider the analysis of historical Big Data, which has the capacity to reveal large-scale patterns and long-term processes (Kaplan and di Lenardo 2017). Machine learning has been demonstrated to reveal latent correlations between events and actors that may not be apparent to traditional methods.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
However, it must be noted that digital technologies are not a panacea. The utilisation of these sources must be of paramount importance, exhibiting a critical nature and demonstrating a capacity for integrative analysis, guided by the discernment of the historian. Technology is a means to facilitate historical thinking, rather than a substitute for it.
<!-- #endregion -->

<!-- #region editable=true slideshow={"slide_type": ""} -->
In conclusion, Digital History demands that historians face a frontier that calls for both courage and innovation. This development signifies a methodological leap, traversing the domains of AI, data, and algorithmic systems, while maintaining fidelity to the core task of the discipline: the narration, interpretation, and explanation of phenomena. In the contemporary era, characterised by the integration of Information and Communication Technologies (ICTs) into historical sources, the Digital Ecological Niche emerges as both an object of study and a milieu for inquiry. This is not merely a response to digital transformation; it is a historiographical imperative.
<!-- #endregion -->
