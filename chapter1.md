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
- Assign values for the populations of **older_adults** and for **younger_adults**.
- Assign values for the numbers of cases with disease in each group. Use **older_cases** and **younger_cases**.
- Calculate prevalence in each population.

`@hint`










