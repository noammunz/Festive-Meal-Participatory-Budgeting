# Participatory Budgeting for Festive Meal

This project implements a participatory budgeting process to decide on the food and drinks for a class event. It involves collecting ideas from participants, designing ballots, conducting voting, and analyzing results to ensure an equitable and satisfactory selection of items.

## Project Overview

Participatory budgeting is a democratic process where community members directly decide how to spend part of a public budget. This approach empowers people to contribute to decision-making, ensuring that funds are used in ways that reflect the community's preferences.

## Steps and Methodology

1. **Idea Collection**:
   - Gathered suggestions from classmates for food and drinks.
   - Finalized a list of 16 categorized items: hot dishes, cold dishes, snacks, sweets, and beverages.

2. **Ballot Design**:
   - Created two types of ballots: Approval and Cumulative.
   - Approval Ballot: Participants vote for any number of items they like.
   - Cumulative Ballot: Participants allocate 100 points among their preferred items.

3. **Voting Process**:
   - Conducted voting considering dietary restrictions and preferences.
   - Excluded meat options and redistributed points for such items.

4. **Aggregation Methods**:
   - Tested three methods: Greedy, Equal Share, and Sequential Phragmén.
   - Greedy method with approval voting using a single budget was most effective.

5. **Result Analysis**:
   - Analyzed outcomes to finalize selections based on participant preferences and budget utilization.

## Future Steps

1. **Final Survey**:
   - Distribute a second and final survey presenting three outcomes based on initial voting results.
   - Gather final feedback and preferences from participants.

2. **Evaluation and Final Selection**:
   - Evaluate the final survey results based on participant responses and other metrics.
   - Determine and finalize the best outcome for the event.

## Repository Structure

- `docs/`: Documentation related to the project.
- `src/`: Source files for data collection, voting, and analysis.
- `results/`: Results from the initial voting and aggregation methods.

## How to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push to your branch.
4. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

