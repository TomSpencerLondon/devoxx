# Devoxx Speaker Profile and Starter For Submissions

### Bio
"Passionate Java developer and consultant with over six years of experience in designing scalable and robust applications. Enthusiast for modern software engineering practices, including event-driven systems, concurrency, and microservices. Avid learner and educator, combining a background in Classics with expertise in software development to deliver engaging and insightful talks. Regular contributor to community meetups and workshops on Java and system design."

---

### Speaking Credentials
"I have delivered talks on concurrency, event-driven systems, and microservices at various technical meetups and internal company sessions. My experience includes preparing and presenting training material for developers and engaging audiences on complex topics like distributed systems and scaling microservices."

---

### Country
United Kingdom


## Proposal Ideas
As a mid-level Java developer, these are some topics I might choose that could reflect current trends and advancements in the Java ecosystem:

1. **Adopting Java 21: New Features and Enhancements**
   - Explore the latest features introduced in Java 21, such as pattern matching for switch statements and record patterns, and discuss how they can be leveraged to write more concise and readable code.

2. **Integrating AI and Machine Learning in Java Applications**
   - Demonstrate how to incorporate AI and machine learning capabilities into Java applications using popular libraries and frameworks, enabling intelligent features and data-driven decision-making.

3. **Building Cloud-Native Java Applications**
   - Guide the audience through developing cloud-native applications with Java, focusing on microservices architecture, containerization, and deployment strategies to cloud platforms.

4. **Exploring Project Loom: Lightweight Concurrency in Java**
   - Introduce Project Loom and its approach to lightweight concurrency with virtual threads, and discuss how it simplifies writing scalable concurrent applications in Java.

5. **Enhancing Java Applications with GraalVM**
   - Present the benefits of using GraalVM for Java applications, including improved performance, polyglot capabilities, and native image generation for faster startup times.

6. **Implementing Reactive Programming with Spring WebFlux**
   - Provide an overview of reactive programming principles and demonstrate how to build responsive and resilient applications using Spring WebFlux.

7. **Securing Java Applications: Best Practices and Tools**
   - Discuss common security vulnerabilities in Java applications and share best practices and tools for securing code, managing dependencies, and protecting sensitive data.

8. **Leveraging the Foreign Function & Memory API in Java**
   - Explore the Foreign Function & Memory API introduced in recent Java versions, which facilitates interaction with native code and memory, enhancing performance and interoperability.

9. **Migrating Legacy Java Applications to Modern Frameworks**
   - Share strategies and considerations for migrating legacy Java applications to modern frameworks like Spring Boot or Quarkus, improving maintainability and performance.

10. **Understanding the Java Module System (Project Jigsaw)**
    - Explain the Java Module System introduced in Java 9, its benefits for large applications, and how to create and manage modules effectively.

If I was to create a proposal I would need to write a clear abstract outlining the talk's objectives, the target audience, and key takeaways. 
I would need to tailor my topic to reflect current trends and technologies to enhance its relevance and appeal to conference attendees.

### Useful blog for proposal examples
https://thoughtbot.com/blog

## Preliminary Thoughts
1. Project Loom could be an interesting topic
2. Integrating AI and machine learning might be interesting

### Unique Perspective?
1. Integrating my background in Classics with modern concurrency concepts like Project Loom and Virtual Threads
2. Lessons from Ancient Rome for modern web development. Could explore how ancient Roman engineering principles inform modern web development and concurrency
3. Ancient thinkers like Zeno of Elea and Euclid and their relevance to concepts like concurrency, processes and problem solving in modern computing

#### Further exploration
- Zeno's paradoxes could illustrate infinite processes and convergence which could be related to concurrency challenges
- Modular Design, Robust Architecture and Systematic Planning could illustrate the importance of structured approaches and scalability in software development
- Ancient communication such as Roman roads could inform our understanding of modern data flow and network architecture
- Progression from mechanical computation to modern parallelism showcases how foundational ideas in structured problem solving and resource management evolved into todays concurrency paradigms


