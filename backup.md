# Learner corpora Bolo 2025

## Alla scoperta dei learner corpora

**Corpus**

Autentico: it’s language produced by humans!! (actually, not only humans...) in real-world environments (either naturalistic settings or examination settings). Perché non synthetic data? perché vogliamo capire che cosa fanno veramente le persone quando usano la lingua.

Un corpus è una raccolta di campioni di lingua rappresentativi della lingua o varietà che si sta studiando (questo implica che la raccolta sia abbastanza grande). Perché dev’essere rappresentativo?

* dai campioni che studi puoi generalizzare alla popolazione e quindi puoi dire qualcosa non solo su i tuoi campioni di lingua ma sull’intera lingua o varietà. Cautions with learner corpora… 
* per fare queste “inferenze” dal campione alla popolazione uso la statistica!

As a consequence of being representative (e quindi fairly large)... machine readable! I cannot go through it linearly (or at least is very time consuming) e quindi ho bisogno di tools to access and consult it.\
A corpus is also usually annotated to enhance potential for linguistic analysis… es. PoS tagging!\
(cf. Stefanowitsch, 2020)

>[!NOTE]
> Excursus su i formati: formato più semplice plain txt, ma se voglio avere la possibilità di cercare qualcosa di più che una parola, allora devo usare annotazioni multilivello. Si usano formati strutturati (es. xml, conllu, vert, etc).

**Tabella 1**

