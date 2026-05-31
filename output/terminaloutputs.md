# Terminal Outputs

## Lab 1 (MDP)

```text
D:\Presentations\Masters Data\Semester-2\Reinforcement Learning\Labs\COMP64202-RL-26\Lab1-MDP\code\autograder.py:17: DeprecationWarning: the imp module is deprecated in favour of importlib and slated for removal in Python 3.12; see the module's documentation for alternative uses
  import imp
Starting on 5-31 at 19:30:48

Question q1
===========

*** PASS: test_cases\q1\1-tinygrid.test
*** PASS: test_cases\q1\2-tinygrid-noisy.test
*** PASS: test_cases\q1\3-bridge.test
*** PASS: test_cases\q1\4-discountgrid.test

### Question q1: 4/4 ###


Question q2
===========

*** FAIL: test_cases\q2\1-bridge-grid.test
***     Policy not correct.
***         Student policy at (1, 1): west
***         Correct policy at (1, 1): east
***         Student policy:
***             .    X    X    X    X    X    .
***             X    W    W    E    E    E    X
***             .    X    X    X    X    X    .
***             Legend:  N,S,E,W at states which move north etc, X at states which exit,
***                      . at states where the policy is not defined (e.g. walls)
***         Correct policy specification:
***             _    _    _    _    _    _    _
***             _    E    _    _    _    _    _
***             _    _    _    _    _    _    _
***             Legend:  N,S,E,W for states in which the student policy must move north etc,
***                      _ for states where it doesn't matter what the student policy does.
***         Gridworld:
***             # -100 -100 -100 -100 -100    #
***             1    S    _    _    _    _    10
***             # -100 -100 -100 -100 -100    #   
***             Legend: # wall, _ empty, S start, numbers terminal states with that reward.
*** Tests failed.

### Question q2: 0/1 ###


Question q3
===========

*** PASS: test_cases\q3\1-question-3.1.test
*** PASS: test_cases\q3\2-question-3.2.test
*** PASS: test_cases\q3\3-question-3.3.test
*** PASS: test_cases\q3\4-question-3.4.test
*** PASS: test_cases\q3\5-question-3.5.test

### Question q3: 5/5 ###


Question q4
===========

*** FAIL: test_cases\q4\1-tinygrid.test
***     Values at iteration 2 are NOT correct.
***        Student solution:
***      values_k_2: """
***                 0.0000       0.0000       0.0000
***     """
***     
***     
***        Correct solution:
***      values_k_2: """
***                10.0000       0.0000       0.0000
***     """
***     
***     
***     Q-Values at iteration 2 for action west are NOT correct.
***        Student solution:
***      q_values_k_2_action_west: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_west: """
***                illegal       5.0000      illegal
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q4\1-tinygrid.test_output
***     
***     
*** FAIL: test_cases\q4\2-tinygrid-noisy.test
***     Values at iteration 2 are NOT correct.
***        Student solution:
***      values_k_2: """
***                 0.0000       0.0000       0.0000
***     """
***     
***     
***        Correct solution:
***      values_k_2: """
***                10.0000       0.0000       0.0000
***     """
***     
***     
***     Q-Values at iteration 2 for action north are NOT correct.
***        Student solution:
***      q_values_k_2_action_north: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_north: """
***                illegal       0.9375      illegal
***     """
***     
***     
***     Q-Values at iteration 2 for action south are NOT correct.
***        Student solution:
***      q_values_k_2_action_south: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_south: """
***                illegal       0.9375      illegal
***     """
***     
***     
***     Q-Values at iteration 2 for action west are NOT correct.
***        Student solution:
***      q_values_k_2_action_west: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_west: """
***                illegal       5.6250      illegal
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q4\2-tinygrid-noisy.test_output
***     
***     
*** FAIL: test_cases\q4\3-bridge.test
***     Values at iteration 2 are NOT correct.
***        Student solution:
***      values_k_2: """
***             __________       0.0000       0.0000       0.0000       0.0000       0.0000   __________
***                 0.0000       0.0000       0.0000       0.0000       0.0000       0.0000       0.0000
***             __________       0.0000       0.0000       0.0000       0.0000       0.0000   __________
***     """
***     
***     
***        Correct solution:
***      values_k_2: """
***             __________       0.0000       0.0000       0.0000       0.0000       0.0000   __________
***                 1.0000       0.0000       0.0000       0.0000       0.0000       0.0000       0.0000
***             __________       0.0000       0.0000       0.0000       0.0000       0.0000   __________
***     """
***     
***     
***     Q-Values at iteration 2 for action north are NOT correct.
***        Student solution:
***      q_values_k_2_action_north: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0000       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_north: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0425       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***     Q-Values at iteration 2 for action south are NOT correct.
***        Student solution:
***      q_values_k_2_action_south: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0000       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_south: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0425       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***     Q-Values at iteration 2 for action west are NOT correct.
***        Student solution:
***      q_values_k_2_action_west: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0000       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_west: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.7650       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q4\3-bridge.test_output
***     
***     
*** FAIL: test_cases\q4\4-discountgrid.test
***     Values at iteration 2 are NOT correct.
***        Student solution:
***      values_k_2: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000   __________       0.0000
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***     """
***     
***     
***        Correct solution:
***      values_k_2: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000   __________       0.0000
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***               -10.0000       0.0000       0.0000       0.0000       0.0000
***     """
***     
***     
***     Q-Values at iteration 2 for action east are NOT correct.
***        Student solution:
***      q_values_k_2_action_east: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_east: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                -0.9000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***     Q-Values at iteration 2 for action south are NOT correct.
***        Student solution:
***      q_values_k_2_action_south: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_south: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                -7.2000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***     Q-Values at iteration 2 for action west are NOT correct.
***        Student solution:
***      q_values_k_2_action_west: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_2_action_west: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                -0.9000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q4\4-discountgrid.test_output
***     
***     
*** Tests failed.

### Question q4: 0/1 ###


Question q5
===========

*** FAIL: test_cases\q5\1-tinygrid.test
***     Values at iteration 1 are NOT correct.
***        Student solution:
***      values_k_1: """
***                 0.0000       0.0000       0.0000
***     """
***     
***     
***        Correct solution:
***      values_k_1: """
***                10.0000       0.0000       0.0000
***     """
***     
***     
***     Q-Values at iteration 1 for action west are NOT correct.
***        Student solution:
***      q_values_k_1_action_west: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_west: """
***                illegal       5.0000      illegal
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q5\1-tinygrid.test_output
***     
***     
*** FAIL: test_cases\q5\2-tinygrid-noisy.test
***     Values at iteration 1 are NOT correct.
***        Student solution:
***      values_k_1: """
***                 0.0000       0.0000       0.0000
***     """
***     
***     
***        Correct solution:
***      values_k_1: """
***                10.0000       0.0000       0.0000
***     """
***     
***     
***     Q-Values at iteration 1 for action north are NOT correct.
***        Student solution:
***      q_values_k_1_action_north: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_north: """
***                illegal       0.9375      illegal
***     """
***     
***     
***     Q-Values at iteration 1 for action south are NOT correct.
***        Student solution:
***      q_values_k_1_action_south: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_south: """
***                illegal       0.9375      illegal
***     """
***     
***     
***     Q-Values at iteration 1 for action west are NOT correct.
***        Student solution:
***      q_values_k_1_action_west: """
***                illegal       0.0000      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_west: """
***                illegal       5.6250      illegal
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q5\2-tinygrid-noisy.test_output
***     
***     
*** FAIL: test_cases\q5\3-bridge.test
***     Values at iteration 1 are NOT correct.
***        Student solution:
***      values_k_1: """
***             __________       0.0000       0.0000       0.0000       0.0000       0.0000   __________
***                 0.0000       0.0000       0.0000       0.0000       0.0000       0.0000       0.0000
***             __________       0.0000       0.0000       0.0000       0.0000       0.0000   __________
***     """
***     
***     
***        Correct solution:
***      values_k_1: """
***             __________       0.0000       0.0000       0.0000       0.0000       0.0000   __________
***                 0.0000       0.0000       0.0000       0.0000       0.0000       0.0000       0.0000
***             __________    -100.0000       0.0000       0.0000       0.0000       0.0000   __________
***     """
***     
***     
***     Q-Values at iteration 1 for action east are NOT correct.
***        Student solution:
***      q_values_k_1_action_east: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0000       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_east: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal      -4.2500       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***     Q-Values at iteration 1 for action south are NOT correct.
***        Student solution:
***      q_values_k_1_action_south: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0000       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_south: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal     -76.5000       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***     Q-Values at iteration 1 for action west are NOT correct.
***        Student solution:
***      q_values_k_1_action_west: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal       0.0000       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_west: """
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***                illegal      -4.2500       0.0000       0.0000       0.0000       0.0000      illegal
***             __________      illegal      illegal      illegal      illegal      illegal   __________
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q5\3-bridge.test_output
***     
***     
*** FAIL: test_cases\q5\4-discountgrid.test
***     Values at iteration 1 are NOT correct.
***        Student solution:
***      values_k_1: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000   __________       0.0000
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***     """
***     
***     
***        Correct solution:
***      values_k_1: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000   __________       0.0000
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***               -10.0000       0.0000       0.0000       0.0000       0.0000
***     """
***     
***     
***     Q-Values at iteration 1 for action east are NOT correct.
***        Student solution:
***      q_values_k_1_action_east: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_east: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                -0.9000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***     Q-Values at iteration 1 for action south are NOT correct.
***        Student solution:
***      q_values_k_1_action_south: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_south: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                -7.2000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***     Q-Values at iteration 1 for action west are NOT correct.
***        Student solution:
***      q_values_k_1_action_west: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***        Correct solution:
***      q_values_k_1_action_west: """
***                 0.0000       0.0000       0.0000       0.0000       0.0000
***                 0.0000   __________       0.0000       0.0000       0.0000
***                 0.0000   __________      illegal   __________      illegal
***                -0.9000       0.0000       0.0000       0.0000       0.0000
***                illegal      illegal      illegal      illegal      illegal
***     """
***     
***     
***     
***     For more details to help you debug, see test output file test_cases\q5\4-discountgrid.test_output
***     
***     
*** Tests failed.

### Question q5: 0/3 ###


Question q6
===========

*** PASS: test_cases\q6\1-tinygrid.test
*** PASS: test_cases\q6\2-tinygrid-noisy.test
*** PASS: test_cases\q6\3-bridge.test
*** PASS: test_cases\q6\4-discountgrid.test

### Question q6: 4/4 ###


Question q7
===========

*** PASS: test_cases\q7\1-tinygrid.test
*** PASS: test_cases\q7\2-tinygrid-noisy.test
*** PASS: test_cases\q7\3-bridge.test
*** PASS: test_cases\q7\4-discountgrid.test

### Question q7: 2/2 ###


Question q8
===========

*** FAIL: test_cases\q8\grade-agent.test
***     Solution is not correct.
***        Student solution: (none, none)
*** Tests failed.

### Question q8: 0/1 ###


Question q9
===========

Beginning 2000 episodes of Training
Reinforcement Learning Status:
	Completed 100 out of 2000 training episodes
	Average Rewards over all training: -509.84
	Average Rewards for last 100 episodes: -509.84
	Episode took 0.32 seconds
Reinforcement Learning Status:
	Completed 200 out of 2000 training episodes
	Average Rewards over all training: -510.68
	Average Rewards for last 100 episodes: -511.52
	Episode took 0.37 seconds
Reinforcement Learning Status:
	Completed 300 out of 2000 training episodes
	Average Rewards over all training: -487.83
	Average Rewards for last 100 episodes: -442.13
	Episode took 0.44 seconds
Reinforcement Learning Status:
	Completed 400 out of 2000 training episodes
	Average Rewards over all training: -455.96
	Average Rewards for last 100 episodes: -360.35
	Episode took 0.46 seconds
Reinforcement Learning Status:
	Completed 500 out of 2000 training episodes
	Average Rewards over all training: -424.84
	Average Rewards for last 100 episodes: -300.38
	Episode took 0.48 seconds
Reinforcement Learning Status:
	Completed 600 out of 2000 training episodes
	Average Rewards over all training: -404.18
	Average Rewards for last 100 episodes: -300.85
	Episode took 0.51 seconds
Reinforcement Learning Status:
	Completed 700 out of 2000 training episodes
	Average Rewards over all training: -380.78
	Average Rewards for last 100 episodes: -240.36
	Episode took 0.49 seconds
Reinforcement Learning Status:
	Completed 800 out of 2000 training episodes
	Average Rewards over all training: -358.20
	Average Rewards for last 100 episodes: -200.17
	Episode took 0.55 seconds
Reinforcement Learning Status:
	Completed 900 out of 2000 training episodes
	Average Rewards over all training: -330.54
	Average Rewards for last 100 episodes: -109.25
	Episode took 0.50 seconds
Reinforcement Learning Status:
	Completed 1000 out of 2000 training episodes
	Average Rewards over all training: -316.43
	Average Rewards for last 100 episodes: -189.43
	Episode took 0.48 seconds
Reinforcement Learning Status:
	Completed 1100 out of 2000 training episodes
	Average Rewards over all training: -291.94
	Average Rewards for last 100 episodes: -47.11
	Episode took 0.50 seconds
Reinforcement Learning Status:
	Completed 1200 out of 2000 training episodes
	Average Rewards over all training: -268.99
	Average Rewards for last 100 episodes: -16.44
	Episode took 0.51 seconds
Reinforcement Learning Status:
	Completed 1300 out of 2000 training episodes
	Average Rewards over all training: -238.69
	Average Rewards for last 100 episodes: 124.85
	Episode took 0.57 seconds
Reinforcement Learning Status:
	Completed 1400 out of 2000 training episodes
	Average Rewards over all training: -217.09
	Average Rewards for last 100 episodes: 63.71
	Episode took 0.64 seconds
Reinforcement Learning Status:
	Completed 1500 out of 2000 training episodes
	Average Rewards over all training: -190.24
	Average Rewards for last 100 episodes: 185.64
	Episode took 0.64 seconds
Reinforcement Learning Status:
	Completed 1600 out of 2000 training episodes
	Average Rewards over all training: -163.55
	Average Rewards for last 100 episodes: 236.76
	Episode took 0.68 seconds
Reinforcement Learning Status:
	Completed 1700 out of 2000 training episodes
	Average Rewards over all training: -148.29
	Average Rewards for last 100 episodes: 95.96
	Episode took 0.62 seconds
Reinforcement Learning Status:
	Completed 1800 out of 2000 training episodes
	Average Rewards over all training: -131.39
	Average Rewards for last 100 episodes: 155.91
	Episode took 0.51 seconds
Reinforcement Learning Status:
	Completed 1900 out of 2000 training episodes
	Average Rewards over all training: -112.50
	Average Rewards for last 100 episodes: 227.56
	Episode took 0.39 seconds
Reinforcement Learning Status:
	Completed 2000 out of 2000 training episodes
	Average Rewards over all training: -99.06
	Average Rewards for last 100 episodes: 156.24
	Episode took 0.66 seconds
Training Done (turning off epsilon and alpha)
---------------------------------------------
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman died! Score: -514
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman died! Score: -512
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 495
Pacman emerges victorious! Score: 499
Pacman emerges victorious! Score: 503
Pacman emerges victorious! Score: 495
Reinforcement Learning Status:
	Completed 100 test episodes
	Average Rewards over testing: 479.76
	Average Rewards for last 100 episodes: 479.76
	Episode took 0.62 seconds
Average Score: 479.76
Scores:        495.0, 503.0, 503.0, 503.0, 499.0, 499.0, 503.0, 503.0, 503.0, 495.0, 503.0, 495.0, 503.0, 503.0, 503.0, 503.0, 499.0, 503.0, 495.0, 495.0, 499.0, 499.0, 495.0, 499.0, 495.0, 495.0, 499.0, 499.0, 503.0, 499.0, -514.0, 503.0, 503.0, 495.0, 503.0, 495.0, 503.0, 503.0, 495.0, 495.0, 495.0, 503.0, 495.0, 499.0, 499.0, 499.0, 503.0, 499.0, 499.0, 503.0, 503.0, 503.0, 503.0, 503.0, 499.0, 495.0, 503.0, 503.0, 503.0, 503.0, 503.0, 503.0, 495.0, 503.0, 503.0, 495.0, 503.0, 499.0, 503.0, 503.0, 495.0, 499.0, 495.0, 503.0, 503.0, -512.0, 503.0, 503.0, 499.0, 499.0, 503.0, 503.0, 499.0, 499.0, 503.0, 495.0, 503.0, 503.0, 495.0, 499.0, 503.0, 503.0, 503.0, 499.0, 499.0, 495.0, 495.0, 499.0, 503.0, 495.0
Win Rate:      98/100 (0.98)
Record:        Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Loss, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Loss, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win, Win
*** PASS: test_cases\q9\grade-agent.test (1 of 1 points)
***     Grading agent using command:  python pacman.py -p PacmanQAgent -x 2000 -n 2100 -l smallGrid -q -f --fixRandomSeed
***     98 wins (1 of 1 points)
***         Grading scheme:
***          < 70:  0 points
***         >= 70:  1 points

### Question q9: 1/1 ###


Question q10
============

*** Method not implemented: getQValue at line 194 of qlearningAgents.py
*** FAIL: Terminated with a string exception.

### Question q10: 0/3 ###


Finished at 19:30:59

Provisional grades
==================
Question q1: 4/4
Question q2: 0/1
Question q3: 5/5
Question q4: 0/1
Question q5: 0/3
Question q6: 4/4
Question q7: 2/2
Question q8: 0/1
Question q9: 1/1
Question q10: 0/3
------------------
Total: 16/25

Your grades are NOT yet registered.  To register your grades, make sure
to follow your instructor's guidelines to receive credit on your project.

```