### Further Reading
- Douglas Hoefstadter, Godel, Escher, Bach
    - recursion
    - self reference
    - interplay of simple rules creating complex systems which can be linked to concurrency patterns in web development
- Brian Goetz, Concurrency In Practice
- Robert Martin, Clean Code
- Donald Knuth, Art of Computer Programming
- Andrew Hunt, David Thomas, Pragmatic Programmer
- Walter Isaacson, The Innovators
- Charles Petsold, Annotated Turing
- Aristotle, Organon
- Maria-Rosa Antognazza, Liebniz An Intellectual Biography
- Krzysztof R. Apt, Hoare Tony, Edsger Wybe Dijkstra, His Life, Work and Legacy

### A Brief history of Concurrency in Computing
Concurrency in computing, the simultaneous execution of multiple sequences of operations, has its roots in early computing and mathematical principles. The evolution of concurrency concepts has been significantly influenced by classical problem-solving principles and the contributions of pioneers like Edsger W. Dijkstra.

**Early Foundations in Mathematics and Computing**

The need for concurrent operations emerged with the advent of multiprogramming in the 1960s, where multiple programs were executed on a single processor to improve resource utilization. This development required mathematical models to manage and synchronize concurrent processes effectively. Early theoretical work, such as Petri nets introduced by Carl Adam Petri in 1962, provided a framework for modeling concurrent systems and analyzing their behavior. 

**Classical Problem-Solving Principles**

Classical problems in concurrency, often used to illustrate synchronization issues and techniques for resolving them, include:

- **Producer-Consumer Problem**: Introduced by Dijkstra in 1965, this problem involves coordinating a producer generating data and a consumer processing it, ensuring they operate smoothly without conflicts. 

- **Dining Philosophers Problem**: Formulated by Dijkstra as a student exam exercise in 1965, this problem illustrates the challenges of allocating shared resources among multiple processes without causing deadlock. 

- **Sleeping Barber Problem**: Also introduced by Dijkstra in 1965, this problem is a classic inter-process communication and synchronization problem between multiple operating system processes. 

**Contributions of Edsger W. Dijkstra**

Edsger W. Dijkstra made foundational contributions to concurrency, including:

- **Mutual Exclusion and Semaphores**: In his 1965 paper, "Solution of a Problem in Concurrent Programming Control," Dijkstra introduced the concept of mutual exclusion and proposed semaphores as a mechanism to control access to shared resources, preventing race conditions. 

- **Cooperating Sequential Processes**: Dijkstra's 1965 manuscript, later published in 1968, laid the groundwork for concurrent programming by formalizing the interaction between processes and introducing synchronization mechanisms. 

- **Banker's Algorithm**: Dijkstra developed this deadlock avoidance algorithm to ensure safe resource allocation in concurrent systems, preventing system-wide deadlocks. 

**Evolution of Concurrency Concepts**

Over time, concurrency concepts have evolved to address the increasing complexity of computing systems:

- **Monitors**: In the early 1970s, C.A.R. Hoare and Per Brinch Hansen developed monitors as high-level synchronization constructs that encapsulate shared resources and the procedures that operate on them, simplifying concurrent programming. 

- **Actor Model**: Introduced in the 1970s, the Actor Model conceptualizes concurrent computation through independent actors that communicate via message passing, eliminating the need for shared state and reducing synchronization issues. 

- **Transactional Memory**: Emerging in the 1990s, transactional memory applies concepts from database transactions to memory operations, allowing concurrent processes to execute in isolation and commit changes atomically, thereby simplifying synchronization.

- **Formal Verification Methods**: Techniques such as model checking and theorem proving have been developed to ensure the correctness of concurrent systems, allowing for the detection of potential issues like deadlocks and race conditions during the design phase.

The progression of concurrency in computing reflects a continuous effort to manage the complexities of simultaneous operations, drawing from mathematical principles and the pioneering work of computer scientists like Dijkstra. This evolution has led to more robust, efficient, and reliable computing systems capable of handling the demands of modern applications. 