# Requirements

## Functional requirements (what the system must DO)
FR1: The system shall extract historical completed item throughput counts from provided sprint records
FR2: The system shall allow the user to input the total remaining backlog item count
FR3: The system shall execute a Monte Carlo simulation consisting of 10,000 iterations
FR4: The system shall randomly resample historical throughput data for future sprints until the backlog count is reached in each simulation iteration
FR5: The system shall output the predicted number of sprints required to finish the backlog at P50, P85, and P95 confidence intervals

## Non-functional requirements (how the system must PERFORM)
NFR1: The system shall complete the 10,000-iteration Monte Carlo simulation and display results in under 5 seconds
NFR2: The system shall accept historical Agile sprint data via structured CSV files
NFR3: The system shall automatically flag an error if the uploaded dataset contains fewer than 5 historical sprints, preventing mathematically invalid simulations