## Lab 3 (Policy Gradients)

```text
Gym has been unmaintained since 2022 and does not support NumPy 2.0 amongst other critical functionality.
Please upgrade to Gymnasium, the maintained drop-in replacement of Gym, or contact the authors of your software and request that they upgrade.
Users of this version of Gym should be able to simply replace 'import gym' with 'import gymnasium as gym' in the vast majority of cases.
See the migration guide at https://gymnasium.farama.org/introduction/migration_guide/ for additional information.
Epoch: 0, Average Test Return: -1219.4458006646305
Epoch: 1, Average Test Return: -1631.0880567314823
Epoch: 2, Average Test Return: -1703.3578892260273
Epoch: 3, Average Test Return: -1713.9976389826982
Epoch: 4, Average Test Return: -1632.6488827795758
Epoch: 5, Average Test Return: -1308.8806236644468
Epoch: 6, Average Test Return: -1214.75030148751
Epoch: 7, Average Test Return: -983.0019167799079
Epoch: 8, Average Test Return: -1121.1923057605388
Epoch: 9, Average Test Return: -1238.1824158206086
Epoch: 10, Average Test Return: -1055.644869772755
Epoch: 11, Average Test Return: -1168.6067236038732
Epoch: 12, Average Test Return: -587.9241672137398
Epoch: 13, Average Test Return: -571.2819419413374
Epoch: 14, Average Test Return: -223.1135263065652
Epoch: 15, Average Test Return: -145.3944150405573
Epoch: 16, Average Test Return: -266.5809732310835
Epoch: 17, Average Test Return: -240.86724009962344
Epoch: 18, Average Test Return: -172.36615514482278
Epoch: 19, Average Test Return: -199.92523862240037
Epoch: 20, Average Test Return: -209.50217303927258
Epoch: 21, Average Test Return: -198.29464409729164
Epoch: 22, Average Test Return: -122.37875339359928
Epoch: 23, Average Test Return: -149.65570558656546
Epoch: 24, Average Test Return: -120.37919453641607
Epoch: 25, Average Test Return: -146.20679123967506
Epoch: 26, Average Test Return: -140.2373792545905
Epoch: 27, Average Test Return: -236.59991163845808
Epoch: 28, Average Test Return: -168.72645004975672
Epoch: 29, Average Test Return: -256.4647595552625
Epoch: 30, Average Test Return: -144.56868447298706
```

