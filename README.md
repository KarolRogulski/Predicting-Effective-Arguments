# Feedback Prize - Predicting Effective Arguments

## Competition description

### Goal of the Competition
The goal of this competition is to classify argumentative elements in student writing as "effective," "adequate," or "ineffective." 
You will create a model trained on data that is representative of the 6th-12th grade population in the United States in order to minimize bias. 
Models derived from this competition will help pave the way for students to receive enhanced feedback on their argumentative writing. 
With automated guidance, students can complete more assignments and ultimately become more confident, proficient writers. 

### Context
Writing is crucial for success. In particular, argumentative writing fosters critical thinking and civic engagement skills, 
and can be strengthened by practice. However, only 13 percent of eighth-grade teachers ask their students to write persuasively each week. 
Additionally, resource constraints disproportionately impact Black and Hispanic students, 
so they are more likely to write at the “below basic” level as compared to their white peers. 
An automated feedback tool is one way to make it easier for teachers to grade writing tasks assigned to their students 
that will also improve their writing skills.

There are numerous automated writing feedback tools currently available, but they all have limitations, especially with argumentative writing. 
Existing tools often fail to evaluate the quality of argumentative elements, such as organization, evidence, and idea development. 
Most importantly, many of these writing tools are inaccessible to educators due to their cost, which most impacts already underserved schools.

Georgia State University (GSU) is an undergraduate and graduate urban public research institution in Atlanta. 
U.S. News & World Report ranked GSU as one of the most innovative universities in the nation. 
GSU awards more bachelor’s degrees to African-Americans than any other non-profit college or university in the country. 
GSU and The Learning Agency Lab, an independent nonprofit based in Arizona, are focused on developing science of learning-based tools 
and programs for social good.

## Data
The dataset presented here contains argumentative essays written by U.S students in grades 6-12. 
These essays were annotated by expert raters for discourse elements commonly found in argumentative writing:

* Lead - an introduction that begins with a statistic, a quotation, a description, or some other device to grab the reader’s attention and point toward the thesis
* Position - an opinion or conclusion on the main question
* Claim - a claim that supports the position
* Counterclaim - a claim that refutes another claim or gives an opposing reason to the position
* Rebuttal - a claim that refutes a counterclaim
* Evidence - ideas or examples that support claims, counterclaims, or rebuttals.
* Concluding Statement - a concluding statement that restates the claims

Your task is to predict the quality rating of each discourse element. Human readers rated each rhetorical or argumentative element, 
in order of increasing quality, as one of:
* Ineffective
* Adequate
* Effective
