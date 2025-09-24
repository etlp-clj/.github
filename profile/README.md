## ETLP - Efficient Data Processing in Clojure

ETLP is a powerful Clojure library that simplifies the implementation of parallel concurrency and provides an efficient way to build data connectors. It leverages the concept of transducers and is based on the CSP (Communicating Sequential Processes) pattern. ETLP allows developers to easily incorporate best practices when working with data streams, positioning it as a go-to library for complex data processing in Clojure.

## Features
- Built on the concept of transducers and CSP pattern.
- Simplifies the implementation of parallel concurrency.
- Allows decoupling data mapping logic (business logic) from code using etlp-mapper.
- Supports the ability to develop a wide range of source and destination processors.


## Quick Start
Check out the following guide to get an overview of developing a connector [with etlp](https://github.com/etlp-clj/etlp-base/blob/main/README.md)

## Performance Benchmark 
High throughput ETL with very low footprint, achieved using transducers + core.async concurrency rather than thread-heavy models.

![alt ETLP Benchmark](https://github.com/etlp-clj/.github/blob/main/profile/etlp_performance_infographic.png)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