## Lab 2 & 4 (Notebooks)

# Notebook Outputs

## FunctionApproximation

### Cell 2

```text
Requirement already satisfied: numpy in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (2.4.6)
```

```text

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

```text
Requirement already satisfied: matplotlib in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (3.10.9)
Requirement already satisfied: contourpy>=1.0.1 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from matplotlib) (1.3.3)
Requirement already satisfied: cycler>=0.10 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from matplotlib) (0.12.1)
Requirement already satisfied: fonttools>=4.22.0 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from matplotlib) (4.63.0)
Requirement already satisfied: kiwisolver>=1.3.1 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from matplotlib) (1.5.0)
Requirement already satisfied: numpy>=1.23 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from matplotlib) (2.4.6)
Requirement already satisfied: packaging>=20.0 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (26.2)
Requirement already satisfied: pillow>=8 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from matplotlib) (12.2.0)
Requirement already satisfied: pyparsing>=3 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from matplotlib) (3.3.2)
Requirement already satisfied: python-dateutil>=2.7 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (2.9.0.post0)
Requirement already satisfied: six>=1.5 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from python-dateutil>=2.7->matplotlib) (1.17.0)
```

```text

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

```text
Requirement already satisfied: gym in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (0.26.2)
Requirement already satisfied: numpy>=1.18.0 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from gym) (2.4.6)
Requirement already satisfied: cloudpickle>=1.2.0 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from gym) (3.1.2)
Requirement already satisfied: gym_notices>=0.0.4 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from gym) (0.1.0)
```

```text

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

```text
Requirement already satisfied: torch in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (2.12.0)
Requirement already satisfied: filelock in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from torch) (3.29.0)
Requirement already satisfied: typing-extensions>=4.10.0 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from torch) (4.15.0)
Requirement already satisfied: setuptools<82 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from torch) (65.5.0)
Requirement already satisfied: sympy>=1.13.3 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from torch) (1.14.0)
Requirement already satisfied: networkx>=2.5.1 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from torch) (3.6.1)
Requirement already satisfied: jinja2 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from torch) (3.1.6)
Requirement already satisfied: fsspec>=0.8.5 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from torch) (2026.4.0)
Requirement already satisfied: mpmath<1.4,>=1.1.0 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from sympy>=1.13.3->torch) (1.3.0)
Requirement already satisfied: MarkupSafe>=2.0 in c:\users\prathap selvakumar\appdata\local\programs\python\python311\lib\site-packages (from jinja2->torch) (3.0.3)
```

```text

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

### Cell 3

```text
Gym has been unmaintained since 2022 and does not support NumPy 2.0 amongst other critical functionality.
Please upgrade to Gymnasium, the maintained drop-in replacement of Gym, or contact the authors of your software and request that they upgrade.
Users of this version of Gym should be able to simply replace 'import gym' with 'import gymnasium as gym' in the vast majority of cases.
See the migration guide at https://gymnasium.farama.org/introduction/migration_guide/ for additional information.
```

### Cell 11

```text
----- Start Learning with Tabular (1600 states) Q-learning -----
Episode #50 (50000 steps) -- Total reward = -1000, epsilon=0.1.
Episode #150 (144272 steps) -- Total reward = -606, epsilon=0.1.
Episode #250 (219001 steps) -- Total reward = -672, epsilon=0.1.
Episode #350 (286761 steps) -- Total reward = -490, epsilon=0.1.
Episode #450 (336702 steps) -- Total reward = -411, epsilon=0.1.
Episode #550 (389266 steps) -- Total reward = -370, epsilon=0.1.
Episode #650 (433427 steps) -- Total reward = -671, epsilon=0.1.
Episode #750 (477029 steps) -- Total reward = -472, epsilon=0.1.
Episode #850 (521521 steps) -- Total reward = -356, epsilon=0.1.
Episode #950 (561307 steps) -- Total reward = -393, epsilon=0.1.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

### Cell 21

```text
----- Start Learning with Linear (1600 OneHot) Q-learning -----
Episode #50 (50000 steps) -- Total reward = -1000, epsilon=0.1.
Episode #150 (144272 steps) -- Total reward = -606, epsilon=0.1.
Episode #250 (219001 steps) -- Total reward = -672, epsilon=0.1.
Episode #350 (286761 steps) -- Total reward = -490, epsilon=0.1.
Episode #450 (336702 steps) -- Total reward = -411, epsilon=0.1.
Episode #550 (389266 steps) -- Total reward = -370, epsilon=0.1.
Episode #650 (433427 steps) -- Total reward = -671, epsilon=0.1.
Episode #750 (477029 steps) -- Total reward = -472, epsilon=0.1.
Episode #850 (521521 steps) -- Total reward = -356, epsilon=0.1.
Episode #950 (561307 steps) -- Total reward = -393, epsilon=0.1.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

