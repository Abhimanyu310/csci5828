# CSCI 5828 - Foundations of Software Engineering
### Homework 1
###### Submitted by : Abhimanyu Ambastha


### Solution:


---

#### Essential Difficulties

* Essential difficulties, according to Brooks, are inherent in the nature of software. This means that these difficulties are not easy to do away with. This does not necessarily mean a lack of innovation but instead, it deals with the difficulties of working with software.
* Brooks uses hardware progress to compare software progress. Where in recent years, we have seen orders of magnitudes of 
improvement in performance price gain, we cannot expect the same rate of progress out of software technology.
* Software comprises of a lot of complex tecnologies working together like relations, algorithms and functions. This is the very reason that building a software to be hard and thus cannot replicate the progress achieved by its hardware counterparts.
* For example, understanding the concept behind the software is the most important part of software development. When the client provides arbitrary specifications, and the developers do not communicate properly to resolve the same, it can lead to different concepts of the final product for both parties. This is a case of essential difficulty in the production of software


---

#### Accidental Difficulties

* According to Brooks, accidental difficulties are the ones that are related to the production of software and implementing the same in code. 
* This does not always mean the difficulties caused by accidents, but instead the ones where one solution leads to another problem.
* Brooks also argues that most of the improvements in software engineering target the accidental difficulties and they have been solved as much as they could have been.
* For example, one of the biggest steps in finishing a software is testing. One can create vast amounts of tests, covering all test cases, and yet, during production, one such case arrises which was never imagined to exist. This is an accidental difficulty because all of the test cases were not covered.


---

#### Four Essential Difficulties

1. Complexity
    * Complexity of a software is intrinsic to it. Brooks says that no two parts of a software are alike, which makes them complex. Also, software systems have a lot more states than a digital system which makes them a lot more complex due to the different relations between all the parts.
    * Even the scaling of software systems is non linear and, unlike hardware systems, is not merely duplication of parts.
    * One example would little to no communication between two parties regarding the software product, which leads to even more problems like bugs and security vulnerabilities.
2. Conformity
    * Often times, a software must conform to some specifications which may or may not be already existing. This leads to an inherent difficulty in software production knows as conformity.
    * Many times, an already existing software needs to adapt to the changes to its specification, and these arbitrary changes can never be predicted.
    * For example, a software product uses a thrid party library to do some of its functions and suddenly the 3rd part vendor decides to change the API of its library. This causes the conformity problem.
3. Changeability
    * Change is inherent in the nature of the software which needs to keep changing to keep pace with its different parts. 
    * Change could be forced due to conformity problem, or required to stay in production. More the people use the software, greater will be the pressure for change.
    * For example, a security bug has been discovered, which needs to be addressed and requires the software to be changed.
4. Invisibility
    * Brooks rightly says that software is invisible and its visualization in our 3D space is difficult.
    * Even if we try to create a diagram, often times these are too complex and a single diagram cannot help visualize the entire software which is made up of various different parts.
    * We could try to create UML's but these contain a lot of different shapes and becomes difficult to visualize for the non-developers.


---

#### Silver Bullet

* According to Brooks, a *silver bullet* is a single *godlike* technique that promises an order of magnitude improvement in software production.
* Brooks article on *No Silver Bullets* rightly states that there is no single technique to increase the productivity of software, but the same can be achieved by a combination of various tools that are specifically targeted at the various difficulties.
* Brooks presents a comparison to hardware entities and says that software is much different than hardware as it consists of various different entities with a lot more complex relationships between them.
* With these arguments Brooks believes that there is no silver bullet for software engineering.


---

#### Software Engineering

* Software engineering can be defined as a tehnique which applies a well defined approach towards the creation of reliable, cost-effective software systems.
* Software engineering is related to computer science but on a much wider level.
* Consider the relation between a chemist and a chemical engineer. The chemist might come up with an innovative idea and might also prove it, on a small scale, in his laboratory. Now comes the difficult job of a chemical engineer.
* He knows that the proposed idea works, since it has been proved with a small scale working model, but to use it on a much larger scale that is hundreds or thousands or magnitude larger than a laboratory is a very different task. This is where a chemical engineer needs to take into account a lot of other things like budget, demands and even feasibility on such a large scale.
* The same relation exists between computer science and software engineering where computer science represents the chemist and chemical engineer is represented by software engineering.
* Computer science can propose all sorts of different algorithms to reduce time complexity of various operations, but it is software engineering that decides the feasibility of the same by taking into account a lot of other relevant things like processor speed.


---

#### Software Engineering Concepts

1. Abstractions
    * Abstraction is the process of breaking down a problem into smaller parts and then working to solve those smaller parts, furhter breaking them down if necessary.
    * Everything in software engineering is solved either by creating own abstractions or by using abstractions created by others.
    * These smaller parts are then synthesized together to create a software product.
    * For example, the Bootstrap CSS Framwork provides complete abstractions for changing display sizes.
2. Conversations
    * Conversation is very important in software development.
    * Whether we are trying to understand the software comcept, or trying to know about the abstraction that someone else wrote, conversation is required in each one of them
3. Specification
    * Software engineers specify everything that the software product will have.
    * This includes all the requirements, code, test cases, deployment, maintenance and everything.
    * However, it is important to develop good specifications to produce a good software product.
4. Translation
    * There is translation everywhere in software engineering.
    * First the engineers translate the client's specification to their own, then the different abstractions are translated to their own needs, and finally the final product is translated to the one desired by the customer.
5. Iteration
	* Software engineering is an interative process, which relates to creating abstractions.
	* We keep working to the final product step by step, until the product matched our desired one.
	* If it doesn't, we iterate again, until we are done.


---

## Reference

* *No Silver Bullet: Essence and Accidents of Software Engineering*, Brooks