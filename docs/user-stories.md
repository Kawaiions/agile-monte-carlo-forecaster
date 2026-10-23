# User Stories

Format: As a [type of user], I want [goal], so that [reason or benefit].

1. As a Scrum Master, I want to input our remaining backlog size, so that I can generate a probabilistic delivery forecast. (FR2)
   * Acceptance Criteria: (1) The system accepts a positive integer for the backlog size. (2) The system displays an error if non-numeric characters are entered.
2. As a Project Manager, I want to view the delivery forecast at 85% and 95% confidence levels, so that I can communicate objective risk to stakeholders. (FR5)
   * Acceptance Criteria: (1) The system distinctly displays the calculated P85 and P95 sprint limits. (2) The system prevents users from altering the calculated probability distribution once generated.
3. As an Agile team member, I want the system to randomly pull from past sprint throughputs 10,000 times, so that the simulation accounts for real-world delays. (FR3, FR4)
   * Acceptance Criteria: (1) The engine successfully triggers 10,000 distinct resampling loops. (2) The system logs a success message upon completion of the iterations.