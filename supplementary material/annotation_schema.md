# Annotation Schema:

Each case will be annotated with the following information stored in a json format.

1. Case ID\
{'caseId': caseyear_casenumber}

2. Case Name\
{'caseName': text}

3. Citations\
{'citations': [{'insc_citation': text, 'scr_citation': text, 'air_citation': text, 'other_citations': text}]}

4. Acts\
{'acts': text}
  
5. Judges:\
{'judges': [{'judgeId': uuid, 'judgeName': text, 'isChiefJustice': binary}]}

6. Plaintiffs:\
{'plaintiffs': [{'plaintiffId': int, 'plaintiffName': text}]}

7. Defendants:\
{'defendants': [{'defendantId': int, 'defendantName': Text}]}

8. Appearing for plaintiffs:\
{'plaintiffLawyers': [{'plaintiffLawyerId': int, 'plaintiffLawyerName': text, 'plaintiffId': [int, ...] }]}

9. Appearing for defendants:\
{'defendantLawyers': [{'defendantLawyerId': int, 'defendantLawyerName': text, 'defendantId': [int, ...] }]}

10. Judgement Text:
{'judementText': text}

11. Judgement Sentences:
{'judgementSents:' [{'sentId': int, 'sentText': text, 'sentRhetoricalRole': int, 'sentPseudoRelevance': binary}]}

12. Headnote Text:
{'headnoteText': text}

13. Headnote Sentences:
{'headnoteSents:' [{'sentId': int, 'sentText': text, 'sentRhetoricalRole': int}]}
