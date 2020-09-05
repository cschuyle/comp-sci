# Stuff all Comp Sci majors should be able to talk intelligently about

## Programming Paradigms and Typologies

OOP
- Class
- Object / Instance
- Encapsulation, Abstraction, Inheritance, Polymorphism

_advanced_ Functional Programming
- Immutability
- No Shared State
- No Side Effects (what is a side effect?)
- Functions as a first class citizen
    - Lambdas
- Closures, Lambdas, variable scoping, Co-routines
- _advanced_ Composition of pure functions
    - Monads
    - Currying

_advanced_ Expert Systems and forward/backward chaining

Terminology
- Reify - what does it mean?

Scripting
- What's a scripting language versus other languages?
- What is scripting used for

Patterns
- GOF (Gang of Four) book.
    - https://en.wikipedia.org/wiki/Design_Patterns
    - It's unfortunate the D is right next to F on the standard keyboard.
- Learn all of them. Memorize interesting, nontrivial examples of juicy ones.

Dynamically vs Statically typed languages

Weakly vs Strongly typed languages

Make a matrix of the above with your favorite languages. For example:

| Facet                    | Java                        | Perl                       | Elm                  | Ambrosia |
| ---                      | ----                        | ---                        | ---                  | --- |
| Compiled / Interpreted   | Compiled                    | Interpreted                | Compile to JS        | Both (compiled for production use) |
| Dynamic / Static         | Static to the point of ruin | Dynamic                    | Static, oh so static | Static |
| Weak / Strong typing     | Strong but droopy           | Flexible                   | Strong, oh so strong | Strong |
| Power of typing systems  | Shit                        | worse than Shit but clever | Pretty OK            | The Best |

Procedural vs Declarative programming
- Is C++ Procedural?
- Is SQL Declarative?
- How about JSON

## Data storage

### File Systems
- Linux, MacOS, Windows filesystems
- NFS
- SMB
- FTP

### RDBMS

Learn one, maybe MySQL (MariaDB), PostgreSQL, Amazon RDS

### NoSQL

Learn a couple from a couple families:

- Key-value stores: Redis, Cassandra, AWS DynamoDB
- Document Stores: MongoDB
- Graph databases: Neo4j

### Information retrieval
- TF/IDF, word vector space 
- Lucene, Elasticsearch

### Chaff
- _advanced_ Know what LDAP is and be able to describe it
- _advanced_ File structures (data structures on disk)
- _advanced_ RDF, Semantic Web

## Development Methodologies

Waterfall

Agile

Scrum

Kanban

XP

Lean

## Development practices

Pair Programming

Test Driven Development

Continuous Integration

Fast Iterative Development

Git Flow and code reviews

Trunk-based development, branching

## Tools

Scripting
- basic Linux commands

IDEs
- Keyboard shortcuts. Be able to rattle off at least 20 that are indispensable.

Dependency management
- Talk about the tool for your favorite language, i.e. leiningen for Clojure

Version management
- Talk about the tool for your favorite language, i.e. rvm for Ruby

Source code management
- old stuff: SVN
- new stuff: Git, Mercurial

IntelliJ
- Explain why it's the best thing in the universe and why Eclipse sucks compared to it and why the military should suck it up and use it in spite of it having been developed in Russia

Markup/data representation languages
- YAML
- XML
- Markdown
- CSS
- HTML
- _advanced_ edn

Protocol buffers (Google loves these)

Monitoring
- Logs
- Metrics
- Dashboards


## Programs

Browsers

Mobile Apps

Servers

Distributed Systems
- How are Microservices different than a Distributed System?

Security
- What's a secret? A Vault?

Networking

REST APIs

MVC, MVVC, layered, hexagonal, DDD, ERDs, UML

Testing
- Testing Pyramid
- "*-Test": where * is: Unit, Integration, Functional, Smoke, end-to-end, Load, Performance, Contract, ....
- Mocks, Stubs, Fakes ....

Map-Reduce

Dependency Injection, IOC
- Spring
- Guice (Google loves this)

## Cloud

IaaS

PaaS

Docker

Networking: load balancers, firewalls, DMZ, proxies, reverse proxies, DNS, certificates

Kubernetes

Serverless


## Computers

Bits & Bytes, other encoding things
- What does cryptographic vs non-cryptographic mean?
- base64
- sha, sha256 ........ ?
- what's a cryptographic vs non-cryptographic hash?
- What power of 2 is about a million?
- What does `chmod 0755 whatever.txt` actually mean?
- What is the maximum value of a byte ?
- What is 2^{1..8}, 2^16 ?
- What is MAXINT or MAXLONG in Java or C++ or whatever other language and why do I care?
- What's a UUID?
- Why should you not compare floating point values exactly in tests? What alternatives are there to floating point types?
- _advanced_ Why is the number of buckets in a well-implemented hash table usually a (Mersenne ?) prime ?
- What's the difference between 32-bit and 64-bit processors?
- How many characters are in the ASCII character set? What does ASCII stand for? What's EBCDIC?
- What's Unicode and how is it different than UTF-8?

RISC & CISC

Processors, Registers, Cache, RAM, persistent storage, networks

Kernel, User Space, Devices, Sockets, TCP/IP, Ports, Pipes, Threads, Fibers, Processes 

Shells, Environment Variables, Permissions, command line tools, background and foreground, signals, TTY

file and device I/O: blocking, non-blocking
- <https://www.youtube.com/watch?v=bzkRVzciAZg>

## Advanced Topics

Big Data

Machine Learning

Deep Learning

Quantum Computing

"Esoteric" programming languages
- LISP
- Haskell
- Prolog
- APL
- ML, OCaml
