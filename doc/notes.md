# Business Understanding Notes

## 1.1 Determine business objectives

### Background
**Organisation**
- University project for evaluation in the Computer Learning course.

**Problem area**
- Sports (basketball) forecasting.
- Predict which teams will qualify for the next season's playoffs.
- Data from the past seasons was provided.
- Targeted towards evaluators / kaggle competition; documentation of the steps taken is paramount.
- The user should be able to use the results of this project to better predict the qualifying teams.

**Current solution**
- They exist but are not relevant to the scope of this project.

### Business objectives
- Predict which teams will qualify for the next season's playoffs.
- The teams must obviously correspond to the current ones.
- We want our predictions to be as accurate as possible to the actual results.

### Business success criteria
- Our solution must perform as accurately as possible in the Kaggle contest.
- Therefore, success can be measured by having our predictions attaining the highest score relative to other submissions.
- Furthermore, the project must meet as many evaluation criteria as possible to assure a high grade.

- The competition is assessed by Kaggle, whereas the final evaluation is assessed by the relevant evaluators.

## 1.2 Assess situation

### Inventory of resources
- The team's own personal computers are the main hardware platform.
- As such, availability should not a problem.

- The data sources are static `csv` files made for this project.
- The basic background knowledge source is provided in the project description.

- The development team consists of the 3 members associated with this repository.
- Tutors provide guidance to the project throughout practical classes.
- Tutors may also be available during lectures and attendance hours.

### Requirements, assumptions and constraints
- The final predictions of this project must be submitted to Kaggle at 24/11.
- Constraints include the juggling of other courses' projects, which may remove time available to this one.

### Risks and contingencies
- Members may become busy with other projects.
- Personal computers may become unavailable due to failure, etc.
- Should there be too many constraints to fully realise the project, priorities must be re-evaluated and focused on.

### Glossary
- **Season:** competition that takes place over the course of one year.
- **Play-offs:** second part of the competition, in which the sole winner is awarded the trophy. Only 8 teams may advance to this phase in a given season.
- **Assist:** basketball term for passing the ball to a player that then scores a goal.
- **Rebound:** basketball term for when a player retrieves the ball after a missed goal/throw.
- **Turnover:** basketball term for when a team loses possession of the ball before attempting a goal.

### Costs and benefits
- Data collection incurs no cost, since the dataset used is already available to us.
- Costs incurred come from setup of the pipeline and experimentation with different methods and models.
- As of now we don't have an estimate of the time cost of this project.

## Determine data mining goals

### Data mining goals
- To determine the likelihood of each team, considering their most recent setup, of participating in a playoff.
- Therefore, this is a *binary probabilistic classification* problem.
- In this case, the probability itself, rather than the classification proper, is the desired attribute, since exactly 8 teams must be chosen.

### Data mining success criteria
- Our algorithm should be able to correctly identify qualifiable teams with over 85% confidence.
- This mark should be able to guarantee good performance in the competition.

