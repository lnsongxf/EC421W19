# EC 421, Winter 2019

Welcome to **Economics 421: Introduction to Econometrics** (Winter 2019) at the University of Oregon (taught by [Edward Rubin](https://edrub.in)).

For information on the course specifics, please see the [syllabus](https://raw.githack.com/edrubin/EC421W19/master/Syllabus/syllabus.pdf).

## Lecture slides

The slides below (linked by their topic) are .html files that will only work properly if you are connected to the internet. If you're going off grid, grab the PDFs (you'll miss out on gifs and interactive plots, but the equations will render correctly). I create the slides with [`xaringan`](https://github.com/yihui/xaringan/wiki) in [R](cran.r-project.org). Thanks go to [Grant McDermott](grantmcdermott.com/) for helping/pushing me to get going with `xaringan`.

1. [The introduction to "Introduction to Econometrics"](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/01Intro/01_intro.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/01Intro/01_intro.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/01Intro/01_intro.Rmd)
2. [Review of key math/stat/metrics topics](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/02Review/02_review.html)<br>Density functions, deriving the OLS estimators, properties of estimators, statistical inference (standard errors, confidence intervals, hypothesis testing), simulation <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/02Review/02_review.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/02Review/02_review.Rmd)
3. [Review of key topics from EC320](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/03Review/03_review.html)<br>(the first course in our intro-to-metrics sequence) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/03Review/03_review.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/03Review/03_review.Rmd)
4. [Heteroskedasticity: Tests and implications](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/04Heteroskedasticity/04_heteroskedasticity.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/04Heteroskedasticity/04_heteroskedasticity.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/04Heteroskedasticity/04_heteroskedasticity.Rmd)
5. [Living with heteroskedasticity: Inference, WLS, and specification](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/05Heteroskedasticity/05_heteroskedasticity.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/05Heteroskedasticity/05_heteroskedasticity.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/05Heteroskedasticity/05_heteroskedasticity.Rmd)
6. [Consistency and OLS in asymptopia](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/06Consistency/06_consistency.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/06Consistency/06_consistency.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/06Consistency/06_consistency.Rmd)
7. [Introduction to time series](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/07TimeSeries/07_time_series.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/07TimeSeries/07_time_series.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/07TimeSeries/07_time_series.Rmd)
8. [Autocorrelated disturbances](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/08Autocorrelation/08_autocorrelation.html)<br>Implications, testing, and estimation. Also: introduction `ggplot2` and user-defined functions. <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/08Autocorrelation/08_autocorrelation.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/08Autocorrelation/08_autocorrelation.Rmd)
9. [Nonstationarity](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/09Nonstationarity/09_nonstationarity.html)<br>Introduciton, implications for OLS, testing, and estimation. Also: in-class exercise for model selection. <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/09Nonstationarity/09_nonstationarity.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/09Nonstationarity/09_nonstationarity.Rmd)
10. [Causality](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/10Causality/10_causality.html)<br>Introduction to causality and the Neymam-Rubin causal model. Also: Recap of in-class model-selection exercise. <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/10Causality/10_causality.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/10Causality/10_causality.Rmd)
11. [Instrumental Variables](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/11InstrumentalVariables/11_instrumental_variables.html)<br>Review the Neymam-Rubin causal model; introduction to instrumental variables (IV) and two-stage least squares (2SLS). Applications to causal inference and measurement error. Venn diagrams. <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/11InstrumentalVariables/11_instrumental_variables.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/12InstrumentalVariables/12_instrumental_variables.Rmd)
12. [Panel Data](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/12PanelData/12_panel_data.html)<br>A brief introduction to panel data. <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/LectureNotes/12PanelData/12_panel_data.pdf) | [.Rmd](https://github.com/edrubin/EC421W19/blob/master/LectureNotes/12PanelData/12_panel_data.Rmd)

## Problem sets

1. [Problem set 1: Review of OLS](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS01/ps01.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS01/ps01.pdf) | [Data](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS01/dataPS01.csv) | [Solutions](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS01Solutions/ps01Solutions.pdf)
2. [Problem set 2: Heteroskedasticity, consistency, and time series](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS02/ps02.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS02/ps02.pdf) | [Data](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS02/dataPS02.csv) | [Solutions](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS02Solutions/ps02Solutions.pdf)
3. [Problem set 3: Time series and autocorrelation](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS03/ps03.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS03/ps03.pdf) | [Data](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS03/gas_oil.csv) | [Solutions](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS03Solutions/ps03Solutions.pdf)
4. [Problem set 4: Nonstationarity, causality, and instrumental variables](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS04/ps04.html) <br> [PDF](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS04/ps04.pdf) | [Data](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS04/wages.csv) | [Solutions](https://raw.githack.com/edrubin/EC421W19/master/ProblemSets/PS04Solutions/ps04Solutions.pdf)

## Midterm

- [Topics](https://raw.githack.com/edrubin/EC421W19/master/Midterm/Topics/midterm_topics.pdf): topics that were fair game for the exam
- [Review questions](https://raw.githack.com/edrubin/EC421W19/master/Midterm/Review/midterm_review.pdf): no solutions; just review questions
- [Midterm](https://raw.githack.com/edrubin/EC421W19/master/Midterm/Exam/midterm.pdf): the actual exam
- [Solutions](https://raw.githack.com/edrubin/EC421W19/master/Midterm/midterm_key.pdf): short solutions to the midterm

## Final

- [Topics](https://raw.githack.com/edrubin/EC421W19/master/Final/Topics/final_topics.pdf): topics that were fair game for the exam
- [Review questions](https://raw.githack.com/edrubin/EC421W19/master/Final/Review/final_review.pdf): no solutions; just review questions
- [Final](https://raw.githack.com/edrubin/EC421W19/master/Final/Exam/final.pdf): the actual exam
- [Solutions](https://raw.githack.com/edrubin/EC421W19/master/ExamKey/final_key.pdf): solution key to the final
