
## Welcome to Model Learners Page
![teias-logo](logo.jpeg)


# People
## Professors:
- [Prof. Mohammad Reza Mousavi](https://www.nms.kcl.ac.uk/mohammad.mousavi/)
- [Prof. Hossein Hojjat](https://scholar.google.com/citations?user=hkfVNCMAAAAJ&hl=en)

## Research Interns:
- [Amin Asadi Sarijalou](https://sites.google.com/view/aasadi)
- [Rasta Tadayon Tahmasebi](https://www.linkedin.com/in/rasta-tadayon-95b6381b0/?originalSubdomain=ir)
- [Alireza Salemi](https://www.linkedin.com/in/alireza-salemi-33b068166/)
- [Zahra Hoseini](#)

# What we have Done:
# Foundations
- Two main techniques which we studied both to know which, each of us prefer to research on:
    - model checking:
        - slides (Dr. Hojjat University slides): [I](./slides/model-checking/model-checking-I.pdf), [II](./slides/model-checking/model-checking-II.pdf),  [III](./slides/model-checking/model-checking-III.pdf)

    - model based testing:
        - slides (Dr. Mousavi University slides): [I](./slides/model-testing/model-testing/I.pdf), [II](./slides/model-testing/model-testing/II.pdf)
        -book(for further study): [[2]](#2)

# Automata Learning
- Angluin L* algorithm for model learning:   
    - paper: [[1]](#1)

    after learning the algorithm we applied it on the `A1` machine on page 2 of [this slides](slides/model-learning/example.pdf)
- TTT :
    - paper: [[9]](#9)
    
    Another automata learning algorithm that was reviewed was the TTT algorithm. What distinguishes TTT from the Angluin L* anlgorithm is its its redundancy-free organization of observations, which can be exploited to achieve optimal linear space complexity.

- Active Learning of Decomposable Systems:
    - paper: [[11]](#11)

A big problem with active learning is that it is very difficult to learn large models and learning models with tens of thousands of states becomes exceptionally resource intensive. In this type of learning models the system is divided into separate components and each component is learned individually. The final learned model is the synchronous product of all the separately learned components.


- As you may have noticed, model of a particular product changes over time. For example a product might be added a feature, or it may have a bug fix. One naive approach is that we build a new model from scratch which obviously is not efficient. So we learnt adaptive model learning methods; i.e `dynamic model learning` and `partial dynamic model learning` which are more efficient as they initially exploit observation table of the old version.
    - papers:
        - [[7]](#7)
            - summary slides: [A summary of: Learning to reuse](https://docs.google.com/presentation/d/1gA5HldYD19wi4Ijqj3cbZ1UOzVpfg2hTCNxbf-EGMx8/edit?usp=sharing)
        - [[8]](#8)  
            - summary slides: [A summary of : Model Inference and Testing](https://docs.google.com/presentation/d/1IK91ROipATUKnb56KnsaRYO6YE0InFeNNtjJVDT--Jc/edit?usp=sharing)
    - example slides: [Dynamic L* example](https://docs.google.com/presentation/d/1TsxvXI29YDuJqBCA85kdCt70adTCrWexqGwoWEFonsc/edit?usp=sharing)




# Software Product Lines
- `Transition Systems` and an efficient varient of them called `Featured Transition Systems` and their model checking algorithm.
    - papers:
        - [[3]](#3)
            - summary slides: [A Summary of Model Checking Lots of Systems](https://docs.google.com/presentation/d/1o_400OjO8IQ_RW6Xj8WPRqbADjHz-D9vqCa2MXJWUu0/edit?usp=sharing)
        Model checking of `Featured Transition Systems` use `sequential product` of transition systems. These slides have some examples of this notion which we reviwed in one of the meetings.
            - (main reference for formal definitions) [[4]](#4)
    

- Besides `Featured Transition Systems` as a family-based technique for model checking, we studied FFSMs which is another family-based technique:
    - paper: [[6]](#6)
        - summary slides: [A Summary of: Learning from Difference](https://docs.google.com/presentation/d/1MtuBS8VZLO1WrsRabmS5_GzB0YWfE6oq0N-S7Go-VsU/edit?usp=sharing)

- As a research problem we were curious whether it is possible to remove priority operator from `Featured Transition Systems` definition or not. We needed to learn how to write formal and precise proofs. We read [[5]](#5) about strutured proofs. Here is it's [summary](https://docs.google.com/presentation/d/1ZV77QDbM9EYCSbzcB-Ek_q228Hl7tRvpaQXUUy81O7Y/edit?usp=sharing) slides.



# References
#### [1] 
#### Broy, M., Jonsson, B., Katoen, J., Leucker, M., & Pretschner, A. (2005). Model-Based Testing of Reactive Systems: Advanced Lectures (Lecture Notes in Computer Science (3472)) (2005th ed.). Springer.

#### [2] 
#### Vaandrager, F. (2017). Model learning. Communications of the ACM, 60(2), 86–95. [https://doi.org/10.1145/2967606](https://doi.org/10.1145/2967606)

#### [3]
#### Damasceno, C. D. N., Mousavi, M. R., & da Silva Simao, A. (2019). Learning to Reuse: Adaptive Model Learning for Evolving Systems. Lecture Notes in Computer Science, 138–156. [https://doi.org/10.1007/978-3-030-34968-4_8](https://doi.org/10.1007/978-3-030-34968-4_8)

#### [4]
#### Naeem Irfan, M., Oriat, C., & Groz, R. (2013). Model Inference and Testing. Advances in Computers, 89–139. [https://doi.org/10.1016/b978-0-12-408094-2.00003-5](https://doi.org/10.1016/b978-0-12-408094-2.00003-5)

#### [5]
#### Classen, A., Cordy, M., Schobbens, P.-Y., Heymans, P., Legay, A., & Raskin, J.-F. (2013). Featured Transition Systems: Foundations for Verifying Variability-Intensive Systems and Their Application to LTL Model Checking. IEEE Transactions on Software Engineering, 39(8), 1069–1089. [https://doi.org/10.1109/tse.2012.86](https://doi.org/10.1109/tse.2012.86)


#### [6]
#### Schobbens, P.-Y., Heymans, P., Trigaux, J.-C., & Bontemps, Y. (2007). Generic semantics of feature diagrams. Computer Networks, 51(2), 456–479. [https://doi.org/10.1016/j.comnet.2006.08.008](https://doi.org/10.1016/j.comnet.2006.08.008)


#### [7]
#### Damasceno, C. D. N., Mousavi, M. R., & Simao, A. (2019). Learning from difference. Proceedings of the 23rd International Systems and Software Product Line Conference - Volume A - SPLC ’19, 1–11. [https://doi.org/10.1145/3336294.3336307](https://doi.org/10.1145/3336294.3336307)

#### [8]
#### Lamport, L. (1995). How to Write a Proof. The American Mathematical Monthly, 102(7), 600. [https://doi.org/10.2307/2974556](https://doi.org/10.2307/2974556)

#### [9]
#### Isberner, M., Howar, F., &amp; Steffen, B. (2014). The TTT Algorithm: A Redundancy-Free Approach to Active Automata Learning. Runtime Verification Lecture Notes in Computer Science, 307-322. [https://doi.org/10.1007/978-3-319-11164-3_26](https://doi.org/10.1007/978-3-319-11164-3_26)

#### [10]
#### Heymans, P., Schobbens, P., Trigaux, J., Bontemps, Y., Matulevičius, R., &amp; Classen, A. (2008). Evaluating formal properties of feature diagram languages. IET Software, 2(3), 281. [https://doi.org/10.1049/iet-sen:20070055](https://doi.org/10.1049/iet-sen:20070055)

#### [11]
#### Duhaiby, O. A., &amp; Groote, J. F. (2020). Active Learning of Decomposable Systems. Proceedings of the 8th International Conference on Formal Methods in Software Engineering. [https://doi.org/10.1145/3372020.3391560](https://doi.org/10.1145/3372020.3391560)


#### [12]
#### Sanchez, L., Groote, J. F., &amp; Schiffelers, R. R. (2019). Active Learning of Industrial Software with Data. Fundamentals of Software Engineering Lecture Notes in Computer Science, 95-110. [https://doi.org/10.1007/978-3-030-31517-7_7](https://doi.org/10.1007/978-3-030-31517-7_7)

#### [13]
#### Duhaiby, O. A., &amp; Groote, J. F. (2019). Distribution of Behaviour into Parallel Communicating Subsystems. Electronic Proceedings in Theoretical Computer Science, 300, 54-68. [https://doi.org/10.4204/eptcs.300.4](https://doi.org/10.4204/eptcs.300.4)

#### [14]
#### Duhaiby, O. A., Mooij, A., Wezep, H. V., &amp; Groote, J. F. (2018). Pitfalls in Applying Model Learning to Industrial Legacy Software. Lecture Notes in Computer Science Leveraging Applications of Formal Methods, Verification and Validation. Industrial Practice, 121-138. [https://doi.org/10.1007/978-3-030-03427-6_13](https://doi.org/10.1007/978-3-030-03427-6_13)