### Cell 24

```text
----- Start Learning with Linear (256 RBF) Q-learning -----
Episode #50 (44509 steps) -- Total reward = -627, epsilon=0.1.
Episode #150 (84187 steps) -- Total reward = -351, epsilon=0.1.
Episode #250 (110867 steps) -- Total reward = -353, epsilon=0.1.
Episode #350 (138880 steps) -- Total reward = -195, epsilon=0.1.
Episode #450 (186520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #550 (286520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #650 (386520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (486520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (586520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (686520 steps) -- Total reward = -1000, epsilon=0.1.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

### Cell 29

```text
----- Start Learning with Target (256 RBF) Q-learning -----
Episode #50 (44398 steps) -- Total reward = -433, epsilon=0.1.
Episode #150 (84325 steps) -- Total reward = -405, epsilon=0.1.
Episode #250 (108434 steps) -- Total reward = -316, epsilon=0.1.
Episode #350 (126882 steps) -- Total reward = -162, epsilon=0.1.
Episode #450 (144332 steps) -- Total reward = -158, epsilon=0.1.
Episode #550 (161679 steps) -- Total reward = -148, epsilon=0.1.
Episode #650 (179349 steps) -- Total reward = -146, epsilon=0.1.
Episode #750 (195949 steps) -- Total reward = -150, epsilon=0.1.
Episode #850 (213118 steps) -- Total reward = -293, epsilon=0.1.
Episode #950 (228619 steps) -- Total reward = -153, epsilon=0.1.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

### Cell 34

```text
----- Start Learning with Double (256 RBF) Q-learning -----
Episode #50 (43784 steps) -- Total reward = -555, epsilon=0.1.
Episode #150 (84573 steps) -- Total reward = -279, epsilon=0.1.
Episode #250 (112032 steps) -- Total reward = -185, epsilon=0.1.
Episode #350 (137944 steps) -- Total reward = -256, epsilon=0.1.
Episode #450 (162582 steps) -- Total reward = -180, epsilon=0.1.
Episode #550 (187949 steps) -- Total reward = -307, epsilon=0.1.
Episode #650 (233837 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (333837 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (433837 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (533837 steps) -- Total reward = -1000, epsilon=0.1.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

### Cell 44

```text
----- Start Learning with DQN Q-learning -----
Episode #50 (50000 steps) -- Total reward = -1000, epsilon=0.822012.
Episode #150 (150000 steps) -- Total reward = -1000, epsilon=0.551011.
Episode #250 (217290 steps) -- Total reward = -341, epsilon=0.369354.
Episode #350 (251769 steps) -- Total reward = -428, epsilon=0.247585.
Episode #450 (293727 steps) -- Total reward = -241, epsilon=0.165961.
Episode #550 (332634 steps) -- Total reward = -744, epsilon=0.111247.
Episode #650 (378965 steps) -- Total reward = -609, epsilon=0.0745713.
Episode #750 (402566 steps) -- Total reward = -194, epsilon=0.0499866.
Episode #850 (444827 steps) -- Total reward = -225, epsilon=0.033507.
Episode #950 (482567 steps) -- Total reward = -224, epsilon=0.0224604.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

### Cell 48

```text
----- Start Learning with Linear (100 RBF) Q-learning -----
Episode #50 (33947 steps) -- Total reward = -366, epsilon=0.1.
Episode #150 (81865 steps) -- Total reward = -1000, epsilon=0.1.
Episode #250 (171600 steps) -- Total reward = -1000, epsilon=0.1.
Episode #350 (271600 steps) -- Total reward = -1000, epsilon=0.1.
Episode #450 (371600 steps) -- Total reward = -1000, epsilon=0.1.
Episode #550 (471600 steps) -- Total reward = -1000, epsilon=0.1.
Episode #650 (571600 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (671600 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (771600 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (871600 steps) -- Total reward = -1000, epsilon=0.1.
  Finished 10x10
----- Start Learning with Linear (144 RBF) Q-learning -----
Episode #50 (37130 steps) -- Total reward = -479, epsilon=0.1.
Episode #150 (74593 steps) -- Total reward = -120, epsilon=0.1.
Episode #250 (153510 steps) -- Total reward = -1000, epsilon=0.1.
Episode #350 (253510 steps) -- Total reward = -1000, epsilon=0.1.
Episode #450 (353510 steps) -- Total reward = -1000, epsilon=0.1.
Episode #550 (453510 steps) -- Total reward = -1000, epsilon=0.1.
Episode #650 (553510 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (653510 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (753510 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (853510 steps) -- Total reward = -1000, epsilon=0.1.
  Finished 12x12
----- Start Learning with Linear (196 RBF) Q-learning -----
Episode #50 (40880 steps) -- Total reward = -509, epsilon=0.1.
Episode #150 (74187 steps) -- Total reward = -380, epsilon=0.1.
Episode #250 (95554 steps) -- Total reward = -219, epsilon=0.1.
Episode #350 (114490 steps) -- Total reward = -153, epsilon=0.1.
Episode #450 (132868 steps) -- Total reward = -153, epsilon=0.1.
Episode #550 (150006 steps) -- Total reward = -150, epsilon=0.1.
Episode #650 (166918 steps) -- Total reward = -149, epsilon=0.1.
Episode #750 (182991 steps) -- Total reward = -147, epsilon=0.1.
Episode #850 (199852 steps) -- Total reward = -143, epsilon=0.1.
Episode #950 (217312 steps) -- Total reward = -155, epsilon=0.1.
  Finished 14x14
----- Start Learning with Linear (256 RBF) Q-learning -----
Episode #50 (44509 steps) -- Total reward = -627, epsilon=0.1.
Episode #150 (84187 steps) -- Total reward = -351, epsilon=0.1.
Episode #250 (110867 steps) -- Total reward = -353, epsilon=0.1.
Episode #350 (138880 steps) -- Total reward = -195, epsilon=0.1.
Episode #450 (186520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #550 (286520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #650 (386520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (486520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (586520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (686520 steps) -- Total reward = -1000, epsilon=0.1.
  Finished 16x16
----- Start Learning with Linear (324 RBF) Q-learning -----
Episode #50 (47060 steps) -- Total reward = -932, epsilon=0.1.
Episode #150 (92401 steps) -- Total reward = -293, epsilon=0.1.
Episode #250 (120618 steps) -- Total reward = -199, epsilon=0.1.
Episode #350 (145223 steps) -- Total reward = -303, epsilon=0.1.
Episode #450 (168180 steps) -- Total reward = -187, epsilon=0.1.
Episode #550 (191425 steps) -- Total reward = -188, epsilon=0.1.
Episode #650 (215272 steps) -- Total reward = -192, epsilon=0.1.
Episode #750 (307558 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (407558 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (507558 steps) -- Total reward = -1000, epsilon=0.1.
  Finished 18x18
----- Start Learning with Linear (400 RBF) Q-learning -----
Episode #50 (47250 steps) -- Total reward = -956, epsilon=0.1.
Episode #150 (100066 steps) -- Total reward = -440, epsilon=0.1.
Episode #250 (131563 steps) -- Total reward = -195, epsilon=0.1.
Episode #350 (156361 steps) -- Total reward = -427, epsilon=0.1.
Episode #450 (179791 steps) -- Total reward = -190, epsilon=0.1.
Episode #550 (202812 steps) -- Total reward = -185, epsilon=0.1.
Episode #650 (225307 steps) -- Total reward = -190, epsilon=0.1.
Episode #750 (249370 steps) -- Total reward = -200, epsilon=0.1.
Episode #850 (273429 steps) -- Total reward = -210, epsilon=0.1.
Episode #950 (295654 steps) -- Total reward = -192, epsilon=0.1.
  Finished 20x20
```



