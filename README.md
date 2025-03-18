java c
Genetic Epidemiology Assessment
Data files
In the folder for the Assessment, you will find binary format PLINK files (i.e. a .bed   file, a .bim   file and a .fam   file) for a genetic dataset used previously to explore genome-wide associations of autosomal variants with risk of coronary artery disease. This phenotype is mostly comprised of cases with myocardial infarction (more commonly known as ‘heart attack’) or who died of coronary artery disease. Unmatched controls to compare against the cases were recruited at each recruitment centre from the general population (e.g. via General Practice registers). The participants were recruited from across 8 European countries (Denmark, Germany, Greece, Italy, the Netherlands, Spain, Sweden and the United Kingdom).
You will also find a separate file (‘assignment_covar.txt’). Within this file you will find the first 2 multi-dimensional scaling (MDS) vectors of genetic ancestry (‘mds1’, ‘mds2’), baseline age (‘age’)   and participant sex (‘sex’, male==1, female==2). A variable called ‘pheno’ represents the phenotype of interest, in this case whether a participant has had a coronary heart disease event (pheno==2) or not (pheno==1). (NB: this same information is also encoded in the phenotype column in the .fam   file). Finally, you have also been provided with a file (‘mds_variables.txt’) that contains the first 2 MDS vectors of genetic ancestry for all the study participants, as well as for samples from the 1000 Genomes project from a few of the different ethnicities:·   CEU = Northern European ancestry samples from Utah in the United States, representing European ancestries;·   CHB = Han Chinese samples from Beijing, representing East Asian ancestries;·   JPT = Japanese samples from Tokyo, representing East Asian ancestries;·   TSI = European samples from Toscana in Italy, representing European ancestries;·   YRI = Nigerian samples, representing African ancestries.
The file also includes information about which of the 8 European countries each of the study participants come from.
Instructions
Using what you have learned during the Genetic Epidemiology module, use this dataset to conduct a genome-wide association study (GWAS) to see what these data can tell you about the association between autosomal SNPs and coronary artery disease. As discussed during the module, it is not informative about biology or disease to merely conclude that a genetic variant has strong evidence of association with a phenotype, so consider which of the several ‘post-GWAS’ approaches you have learned about in the module that you could employ to build on your statistical findings to provide further biological insights.
Write up your findings in a technical report of no more than 2000 words   (excluding any Tables, Figures, legends, appendices or references). The report should include details of the methods you have used and the rationale for using those methods, the results you have generated (including any relevant tables or figures to display information), and a brief discussion that summarises your findings, puts your findings in context of previous literature and considers strengths and limitations of what you have done. You may wish to refer to the module marking rubric below.
The choice of how to structure your report is up to you, but you may wish to consider subheadings such as “Pre-GWAS Quality Control, Association Testing, Post-GWAS Analysis, Discussion” or more traditional subheadings like “Methods, Results, Discussion”. Note that you are not   expected to include an Introduction section as the aim of the exercise is to test your knowledge and understanding from the Module, not to spend time extensively reviewing the background of the phenotype or previous studies. When you refer to published literature, please list the references at the end of the report.
Even though you have variants from all 22 autosomal chromosomes, it should take no more than a few minutes to run PLINK v1.9 commands on this dataset on your computer as you have only been provided with directly genotyped variants (not imputed variants). However, bear in mind that the input files provided and the results files you produce will be considerably larger than those used in the GWAS practical sessions, so you may have to adapt accordingly. If PLINK is giving you strange errors (e.g. segmentation fault errors) or refusing to run, please (a) consult with a classmate in case they have already overcome this issue, then (b) email me with details of the error. This assignment is not supposed to be testing your understanding of specific computing issues so don’t spend hours unable to make progress due to computing problems!
Some additional guidance for markers
●   The rubric is for guidance on expectations – it is not a prescriptive template. Use your judgement and experience, and interpret flexibly.
●   Remember that the students have only spent 4 days on the Genetic Epidemiology module, which was completely new to many of them, so judge accordingly. For example, students have 代 写Genetic Epidemiology AssessmentSQL
代做程序编程语言learned about the principles of data filtering for quality control purposes, but have not spent much time considering how to determine what exact filtering thresholds to use.
●   We intentionally have not provided guidance on how the different sections should be weighted. Think about the quality of each section, then give an overall mark based on these and your overall impression. While this assessment includes considerable elements of computational work, it is primarily intended to test their understanding of the principles and practices of Genetic Epidemiology have, so the most important aspect is that they have used appropriate methods and justified why they are using them, interpreted their results appropriately etc.
●   The words used in the rubric will be interpreted differently by different people. Talking with colleagues could help you gain clarity. Appreciation of inherent uncertainty is one of the course learning outcomes. Remember, not every aspect of the report needs to be at Distinction level to merit an overall Distinction grade.
●   Remind yourself of the instructions given to students above.
●   Provide constructive   feedback. Give your overall impression, and provide specific, actionable feedback, ideally that students can apply in subsequent work. Including specific examples from the assignment to illustrate points is helpful.
●   Student submissions are blinded, so please do not try to determine the identity of the student whose assignment you are marking and please do bear the principles of blind marking in mind: make every effort to mark based only on the merits of the submission itself, using the criteria in the rubric provided, rather than anything you might know about the student, their supervisor, or any previous feedback you may have given.
Marks and feedback formStudent name: Marker 1 feedback comments: Marker 2 feedback comments: Quality control      GWAS analysis      Post-GWAS aspects      Tables  Figures      Discussion      Overall impression      
Up to three key things done well      
Up to three key aspects that could have been better       
Mark (provisional, then replaced with agreed final mark)      
Rationale for final mark   
Any other useful feedback for student      
Genetic Epidemiology Module Assessment marking rubric      
   
