## Data Description

- survey data which was randomly administered in the fall of 2025 at a large commuter school in Canada. Although the author doesn't explicitly mention it, the school was ascertained to be the University of Toronto Missisauga due to a variable name.
- Students who were selected for the study were below the first quartile in terms of entering hs gpa. This was because students who place in the upper quartile are more likely to graduate than those who don't.
- Students were randomly assigned to one of three treatment groups:
  1) Service Strategy: Student Support Program (SSP)
  2) Incentive Stategy: Student Fellowship Program (SFP)
  3) Both: SFSP (Student Fellowship and Student Program)
- students in the treatment group were randomly assigned and asked to sign-up for one of the three services. They were presumably not told beforehand which one.
  - SSP: 55%, SFP: 87%, SFSP: 79%
- There were 1006 students in the control group which did not receive any further information except for the baseline survey.

### Service Strategy: SSP
- 250 students were offered SSP including peer advising and facilitated study groups
- 150 students were also offered it in the SFSP
- there were 21 female peer advisors and 8 male

### Methodology
- The empirical tool that will be used to investigate the relationship between 

Example: What is the impact of participating in student support services on GPA?
- Treatment: participation in the student support program
- Groups: No participation in the student support program (control), participation in the student support program (treatment)
- The two groups of students are otherwise similar
- Outcome (Y): % change in GPA
<hr>

[Difference in Difference Columbia University](https://www.publichealth.columbia.edu/research/population-health-methods/difference-difference-estimation)
In order to estimate any causal effect, three assumptions must hold: exchangeability, positivity, and Stable Unit Treatment Value Assumption (SUTVA)
. DID estimation also requires that:

- Intervention unrelated to outcome at baseline (allocation of intervention was not determined by outcome)

- Treatment/intervention and control groups have Parallel Trends in outcome (see below for details)

- Composition of intervention and comparison groups is stable for repeated cross-sectional design (part of SUTVA)

- No spillover effects (part of SUTVA)

I will focus on parallel trends here and that the treatment and control groups are similar. 