| Nome del corpus | Disponibile? Dove?                                         | Modalità (scritta, orale o entrambe?) | Metadati (es. L1, CEFR, nazionalità, etc.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Annotazioni (lemma, pos, dependencies, target hypothesis, errori)                                                   |                                                                                                                                                                    |
|-----------------|------------------------------------------------------------|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| VALICO          | http://www.valico.org/valico.html                          | Scritta                               | provenienza (luogo della scuola, probabilmente),<br>tipo scuola,<br>nome scuola,<br>data,<br>consegna (task),<br>scolarizzazione,<br>permanenza (anni in Italia e dove?),<br>lingue conosciute,<br>lingua madre,<br>annualità (?),<br>età,<br>specifiche (=genere)                                                                                                                                                                                                                                                                                                                                                                                               | lemma,<br>pos,<br>correzioni inline                                                                                       |                                                                                                                                                                    |
| LIPS            | https://parlaritaliano.studiumdipsum.it/it/653-corpus-lips | Orale                                 | matricola,<br>anno esame,<br>mese esame,<br>livello esame,<br>sede esame,<br>numero esami svolti dallo stesso candidato,<br>numero evento comunicativo (?),<br>argomento del testo,<br>genere testuale                                                                                                                                                                                                                                                                                                                                                                                                                                                  | lemma (con polirematiche),<br>pos (ma non disponibili, solo disponibili le trascrizioni)                               |                                                                                                                                                                    |
| CELI            | https://lt.eurac.edu/cqpweb/                               | Scritta                               | age group,<br>cefr,<br>exam centre location,<br>task,<br>nationality,<br>sex,<br>genre,<br>type (text type: argomentativo, descrittivo, etc.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | lemma,<br>pos                                                                                                          |                                                                                                                                                                    |
| COLI            | https://lt.eurac.edu/cqpweb/                               | Entrambe                              | età,<br>cefr,<br>sesso,<br>task,<br>tipo di testo (parlato o scritto)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | lemma,<br>pos                                                                                                          |                                                                                                                                                                    |
| LOCCLI          | https://lt.eurac.edu/cqpweb/                               | Scritta                               | age,<br>cefr,<br>composition,<br>point in time (longitudinal!!),<br>sex                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | lemma,<br>pos                                                                                                          |                                                                                                                                                                    |
| LEONIDE         | https://www.porta.eurac.edu/lci/leonide/                   | Scritta                               | author_L1,<br>author_age_at_production,<br>author_complete_DE,<br>author_complete_EN,<br>author_complete_IT,<br>author_complete_opinion,<br>author_complete_picture,<br>author_complete_texts,<br>author_gender,<br>author_id,<br>author_multiple_L1,<br>author_participation_y1,<br>author_participation_y2,<br>author_participation_y3,<br>author_special_needs,<br>author_years_in_project,<br>(longitudinal!!)corpus,<br>school_class_id,<br>school_grade_level,<br>school_language,<br>task_id,<br>task_type,<br>task_year,<br>text_id,<br>text_language,<br>time_of_data_collection                                                                                                                                             | ambiguous_alt_1,<br>ambiguous_alt_2,<br>foreign_word,<br>lemma,<br>original,<br>page,<br>paragraph,<br>pos,<br>pos_ud,<br>sentence,<br>target,<br>transcription |                                                                                                                                                                    |
| KOLIPSI (2)     | https://www.porta.eurac.edu/lci/kolipsi-family/            | Scritta                               | author_id,<br>author_gender,<br>author_socioeconomic_status,<br>author_L1,<br>author_father_L1,<br>author_mother_L1,<br>author_language_environment,<br>author_environment,<br>author_language_group_affiliation,<br>author_L2_dialect_competence,<br>author_proficiency_level,<br>author_L2_school_grade,<br>dialang_test,<br>doc,<br>exam_type,<br>text_language,<br>school_type,<br>school_language,<br>cefr_appropriateness,<br>cefr_orthography,<br>cefr_grammar,<br>cefr_lex_accuracy,<br>cefr_lex_diversity,<br>cefr_coherence                                                                                                                                                                                      | ambiguous_alt,<br>foreign_word (!!),<br>lemma,<br>original,<br>paragraph,<br>pos,<br>pos_ud,<br>sentence,<br>target,<br>transcription                   |                                                                                                                                                                    |
| MERLIN          | https://www.porta.eurac.edu/lci/merlin/                    | Scritta                               | _author_id,<br>_author,<br>_author_L1,<br>_author_age,<br>_author_gender,<br>_rating_coherence,<br>_rating_coherence2,<br>_rating_fair_cefr,<br>_rating_fair_cefr_rough,<br>_rating_general_linguistic_range,<br>_rating_general_linguistic_range2,<br>_rating_grammatical_accuracy,<br>_rating_grammatical_accuracy2,<br>_rating_orthography,<br>_rating_orthography2,<br>_rating_sociolinguistic_appropriateness,<br>_rating_sociolinguistic_appropriateness2,<br>_rating_vocabulary_control,<br>_rating_vocabulary_control2,<br>_rating_vocabulary_range,<br>_rating_vocabulary_range2,<br>_task_formality,<br>_task_id,<br>_task_topic,<br>_task_topic_en,<br>_task_type,<br>_task_versions,<br>_test_language,<br>_test_level_cefr,<br>_text_type |                                                                                                           lemma,<br> pos,<br>target hypothesis,<br>vari errori grammaticali,<br>ortografici,<br>intelligibility,<br>vocabulary,<br>cohesion/coherence,<br>sociolinguistic appropriateness, pragmatics |

**Discussione in plenum**: rispetto ai corpora che già conoscevi o che hai usato, quali sono le caratteristiche e le particolarità dei learner corpora? 

* sample autentici? corpora non di apprendenti: testi che scrivi indipendentemente dalla ricerca/raccolta del corpus vs. learner corpora: quasi sempre setting sperimentali, certificazioni, esami, etc.
* design del corpus è molto più ‘constrained’ -> es. studi longitudinali (leonide, loccli), scritto vs. parlato (coli)
* metadati: sappiamo moltissimo sull’autore/autrice del testo, es. usi linguistici, proficiency, task, etc. vs. non sappiamo quasi nulla degli autori che contribuiscono ai corpora generali.
* rappresentativi? sample sono quasi sempre relativi a una singola certificazione (es. LIPS, COLI), o relativi a una specifica regione (es. LEONIDE, KOLIPSI x Alto Adige). Eccezione di Valico che raccoglie testi da tantissime location e centri linguistici.
* annotazioni: oltre ai classici lemma e pos, può essere annotata anche la target hypothesis, errori ortografici, grammaticali, etc. code-switching, etc.

## Usare i learner corpora

Sillabo data-driven: parole connettive nello scritto di apprendenti di livello B1-C2.

### 1.1 - Scelta del corpus

* Corpora con CEFR: CELI, COLI, LOCCLI, KOLIPSI-2, MERLIN
* CEFR B1-C2: CELI, KOLIPSI-2

### 1.2 - Costruzione della query

* CELI: 
    * vado su "Restricted query"
    * seleziono CQP syntax 
    * query [pos = "SUB"] oppure [pos = "(SUB|CON)"]

* KOLIPSI-2:
    * vado su all4ling.eurac.edu/annis
    * seleziono Kolipsi-2_L2_IT
    * Query builder > word sequences & meta > (Linguistic sequence) initialize > add > pos_ud SCONJ;
    * (Meta information) > add > author_proficiency_level > B1 (meta::author_proficiency_level = "B1")
    * Trick the query to search for both CCONJ and SCONJ = pos_ud = /.*CONJ/; alternatively look for pos = CON 

### 1.3 - come varia l'uso dei connettivi nei diversi livelli del CEFR?

* CELI

Tendenze generali

| cefr | norm frequency | types | types/tokens |
|------|----------------|-------|--------------|
| B1   |12,029.73       |39     |              |
| B2   |13,996.62       |52     |              |
| C1   |10,576.61       |52     |              |
| C2   |10,140.63       |59     |              |

Quali sono i connettivi comuni a tutti i livelli? ​​

Nonostante, affinché, che cosa, chi, com', come, cos', cosa, dato che, dove, finché, in quanto, perché, poiché, prima che, quale, quali, quanto, se, sempre che, senza che, tanto che, tanto da, 

Connettivi tipici livelli più avanzati (appaiono solo nei livelli C1-C2):

Dal momento che, Quando, a patto che, malgrado che, per quanto, quasi che, si, tant'è vero che, Può darsi che, allo scopo di, laddove, sebbene, Adesso che, Pur, Tant'è vero che, Tanto è vero che, benché, dal momento che, dovunque, in modo da, nel momento in cui, quado, qual, quant'

Vedi notebook per tendenze interessanti sui singoli connettivi.

* KOLIPSI-2

Tendenze generali

| cefr | norm frequency | types | types/tokens |
|------|----------------|-------|--------------|
| B1   |12,029.73       |39     |              |
| B2   |13,996.62       |52     |              |
| C1   |10,576.61       |52     |              |
| C2   |10,140.63       |59     |              |

Quali sono i connettivi comuni a tutti i livelli? ​​

Connettivi tipici livelli più avanzati (appaiono solo nei livelli C1-C2):
