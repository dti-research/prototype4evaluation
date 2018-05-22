- [x] Environment: Cartpole, Acrobot, Lunar Lander Discrete 
- [x] Metrics for evaluation: How quickly , Best 100 episode performance, Episodes before you solve 
- [ ] Action Items 
  - [ ]  **First Milestone**
      - [ ]  Take our existing simple algoroithm implementations and test it on each of these environments 
            - [ ] Khimya uploads DYNAQ, LSTD-lambda, Q-Learning
            - [ ] Zaf uploads Vanilla Policy Gradient
            - [ ] Andre uploads the AC with Eligibility traces
      - [ ] Goal1: How do I go about comparing these algorithms - reproducibility in evaluation 
            - [ ] Set up a demonstrative Evaluation Pipeline - plug these algorithms in and test to show this case-study. Document this case-study - what are the problems one faces while comparing algorithm performances etc.
            
  - [ ]  **Second Milestone**
       - [ ]  Real world, code bases are not so simple to reproduce so need abstraction via wrappers for test bench
            - [ ] Each algorithm gets wrapped in a way it can be just ran by the test bench without knowing what is inside the algo
            - [ ] Arguments are environment, metric to evaluate on, epochs, episodes, etc. 
       - [ ] Goal2: Prototype of an evaluation pipeline which Alice, Bob, and Rob go-to to evaluate different algorithms which follow the formats of wrappers..