```text
<Figure size 1200x500 with 1 Axes>
```

```text
More bases improve early performance but increase late-training instability,
because larger weight vectors amplify target non-stationarity in Q-learning.
```

### Cell 50

```text
----- Start Learning with Linear (256 RBF) Q-learning -----
Episode #50 (44509 steps) -- Total reward = -627, epsilon=0.1.
Episode #150 (84187 steps) -- Total reward = -351, epsilon=0.1.
Episode #250 (110867 steps) -- Total reward = -353, epsilon=0.1.
Episode #350 (138880 steps) -- Total reward = -195, epsilon=0.1.
Episode #450 (186520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #550 (286520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #650 (386520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (486520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (586520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (686520 steps) -- Total reward = -1000, epsilon=0.1.
----- Start Learning with DecayLR (256 RBF) Q-learning -----
Episode #50 (48490 steps) -- Total reward = -1000, epsilon=0.1.
Episode #150 (140830 steps) -- Total reward = -837, epsilon=0.1.
Episode #250 (231101 steps) -- Total reward = -980, epsilon=0.1.
Episode #350 (318869 steps) -- Total reward = -954, epsilon=0.1.
Episode #450 (406325 steps) -- Total reward = -1000, epsilon=0.1.
Episode #550 (492380 steps) -- Total reward = -945, epsilon=0.1.
Episode #650 (578365 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (662550 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (746753 steps) -- Total reward = -885, epsilon=0.1.
Episode #950 (827996 steps) -- Total reward = -950, epsilon=0.1.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

```text
Decaying alpha stabilises later training: once good Q-values are learned,
smaller updates prevent noisy targets from overwriting them.
```

### Cell 52

```text
----- Start Learning with Linear (256 RBF) Q-learning -----
Episode #50 (44509 steps) -- Total reward = -627, epsilon=0.1.
Episode #150 (84187 steps) -- Total reward = -351, epsilon=0.1.
Episode #250 (110867 steps) -- Total reward = -353, epsilon=0.1.
Episode #350 (138880 steps) -- Total reward = -195, epsilon=0.1.
Episode #450 (186520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #550 (286520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #650 (386520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #750 (486520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #850 (586520 steps) -- Total reward = -1000, epsilon=0.1.
Episode #950 (686520 steps) -- Total reward = -1000, epsilon=0.1.
----- Start Learning with LinearDecay(e=100) (256 RBF) Q-learning -----
Episode #50 (45544 steps) -- Total reward = -491, epsilon=0.5149.
Episode #150 (85512 steps) -- Total reward = -289, epsilon=0.01.
Episode #250 (117172 steps) -- Total reward = -190, epsilon=0.01.
Episode #350 (146260 steps) -- Total reward = -312, epsilon=0.01.
Episode #450 (203707 steps) -- Total reward = -1000, epsilon=0.01.
Episode #550 (303707 steps) -- Total reward = -1000, epsilon=0.01.
Episode #650 (403707 steps) -- Total reward = -1000, epsilon=0.01.
Episode #750 (503707 steps) -- Total reward = -1000, epsilon=0.01.
Episode #850 (603707 steps) -- Total reward = -1000, epsilon=0.01.
Episode #950 (703707 steps) -- Total reward = -1000, epsilon=0.01.
----- Start Learning with LinearDecay(e=500) (256 RBF) Q-learning -----
Episode #50 (50000 steps) -- Total reward = -1000, epsilon=0.90298.
Episode #150 (123110 steps) -- Total reward = -439, epsilon=0.70498.
Episode #250 (162836 steps) -- Total reward = -372, epsilon=0.50698.
Episode #350 (187894 steps) -- Total reward = -150, epsilon=0.30898.
Episode #450 (204751 steps) -- Total reward = -153, epsilon=0.11098.
Episode #550 (220554 steps) -- Total reward = -165, epsilon=0.01.
Episode #650 (237172 steps) -- Total reward = -223, epsilon=0.01.
Episode #750 (259780 steps) -- Total reward = -154, epsilon=0.01.
Episode #850 (274453 steps) -- Total reward = -142, epsilon=0.01.
Episode #950 (288443 steps) -- Total reward = -140, epsilon=0.01.
----- Start Learning with ExpDecay(tau=250) (256 RBF) Q-learning -----
Episode #50 (48434 steps) -- Total reward = -854, epsilon=0.822012.
Episode #150 (100993 steps) -- Total reward = -344, epsilon=0.551011.
Episode #250 (126281 steps) -- Total reward = -195, epsilon=0.369354.
Episode #350 (144905 steps) -- Total reward = -239, epsilon=0.247585.
Episode #450 (162629 steps) -- Total reward = -154, epsilon=0.165961.
Episode #550 (254280 steps) -- Total reward = -1000, epsilon=0.111247.
Episode #650 (354280 steps) -- Total reward = -1000, epsilon=0.0745713.
Episode #750 (454280 steps) -- Total reward = -1000, epsilon=0.0499866.
Episode #850 (554280 steps) -- Total reward = -1000, epsilon=0.033507.
Episode #950 (654280 steps) -- Total reward = -1000, epsilon=0.0224604.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

```text
Fast decay (100 ep): explores quickly then exploits — good if near-optimal
  policy is discoverable early, risky if the initial policy is poor.
Slow decay (500 ep): maintains exploration longer, usually more stable.
Exp decay: smooth, asymptotes to 0 — similar to DQN schedule; often best.
```

### Cell 54

```text
----- Start Learning with DQN Q-learning -----
Episode #50 (50000 steps) -- Total reward = -1000, epsilon=0.822012.
Episode #150 (149400 steps) -- Total reward = -1000, epsilon=0.551011.
Episode #250 (246196 steps) -- Total reward = -1000, epsilon=0.369354.
Episode #350 (308621 steps) -- Total reward = -337, epsilon=0.247585.
Episode #450 (336816 steps) -- Total reward = -258, epsilon=0.165961.
Episode #550 (390496 steps) -- Total reward = -250, epsilon=0.111247.
Episode #650 (425385 steps) -- Total reward = -699, epsilon=0.0745713.
Episode #750 (464973 steps) -- Total reward = -696, epsilon=0.0499866.
Episode #850 (511562 steps) -- Total reward = -323, epsilon=0.033507.
Episode #950 (549636 steps) -- Total reward = -468, epsilon=0.0224604.
----- Start Learning with DQN-Deep(Adam) Q-learning -----
Episode #50 (50000 steps) -- Total reward = -1000, epsilon=0.822012.
Episode #150 (150000 steps) -- Total reward = -1000, epsilon=0.551011.
Episode #250 (247538 steps) -- Total reward = -1000, epsilon=0.369354.
Episode #350 (337910 steps) -- Total reward = -1000, epsilon=0.247585.
Episode #450 (401918 steps) -- Total reward = -357, epsilon=0.165961.
Episode #550 (450146 steps) -- Total reward = -711, epsilon=0.111247.
Episode #650 (499312 steps) -- Total reward = -511, epsilon=0.0745713.
Episode #750 (545751 steps) -- Total reward = -540, epsilon=0.0499866.
Episode #850 (592893 steps) -- Total reward = -286, epsilon=0.033507.
Episode #950 (653940 steps) -- Total reward = -163, epsilon=0.0224604.
```

```text
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:46: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_xticklabels(["%g" % (env_low[0] + i * (env_high[0] - env_low[0]) / 5) for i in range(6)])
C:\Users\Prathap Selvakumar\AppData\Local\Temp\ipykernel_23456\1509883902.py:48: UserWarning: set_ticklabels() should only be used with a fixed number of ticks, i.e. after set_ticks() or using a FixedLocator.
  ax.set_yticklabels(["%g" % (env_low[1] + i * (env_high[1] - env_low[1]) / 5) for i in range(6)])
```



```text
<Figure size 1600x750 with 5 Axes>
```

```text
Deeper networks + Adam converge faster on MountainCar but can overfit noisy
replay samples. Tuning target_update_freq and batch_size matters most.
```

### Cell 56

```text
Evaluating 'Tabular 40x40' over 10 seeds ...
Evaluating 'Linear RBF 16x16' over 10 seeds ...
```

