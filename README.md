# Assignment:Developing a Rule-Based Matchmaking System for a Dating Application(In your groups)

## Instructions
# Part 1: System Overview & Design
- Explain the purpose of a rule-based matchmaking system.
- Define the attributes that will be used for matchmaking (e.g., age, location, interests, gender preference).
- Describe the scoring rules for compatibility (e.g., shared interests = +10 points, same city = +5 points, age gap > 10 years = -5 points).
- Define the data structure to store user profiles (e.g., dictionaries, lists, or classes in Python).

# Part 2: Implementation
- Create a Profile Management System:
- Implement a system to add, remove, and retrieve user profiles.
- Each profile should include attributes such as:
1. Name
2. Age
3. Gender
4. Interests (list of hobbies)
5. Location
- Develop a Matching Algorithm:
- Implement a function to compare two profiles based on predefined rules.
- Assign compatibility scores using weighted attributes:
- Age difference: Normalize and assign a score.
- Shared interests: Calculate a similarity score (e.g., Jaccard Index).
- Location: Exact match gets a higher score.
- Find Best Matches:
- Implement a function that takes a user ID and finds the top 3 best matches based on compatibility scores.
- Sort matches in descending order of compatibility.

# Part 3: Testing & Evaluation
- Create at least 5 user profiles and store them in the system.
- Run the matchmaking function for one of the profiles and display the top matches with scores.
- Analyze the output and explain why certain users were matched.

# Deliverables:
- Code Implementation: A Python script or Jupyter Notebook with the matchmaking system.
- Report (2-3 pages):
- System overview and design explanation.
- Description of rules and scoring logic.
- Screenshots or outputs of matchmaking results.
- Reflection on limitations and possible improvements.

# If possible:
1. Implement gender preferences in matchmaking.
2. Add a GUI or web interface for user interaction.
3. Allow users to customize weightings for different attributes.