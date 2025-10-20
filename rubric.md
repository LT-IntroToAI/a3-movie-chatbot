# Assignment 3 Rubric - Movie Chatbot
**Total Points: 20**
**Name: [Insert name here]**
---
## Grading Notes
You'll be graded on your **function implementations**, **search functionality**, and **creative additions**. I'm looking for:
- Correct implementation of all action functions with proper data filtering
- Working search_pa_list that handles matches, no answers, and unknown queries
- Thoughtful additions to the movie database and pattern/action pairs
- Clean, well-documented code with appropriate docstrings
Remember: This assignment completes our movie chatbot system - focus on understanding **how databases work with natural language** and **how to extend systems with new functionality**.
---
## Grading Table
| Criteria | Points Possible | Points Earned | Comments |
|----------|----------------|---------------|----------|
| **Action Functions** | 9 | | |
| **Core System Functions** | | | |
| search_pa_list Implementation | 6 | | |
| query_loop Function | 1 | | |
| **Creative Additions** | | | |
| Database & Pattern Extensions | 3 | | |
| **Writeup & Reflection** | | | |
| Reflection answers | 2 | | |
| **TOTAL** | **20** | | |
---
## Action Functions (9 points)
**Basic Movie Queries (5 points)**
- title_by_year (1 point): Returns movies from specific year
- title_by_year_range (1 point): Returns movies from year range (inclusive)
- title_before_year (1 point): Returns movies before specific year (exclusive)  
- title_after_year (1 point): Returns movies after specific year (exclusive)
- year_by_title (1 point): Returns year when movie was made

**Actor/Director Queries (4 points)**
- director_by_title (1 point): Returns director of specific movie
- title_by_director (1 point): Returns movies directed by specific person
- actors_by_title (1 point): Returns actors in specific movie (only tested on valid titles)
- title_by_actor (1 point): Returns movies featuring specific actor

*Scoring for each function:*
- **1 point:** Function works correctly, passes all tests, returns proper list format
- **0.5 points:** Function mostly works but has minor issues (edge cases, formatting)
- **0 points:** Function doesn't work or not implemented
---
## Core System Functions (6 points)
**search_pa_list Implementation (5 points)**
- **Returning Answers (2 points)**
  - **2 points:** Correctly matches patterns and returns appropriate answers for all valid queries
  - **1 point:** Works for most queries but misses some edge cases
  - **0 points:** Function doesn't properly return answers
- **"No answers" Response (2 points)**
  - **2 points:** Correctly returns ["No answers"] when pattern matches but no data found
  - **1 point:** Sometimes returns correct response but inconsistent
  - **0 points:** Doesn't handle no-answer cases properly
- **"I don't understand" Response (2 points)**
  - **2 points:** Correctly returns ["I don't understand"] when no pattern matches
  - **1 point:** Sometimes returns correct response but inconsistent  
  - **0 points:** Doesn't handle unknown queries properly
---
## Creative Additions (3 points)
**Database & Pattern Extensions (3 points)**
- **Add Movie to Database (1 point)**
  - **1 point:** Successfully added at least one new movie with proper format (title, director, year, actors)
  - **0.5 points:** Added movie but with formatting issues
  - **0 points:** No movie added or incorrect format
- **Add Pattern/Action Pair (2 points)**  
  - **2 points:** Added new pattern and corresponding action function that works correctly, demonstrates creativity and understanding
  - **1 point:** Added pattern/action but with minor implementation issues or limited functionality
  - **0.5 points:** Attempted addition but significant problems
  - **0 points:** No new pattern/action pair added

---

## Writeup & Reflection (2 points)

**Reflection Questions (2 points)**
- **2 points:** All three reflection questions answered thoughtfully with specific examples and clear understanding of concepts
- **1.5 points:** All questions answered with good detail but could use more depth
- **1 point:** Questions answered but responses are brief or lack specific examples
- **0.5 points:** Questions answered minimally with little detail
- **0 points:** Reflection questions not completed

---

**Documentation Penalty**
- **-1 point:** Missing or inadequate docstrings for new functions