Refer
Pass 
High Pass 
Distinction 
Quality control 
Little attempt to ensure data cleanliness or mitigate potential biases. Use of methods poorly justified.
Reasonable efforts made to ensure data cleanliness and mitigate potential biases. Use of methods mostly well justified.
Good efforts made to ensure data cleanliness and mitigate potential biases. Use of methods well justified.
Considerable efforts made to ensure data cleanliness and mitigate potential biases. Clear justification for all methods.
GWAS analysis
Analysis poorly implemented, inadequately described and not appropriately interpreted.
Analytical steps well implemented but only partially described and interpreted.
Analytical steps clearly described, appropriately implemented and interpreted.
Thorough analyses, clearly described and well justified, with thoughtful and appropriate interpretation.
Post-GWAS aspects
Little effort to follow up beyond the GWAS analysis.
Reasonable efforts to follow up findings from GWAS analysis, but only partially described, justified or interpreted.
Good efforts to follow up findings from GWAS analysis, generally well described, justified and interpreted.
Extensive efforts to follow up findings from GWAS analysis, well described, clearly justified and appropriately interpreted.
Tables and Figures
Limited use of any Tables  Figures.
Appropriate use of Tables  Figures but not always clearly labelled or easy to interpret.
Tables  Figures are mostly appropriately used and are generally well labelled and clear to interpret.
Very clear, well-labelled, appropriate Tables  Figures that are easy to interpret.
Discussion
Little attempt to interpret findings and to put results into context of previous studies.
References absent or largely incomplete. 
Partial interpretation with some attempt to put findings into context of previous studies.
References mostly relevant and using standard format.
Good interpretation of findings with clear background context. 
References all relevant using standard format.
Excellent interpretation with findings clearly put into context of previous studies.
References all relevant sources, consistently using standard format.
Overall impression
Poor analysis and report, lack of clarity in writing, doesn’t show clear understanding of the topic. 
Good analysis and report, mostly clearly written and demonstrates reasonable understanding.
Very good analysis and report, clearly written and demonstrates very good understanding.
Excellent analysis and report, very clear and thorough demonstrates excellent understanding.
   
   

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