## MARL

### Cell 0

```text
'pip' is not recognized as an internal or external command,
operable program or batch file.
```

### Cell 1

### Cell 6

### Cell 7

```text
Reward  0.0
[[ 0.  0.  0.  0.]
 [ 0.  0.  0.  0.]
 [ 0.  0.  2.  1.]
 [-1.  0.  0.  0.]]
```

### Cell 17

```text
----- Start Learning with SingleLearner, 2 agents -----
Epoch 1: time = 0.87
Train: reward = -0.20 -- Captures/1000 = 0.20
Eval: reward = -0.15 -- Captures/1000 = 0.70
{'table_size': 240250}
Epoch 2: time = 0.84
Train: reward = -0.11 -- Captures/1000 = 2.20
Eval: reward = 0.10 -- Captures/1000 = 7.85
{'table_size': 242600}
Epoch 3: time = 0.85
Train: reward = 0.31 -- Captures/1000 = 14.06
Eval: reward = 0.24 -- Captures/1000 = 7.50
{'table_size': 242725}
Epoch 4: time = 0.83
Train: reward = 0.65 -- Captures/1000 = 22.82
Eval: reward = 1.26 -- Captures/1000 = 40.05
{'table_size': 242775}
Epoch 5: time = 0.93
Train: reward = 0.83 -- Captures/1000 = 27.66
Eval: reward = 1.22 -- Captures/1000 = 35.45
{'table_size': 242900}
Epoch 6: time = 1.35
Train: reward = 0.79 -- Captures/1000 = 26.46
Eval: reward = 1.58 -- Captures/1000 = 48.00
{'table_size': 243025}
Epoch 7: time = 0.94
Train: reward = 0.75 -- Captures/1000 = 25.80
Eval: reward = 1.87 -- Captures/1000 = 56.40
{'table_size': 243050}
Epoch 8: time = 0.93
Train: reward = 0.71 -- Captures/1000 = 23.36
Eval: reward = 0.47 -- Captures/1000 = 14.20
{'table_size': 243100}
Epoch 9: time = 0.88
Train: reward = 0.76 -- Captures/1000 = 25.28
Eval: reward = 0.00 -- Captures/1000 = 0.00
{'table_size': 243100}
Epoch 10: time = 1.03
Train: reward = 0.82 -- Captures/1000 = 26.92
Eval: reward = 0.60 -- Captures/1000 = 17.05
{'table_size': 243125}
Epoch 11: time = 0.98
Train: reward = 0.52 -- Captures/1000 = 18.22
Eval: reward = 0.01 -- Captures/1000 = 0.25
{'table_size': 243125}
Epoch 12: time = 1.03
Train: reward = 0.87 -- Captures/1000 = 28.22
Eval: reward = 1.75 -- Captures/1000 = 51.85
{'table_size': 243125}
Epoch 13: time = 1.08
Train: reward = 0.62 -- Captures/1000 = 20.72
Eval: reward = 0.00 -- Captures/1000 = 0.00
{'table_size': 243175}
Epoch 14: time = 1.15
Train: reward = 0.82 -- Captures/1000 = 27.00
Eval: reward = 0.93 -- Captures/1000 = 27.35
{'table_size': 243250}
Epoch 15: time = 1.01
Train: reward = 0.72 -- Captures/1000 = 24.22
Eval: reward = 0.01 -- Captures/1000 = 0.25
{'table_size': 243275}
Epoch 16: time = 1.12
Train: reward = 0.87 -- Captures/1000 = 28.56
Eval: reward = 1.71 -- Captures/1000 = 49.00
{'table_size': 243275}
Epoch 17: time = 1.22
Train: reward = 1.01 -- Captures/1000 = 31.90
Eval: reward = 1.71 -- Captures/1000 = 50.65
{'table_size': 243325}
Epoch 18: time = 1.14
Train: reward = 0.87 -- Captures/1000 = 27.92
Eval: reward = 1.69 -- Captures/1000 = 50.45
{'table_size': 243350}
Epoch 19: time = 1.05
Train: reward = 0.95 -- Captures/1000 = 30.48
Eval: reward = 1.65 -- Captures/1000 = 47.95
{'table_size': 243475}
Epoch 20: time = 1.09
Train: reward = 0.86 -- Captures/1000 = 28.46
Eval: reward = 1.71 -- Captures/1000 = 49.70
{'table_size': 243500}
```



```text
<Figure size 1400x500 with 2 Axes>
```

### Cell 19

```text
----- Start Learning with SingleLearner, 2 agents -----
Epoch 1: time = 1.11
Train: reward = 1.57 -- Captures/1000 = 64.36
Eval: reward = 2.93 -- Captures/1000 = 108.90
{'table_size': 5900}
Epoch 2: time = 1.18
Train: reward = 2.24 -- Captures/1000 = 86.18
Eval: reward = 2.82 -- Captures/1000 = 97.55
{'table_size': 6000}
Epoch 3: time = 1.04
Train: reward = 1.94 -- Captures/1000 = 75.48
Eval: reward = 0.94 -- Captures/1000 = 34.20
{'table_size': 6000}
Epoch 4: time = 0.96
Train: reward = 1.73 -- Captures/1000 = 68.42
Eval: reward = 1.96 -- Captures/1000 = 77.85
{'table_size': 6000}
Epoch 5: time = 0.92
Train: reward = 2.00 -- Captures/1000 = 75.26
Eval: reward = 2.21 -- Captures/1000 = 81.40
{'table_size': 6000}
```



```text
<Figure size 2100x500 with 3 Axes>
```

### Cell 22

```text
----- Start Learning with SingleLearner, 3 agents -----
Epoch 1: time = 2.85
Train: reward = 2.32 -- Captures/1000 = 113.98
Eval: reward = 4.43 -- Captures/1000 = 150.15
{'table_size': 364375}
Epoch 2: time = 2.86
Train: reward = 3.45 -- Captures/1000 = 128.72
Eval: reward = 4.48 -- Captures/1000 = 152.80
{'table_size': 379125}
Epoch 3: time = 2.83
Train: reward = 3.62 -- Captures/1000 = 132.30
Eval: reward = 4.36 -- Captures/1000 = 150.70
{'table_size': 389125}
Epoch 4: time = 2.85
Train: reward = 3.75 -- Captures/1000 = 135.36
Eval: reward = 4.66 -- Captures/1000 = 155.25
{'table_size': 397875}
Epoch 5: time = 2.79
Train: reward = 3.63 -- Captures/1000 = 132.28
Eval: reward = 4.35 -- Captures/1000 = 149.05
{'table_size': 402250}
----- Start Learning with SingleLearner, 4 agents -----
Epoch 1: time = 12.23
Train: reward = -1.39 -- Captures/1000 = 90.68
Eval: reward = 0.14 -- Captures/1000 = 126.00
{'table_size': 17691250}
Epoch 2: time = 12.44
Train: reward = 1.20 -- Captures/1000 = 145.80
Eval: reward = 2.77 -- Captures/1000 = 173.85
{'table_size': 20688125}
Epoch 3: time = 13.16
Train: reward = 3.00 -- Captures/1000 = 172.14
Eval: reward = 4.77 -- Captures/1000 = 202.05
{'table_size': 21671875}
Epoch 4: time = 13.10
Train: reward = 4.17 -- Captures/1000 = 186.24
Eval: reward = 5.58 -- Captures/1000 = 211.10
{'table_size': 22138125}
Epoch 5: time = 12.33
Train: reward = 4.78 -- Captures/1000 = 192.68
Eval: reward = 6.22 -- Captures/1000 = 219.85
{'table_size': 22439375}
```



```text
<Figure size 3500x500 with 5 Axes>
```

### Cell 29

