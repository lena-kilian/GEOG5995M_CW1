### Brief Outline

This model is part of an assessment for [GEOG5995](http://www.geog.leeds.ac.uk/courses/computing/study/core-python-phd/index.html). It creates *n* agents, which are located randomly on a 300 x 300 grid. In this example the agents represent sheep, which will move around and interact with an imported environment, as well as each other. 

The code here mostly follows [these practicals](http://www.geog.leeds.ac.uk/courses/computing/study/core-python-phd/assessment1/index.html). However, some changes were made, including the way in which agents move around the environment. Changes are commented on throughout the code. 

### Relevant Files

|File Name|Description|
|-|-|
|agent_framework.py|Contains the agent class|
|animation.py|Contains the final model, which when run produces an animated chart of the agents' movements and environment|
|in_example.txt|Contains the raster data for the environment|
|mock_framework.py|Contains an un-randomised version of agent_framework.py, which can be used for testing|
|test_abm.py|Contains test functions for mock_framework.py|


The files must be run in the following order:
1. agent_framework.py 
2. mock_framework.py
3. test_abm.py
4. animation.py

The file in_example.txt is needed to run animation.py. 

