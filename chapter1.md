---
  title: "Disease Occurrence"
  description: "Calculating prevalence and incidence"
  v2: true

---
## Prevalence

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 353e68ba0c



```

Prevalence is the proportion of a population that has a disease or condition at a certain time. For example, let's calculate prevalence for a population of 500,000 in which we detected 100 cases of disease.

`@instructions`
- Assign the value 500,000 to a variable called population.
- Assign 100 to a variable called cases.
- Calculate the proportion of cases per population. Save this result to a variable called prevalence.

`@hint`
- To assign a variable use the <- operator, as in this example: population <- 500000. 
- Prevalence = cases / population

`@pre_exercise_code`
```{r}
# Load datasets and packages here.
```
`@sample_code`
```{r}
# Assign the population variable
population <- 500000

# Or use scientific notation if it's clearer. The result is the same in R.
population <- 5 * 10^5

# Finish the assignment of the cases variable
cases <- ___

# Finish the prevalence calculation
prevalence <- cases / ___

# Print the prevalence result
prevalence
```
`@solution`
```{r}
# Assign the population variable
population <- 500000

# Or use scientific notation if it's clearer. The result is the same in R.
population <- 5 * 10^5

# Finish the assignment of the cases variable
cases <- 100

# Finish the prevalence calculation
prevalence <- cases / population

# Print the prevalence result
prevalence
```
`@sct`
```{r}
# Update this to something more informative.
success_msg("Great! You have the basics of assigning values to variables. And you've used your skills to calculate prevalence, an important measure of disease occurrence.")
```






---
## Prevalence comparison

```yaml
type: NormalExercise

xp: 100

key: a5f925630f



```

An important purpose of prevalence estimation is to compare disease occurrence over time, among sub-populations, or across geographic regions. Practice calculating prevalence using these examples.
- In 150,000 older adults, 500 had disease.
- In 300,000 younger adults, 100 had disease.

`@instructions`
- Assign values for the populations of **olderAdults** and for **youngerAdults**.
- Assign values for the numbers of cases with disease in each group. Use **olderCases** and **youngerCases**.
- Calculate the prevalence in each population, **olderPrevalence** and **youngerPrevalence**. 
- Display each result by simply typing the prevalence variable name.



`@sample_code`
```{r}
# Assign the olderAdults value of 150,000
olderAdults <- 150000

# Assign the youngerAdults value of 300,000

# Assign the olderCases value of 500
olderCases <- 500

# Assign the youngerCases value of 100

# Calculate the prevalence of disease among older adults
olderPrevalence <- olderCases / olderAdults

# Calculate the prevalence in younger adults
youngerPrevalence <- 

# Display each prevalence result
# Older
olderPrevalence
# Younger
```
`@solution`
```{r}
# Assign the olderAdults value of 150,000
olderAdults <- 150000

# Assign the youngerAdults value of 300,000
youngerAdults <- 300000

# Assign the olderCases value of 500
olderCases <- 500

# Assign the youngerCases value of 100
youngerCases <- 100

# Calculate the prevalence of disease among older adults
olderPrevalence <- olderCases / olderAdults

# Calculate the prevalence in younger adults
youngerPrevalence <- youngerCases / youngerAdults

# Display each prevalence result
# Older
olderPrevalence
# Younger
youngerPrevalence
```







---
## Prevalence across many groups

```yaml
type: NormalExercise

xp: 100

key: 144ec286cf



```















---
## Prevalence

```yaml
type: VideoExercise

xp: 50

key: 8ba6e7451b



```

`@projector_key`
6e06bd4fec46234c3844c651c3c1e003