```text
----- Start Learning with IQL: TabularQLearner, 2 agents -----
Epoch 1: time = 0.93
Train: reward = -0.18 -- Captures/1000 = 0.10
Eval: reward = -0.14 -- Captures/1000 = 0.15
{'table_size': 96400}
Epoch 2: time = 0.90
Train: reward = -0.11 -- Captures/1000 = 0.50
Eval: reward = -0.05 -- Captures/1000 = 1.35
{'table_size': 97060}
Epoch 3: time = 0.98
Train: reward = 0.06 -- Captures/1000 = 5.26
Eval: reward = 0.71 -- Captures/1000 = 22.15
{'table_size': 97090}
Epoch 4: time = 0.88
Train: reward = 0.70 -- Captures/1000 = 24.64
Eval: reward = 0.29 -- Captures/1000 = 8.30
{'table_size': 97100}
Epoch 5: time = 0.89
Train: reward = 0.82 -- Captures/1000 = 27.84
Eval: reward = 1.95 -- Captures/1000 = 57.65
{'table_size': 97100}
Epoch 6: time = 0.88
Train: reward = 0.78 -- Captures/1000 = 26.52
Eval: reward = 0.77 -- Captures/1000 = 22.45
{'table_size': 97140}
Epoch 7: time = 0.88
Train: reward = 0.86 -- Captures/1000 = 28.04
Eval: reward = 1.07 -- Captures/1000 = 31.35
{'table_size': 97170}
Epoch 8: time = 0.88
Train: reward = 0.95 -- Captures/1000 = 30.88
Eval: reward = 2.13 -- Captures/1000 = 62.60
{'table_size': 97180}
Epoch 9: time = 1.26
Train: reward = 0.90 -- Captures/1000 = 29.50
Eval: reward = 0.03 -- Captures/1000 = 0.75
{'table_size': 97190}
Epoch 10: time = 1.09
Train: reward = 0.84 -- Captures/1000 = 27.68
Eval: reward = 1.01 -- Captures/1000 = 30.10
{'table_size': 97200}
Epoch 11: time = 1.29
Train: reward = 0.92 -- Captures/1000 = 30.62
Eval: reward = 0.09 -- Captures/1000 = 2.75
{'table_size': 97230}
Epoch 12: time = 0.97
Train: reward = 1.01 -- Captures/1000 = 32.76
Eval: reward = 1.80 -- Captures/1000 = 52.90
{'table_size': 97260}
Epoch 13: time = 0.92
Train: reward = 0.96 -- Captures/1000 = 30.38
Eval: reward = 0.58 -- Captures/1000 = 17.00
{'table_size': 97270}
Epoch 14: time = 1.02
Train: reward = 0.84 -- Captures/1000 = 27.40
Eval: reward = 0.63 -- Captures/1000 = 19.05
{'table_size': 97270}
Epoch 15: time = 0.98
Train: reward = 1.13 -- Captures/1000 = 36.10
Eval: reward = 0.29 -- Captures/1000 = 8.80
{'table_size': 97280}
Epoch 16: time = 0.88
Train: reward = 0.98 -- Captures/1000 = 31.68
Eval: reward = 0.00 -- Captures/1000 = 0.00
{'table_size': 97290}
Epoch 17: time = 0.95
Train: reward = 1.00 -- Captures/1000 = 32.06
Eval: reward = 2.05 -- Captures/1000 = 62.50
{'table_size': 97310}
Epoch 18: time = 0.89
Train: reward = 1.12 -- Captures/1000 = 35.56
Eval: reward = 0.00 -- Captures/1000 = 0.10
{'table_size': 97330}
Epoch 19: time = 0.88
Train: reward = 1.01 -- Captures/1000 = 32.26
Eval: reward = 2.05 -- Captures/1000 = 61.15
{'table_size': 97340}
Epoch 20: time = 0.86
Train: reward = 1.15 -- Captures/1000 = 36.62
Eval: reward = 0.85 -- Captures/1000 = 25.00
{'table_size': 97390}
```



```text
<Figure size 4200x500 with 6 Axes>
```

### Cell 31

```text
----- Start Learning with IQL: TabularQLearner, 2 agents -----
Epoch 1: time = 0.95
Train: reward = 1.49 -- Captures/1000 = 63.62
Eval: reward = 0.31 -- Captures/1000 = 11.10
{'table_size': 2340}
Epoch 2: time = 0.91
Train: reward = 1.33 -- Captures/1000 = 57.18
Eval: reward = 3.26 -- Captures/1000 = 113.65
{'table_size': 2400}
Epoch 3: time = 1.15
Train: reward = 1.79 -- Captures/1000 = 72.34
Eval: reward = 3.24 -- Captures/1000 = 117.50
{'table_size': 2400}
Epoch 4: time = 1.01
Train: reward = 1.81 -- Captures/1000 = 74.26
Eval: reward = 3.34 -- Captures/1000 = 122.05
{'table_size': 2400}
Epoch 5: time = 1.01
Train: reward = 2.20 -- Captures/1000 = 87.92
Eval: reward = 3.14 -- Captures/1000 = 111.95
{'table_size': 2400}
```



```text
<Figure size 4900x500 with 7 Axes>
```

### Cell 34

```text
----- Start Learning with IQL: TabularQLearner, 3 agents -----
Epoch 1: time = 1.55
Train: reward = 1.96 -- Captures/1000 = 100.30
Eval: reward = 5.08 -- Captures/1000 = 164.15
{'table_size': 43770}
Epoch 2: time = 1.49
Train: reward = 3.63 -- Captures/1000 = 132.04
Eval: reward = 5.65 -- Captures/1000 = 178.80
{'table_size': 45285}
Epoch 3: time = 1.45
Train: reward = 3.76 -- Captures/1000 = 134.92
Eval: reward = 6.16 -- Captures/1000 = 189.15
{'table_size': 46410}
Epoch 4: time = 1.43
Train: reward = 3.96 -- Captures/1000 = 137.08
Eval: reward = 6.18 -- Captures/1000 = 188.10
{'table_size': 47175}
Epoch 5: time = 1.46
Train: reward = 3.96 -- Captures/1000 = 137.16
Eval: reward = 6.05 -- Captures/1000 = 185.90
{'table_size': 47700}
----- Start Learning with IQL: TabularQLearner, 4 agents -----
Epoch 1: time = 1.97
Train: reward = -1.61 -- Captures/1000 = 84.00
Eval: reward = 0.02 -- Captures/1000 = 118.15
{'table_size': 568740}
Epoch 2: time = 2.77
Train: reward = 0.69 -- Captures/1000 = 129.10
Eval: reward = 2.80 -- Captures/1000 = 167.60
{'table_size': 664440}
Epoch 3: time = 2.48
Train: reward = 2.32 -- Captures/1000 = 151.98
Eval: reward = 4.65 -- Captures/1000 = 194.50
{'table_size': 693180}
Epoch 4: time = 2.99
Train: reward = 3.56 -- Captures/1000 = 169.80
Eval: reward = 5.88 -- Captures/1000 = 213.80
{'table_size': 707820}
Epoch 5: time = 2.38
Train: reward = 4.31 -- Captures/1000 = 180.72
Eval: reward = 6.52 -- Captures/1000 = 224.15
{'table_size': 717600}
```



```text
<Figure size 6300x500 with 9 Axes>
```

### Cell 42

```text
----- Start Learning with IQL: HystereticQLearner, 2 agents -----
Epoch 1: time = 1.02
Train: reward = -0.18 -- Captures/1000 = 0.10
Eval: reward = -0.14 -- Captures/1000 = 0.15
{'table_size': 96400}
Epoch 2: time = 1.17
Train: reward = -0.11 -- Captures/1000 = 0.66
Eval: reward = -0.05 -- Captures/1000 = 1.70
{'table_size': 97040}
Epoch 3: time = 1.14
Train: reward = 0.08 -- Captures/1000 = 5.84
Eval: reward = 0.79 -- Captures/1000 = 25.00
{'table_size': 97100}
Epoch 4: time = 1.15
Train: reward = 0.79 -- Captures/1000 = 27.12
Eval: reward = 1.90 -- Captures/1000 = 56.25
{'table_size': 97180}
Epoch 5: time = 1.11
Train: reward = 1.24 -- Captures/1000 = 40.22
Eval: reward = 1.13 -- Captures/1000 = 32.75
{'table_size': 97220}
Epoch 6: time = 1.04
Train: reward = 0.93 -- Captures/1000 = 32.32
Eval: reward = 2.24 -- Captures/1000 = 66.45
{'table_size': 97240}
Epoch 7: time = 0.98
Train: reward = 1.11 -- Captures/1000 = 36.78
Eval: reward = 0.17 -- Captures/1000 = 5.10
{'table_size': 97250}
Epoch 8: time = 0.98
Train: reward = 1.27 -- Captures/1000 = 41.66
Eval: reward = 2.23 -- Captures/1000 = 66.60
{'table_size': 97260}
Epoch 9: time = 1.00
Train: reward = 1.06 -- Captures/1000 = 35.70
Eval: reward = 1.94 -- Captures/1000 = 58.00
{'table_size': 97300}
Epoch 10: time = 1.00
Train: reward = 1.00 -- Captures/1000 = 34.04
Eval: reward = 1.89 -- Captures/1000 = 55.55
{'table_size': 97310}
Epoch 11: time = 0.99
Train: reward = 0.89 -- Captures/1000 = 30.72
Eval: reward = 2.04 -- Captures/1000 = 61.20
{'table_size': 97350}
Epoch 12: time = 0.92
Train: reward = 1.17 -- Captures/1000 = 38.32
Eval: reward = 1.95 -- Captures/1000 = 58.05
{'table_size': 97350}
Epoch 13: time = 1.01
Train: reward = 1.26 -- Captures/1000 = 41.72
Eval: reward = 2.18 -- Captures/1000 = 66.45
{'table_size': 97370}
Epoch 14: time = 1.08
Train: reward = 1.22 -- Captures/1000 = 40.10
Eval: reward = 2.38 -- Captures/1000 = 70.50
{'table_size': 97380}
Epoch 15: time = 1.07
Train: reward = 1.23 -- Captures/1000 = 41.20
Eval: reward = 2.29 -- Captures/1000 = 68.45
{'table_size': 97390}
Epoch 16: time = 0.91
Train: reward = 1.24 -- Captures/1000 = 41.02
Eval: reward = 2.49 -- Captures/1000 = 72.95
{'table_size': 97450}
Epoch 17: time = 0.88
Train: reward = 1.33 -- Captures/1000 = 44.04
Eval: reward = 2.39 -- Captures/1000 = 71.05
{'table_size': 97480}
Epoch 18: time = 0.92
Train: reward = 1.29 -- Captures/1000 = 43.64
Eval: reward = 2.49 -- Captures/1000 = 73.60
{'table_size': 97560}
Epoch 19: time = 0.94
Train: reward = 1.28 -- Captures/1000 = 42.48
Eval: reward = 2.31 -- Captures/1000 = 70.45
{'table_size': 97570}
Epoch 20: time = 1.04
Train: reward = 1.11 -- Captures/1000 = 38.38
Eval: reward = 2.16 -- Captures/1000 = 67.80
{'table_size': 97600}
```



```text
<Figure size 1400x500 with 2 Axes>
```

### Cell 43

```text
----- Start Learning with IQL: HystereticQLearner, 2 agents -----
Epoch 1: time = 0.97
Train: reward = 1.79 -- Captures/1000 = 74.86
Eval: reward = 2.97 -- Captures/1000 = 106.75
{'table_size': 2390}
Epoch 2: time = 0.95
Train: reward = 2.46 -- Captures/1000 = 98.66
Eval: reward = 3.88 -- Captures/1000 = 144.15
{'table_size': 2400}
Epoch 3: time = 1.00
Train: reward = 2.55 -- Captures/1000 = 107.32
Eval: reward = 4.55 -- Captures/1000 = 161.00
{'table_size': 2400}
Epoch 4: time = 1.07
Train: reward = 2.74 -- Captures/1000 = 114.22
Eval: reward = 3.88 -- Captures/1000 = 155.15
{'table_size': 2400}
Epoch 5: time = 1.02
Train: reward = 3.11 -- Captures/1000 = 126.30
Eval: reward = 4.74 -- Captures/1000 = 171.20
{'table_size': 2400}
```



```text
<Figure size 2100x500 with 3 Axes>
```

## POMDP

### Cell 7



```text
<Figure size 640x480 with 1 Axes>
```

### Cell 17

```text
Text(0, 0.5, 'Belief to be in state one after update')
```



```text
<Figure size 640x480 with 1 Axes>
```

### Cell 20

```text
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: numpy in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (2.2.6)
Requirement already satisfied: matplotlib in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (3.10.7)
Requirement already satisfied: contourpy>=1.0.1 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (1.3.3)
Requirement already satisfied: cycler>=0.10 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (0.12.1)
Requirement already satisfied: fonttools>=4.22.0 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (4.62.1)
Requirement already satisfied: kiwisolver>=1.3.1 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (1.5.0)
Requirement already satisfied: packaging>=20.0 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (26.0)
Requirement already satisfied: pillow>=8 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (12.0.0)
Requirement already satisfied: pyparsing>=3 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (3.3.2)
Requirement already satisfied: python-dateutil>=2.7 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from matplotlib) (2.9.0.post0)
Requirement already satisfied: six>=1.5 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from python-dateutil>=2.7->matplotlib) (1.17.0)
```

```text

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

### Cell 21



```text
<Figure size 640x480 with 1 Axes>
```

### Cell 29

```text
Defaulting to user installation because normal site-packages is not writeable
Collecting git+https://github.com/pemami4911/POMDPy.git
  Cloning https://github.com/pemami4911/POMDPy.git to c:\users\prathap selvakumar\appdata\local\temp\pip-req-build-l4b5tdcg
  Resolved https://github.com/pemami4911/POMDPy.git to commit ffa74ad627aade19cfa1773b01305e7736b2044d
  Preparing metadata (setup.py): started
  Preparing metadata (setup.py): finished with status 'done'
```

```text
  Running command git clone --filter=blob:none --quiet https://github.com/pemami4911/POMDPy.git 'C:\Users\Prathap Selvakumar\AppData\Local\Temp\pip-req-build-l4b5tdcg'

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

```text
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: future in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (1.0.0)
```

```text

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

```text
Defaulting to user installation because normal site-packages is not writeable
Requirement already satisfied: scipy in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (1.15.3)
Requirement already satisfied: numpy<2.5,>=1.23.5 in c:\users\prathap selvakumar\appdata\roaming\python\python311\site-packages (from scipy) (2.2.6)
```

```text

[notice] A new release of pip available: 22.3 -> 26.1.1
[notice] To update, run: python.exe -m pip install --upgrade pip
```

### Cell 31

```text
{'discount': 1,
 'env': 'Tiger',
 'max_steps': 1,
 'n_epochs': 1,
 'planning_horizon': 1,
 'save': True,
 'solver': 'ValueIteration'}
[Value Iteration] planning horizon 0...
agent - Step Number = 0
agent - Step Result.Action = Listening
agent - Step Result.Observation = Roaring is heard coming from door 2
agent - Step Result.Reward = -1.0
======================================================================
	Epoch #1 RESULTS
======================================================================
agent - discounted return statistics
==========================================
Name =  discounted return
Running Total =  -1.0
Mean =  -1.0
Count =  1.0
Variance =  0.0
Max =  -1.0
Min =  -1.0
==========================================
agent - undiscounted return statistics
==========================================
Name =  undiscounted return
Running Total =  -1.0
Mean =  -1.0
Count =  1.0
Variance =  0.0
Max =  -1.0
Min =  -1.0
==========================================
agent - Time
==========================================
Name =  Time
Running Total =  0.014999151229858398
Mean =  0.014999151229858398
Count =  1.0
Variance =  0.0
Max =  0.014999151229858398
Min =  0.014999151229858398
==========================================
agent - Total possible undiscounted return: 10
==========================================
  [*] save ./VI_planning_horizon_1.pkl
   [-] save_pkl : 0.00100 sec


agent - epochs: 1
agent - ave undiscounted return/step: -1.0 +- 0.0
agent - ave discounted return/step: -1.0 +- 0.0
agent - ave time/epoch: 0.014999151229858398
```

### Cell 32

```text
There are 3 alpha-vectors
{'action': 0, 'v': array([-1., -1.])}
{'action': 2, 'v': array([ 10., -20.])}
{'action': 1, 'v': array([-20.,  10.])}
```

```text
Text(0, 0.5, 'Value')
```



```text
<Figure size 640x480 with 1 Axes>
```

