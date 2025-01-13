![N-gineer](assets/Ngineer%20-%20Green.png)

# N-gineers Start Here

Welcome to **N Lang**! This guide will help you get started writing and deploying your own Sub-dividable N-Lang Apps (**Snapps** for short). If you’re looking for deeper technical details, check out the official [N Lang Specification](https://github.com/squillo/n). We’re excited to see what you’ll build with native **cloud** and **agentic** software!

---

## FAQ & Quick Reference

- [What is N Lang?](#what-is-n-lang)
- [What is a Node Language?](#what-is-a-node-language)
- [What are Nodes?](#what-are-nodes)
- [What type of language is N?](#what-type-of-language-is-n)
- [What makes N unique?](#what-makes-n-unique)
- [Direct & Indirect Interpretation?](#direct--indirect-interpretation)
- [Why create a new language?](#why-create-a-new-language)
- [Is N Lang hard to learn?](#is-n-lang-hard-to-learn)
- [Why would I use N Lang?](#why-would-i-use-n-lang)
- [What would I use N Lang for?](#what-would-i-use-n-lang-for)
  - [Orchestration / Configuration Model](#orchestration--configuration-model)
  - [Operational Model](#operational-model)
  - [Information Model](#information-model)
- [What is an N-gineer?](#what-is-an-n-gineer)
- [What is an N Lang program?](#what-is-an-n-lang-program)
- [How do I learn to write a Snapp?](#how-do-i-learn-to-write-a-snapp)
- [Is N Lang extendable?](#is-n-lang-extendable)
- [Can I develop my own N Lang blocks?](#can-i-develop-my-own-n-lang-blocks)
- [How do I develop my Snapp?](#how-do-i-develop-my-snapp)
- [How do I interpret my parsed Snapp?](#how-do-i-interpret-my-parsed-snapp)
- [How do I deploy my Snapp as an application?](#how-do-i-deploy-my-snapp-as-an-application)
- [How do Snapps communicate?](#how-do-snapps-communicate)
- [How do I message my N Lang application?](#how-do-i-message-my-n-lang-application)
- [Where are Snapps stored?](#where-are-snapps-stored)
- [How is N Lang Licensed?](#how-is-n-lang-licensed)

---

## What is N Lang?

[N Lang](https://github.com/squillo/n) is a **“Node Language”** — a language for creating and programming distributed data on a **programmable graph** of nodes. It provides a framework for writing simple, *sub-dividable* programs (Snapps) that, when composed, build fast, reliable, and maintainable distributed software that securely scales.

### Some Key Highlights of N Lang

1. **ALWAYS Forward-Backward Compatible**  
   Data and shape changes are core features, not afterthoughts. You can evolve your data and programs without breaking older versions — crucial at massive scale.

2. **Programmable Graph of Nodes**  
   Data models imitate real life and programs are a graph of Nodes that you can split, merge, or recombine into different modules, libraries, or services.

3. **First-Class Data**  
   Data is king. Node state changes automatically trigger deterministic events, making it ideal for reactive and event-sourced apps.

4. **Built-In CEQRS**  
   Extends CQRS into state-of-the-art **CEQRS** — Commands, *Events* Queries — so your data is consistent, trackable, and verifiable across distributed nodes. [TODO, link]

5. **Distributed Runtime**  
   One ore more Nodes can run across machines or regions, unified by a persistent distributed ledger. Horizontal scaling and replication come standard. Easily set boundaries and endlessly vertically scale apps.

6. **Native & Foreign Function Interface**  
   Tap into Rust, C, Java, Python, JavaScript or other languages seamlessly. N Lang’s FFI lets you integrate and extend easily and ship VMs where your nodes live.

7. **Declarative & Typed**  
   Focus on *what* your data should do, not *how* to do it. Statically checked types reduce runtime errors, enhances testing, and keeps code reliable.

8. **Security & Reliability**  
   Built-in permissions, robust error handling, and event-based orchestration help you craft secure, fault-tolerant systems ready for production.

9. **Functional, Reactive, Pattern Matching**  
   N Lang is a functional language with reactive programming and pattern matching built-in. This makes it easy to write complex programs with simple, readable code.

---

## What is a Node Language?

A **Node Language** uses recursively linked “programmable nodes” within a semi-directed graph. In N Lang, each Node can represent anything from a simple scalar value to an entire database or even an entirely other N Lang program.

---

## What are Nodes?

**Nodes** are N Lang’s core data structures. They can be as simple as a single value or as complex as a nested hierarchy of data. Nodes become incredibly powerful when linked together in a graph, enabling distributed, reactive programming at scale.

---

## What type of language is N?

N Lang is a:

- Statically typed
- Declarative
- Functional
- Trait based
- Lazily initialized & evaluated distributed “tuple space” language

However, we prefer to call it a **Node Language**, keeping things simple. Simple is an N Lang theme.

---

## What makes N unique?

N Lang has a built-in **immutable ledger** that stores your Nodes, offering powerful event sourcing and versioning through a novel implementation of CQRS called CEQRS (pronounced "Sea crest"). 

N can notably always (de)serialize to and from JSON.

---

## Why Create a New Language?
The world has seen some pretty incredible languages over the years, but N Lang is here to solve a specific problem: **data-driven programming**.

When we started N Lang, we saw how Hyper-text transformed how people connected with each other. **N Lang** aims to transform how **data** connects both humans and AI. We've taken decades of human experience and modern development demands to devise a simple and intuitive syntax that enables distributed and event-driven patterns and makes them second nature.

We interviewed thousands of Engineers, Developers, Programmers, Designers, Architects, and even Business Owners to understand what they needed from software, and the result is a new language & system we could describe as "N Lang".

Modern teams need to move fast in a distributed world, but building secure and reliable systems at scale is REALLY hard. N Lang is here to make that easy.

From **CEQRS** (Command, Event, Query, Responsibility, Segregation) and **CRDTs** to **immutable ledgers** and **hot module swapping**, we believe these making these “hard problems” simple make N Lang a go-to choice for building **reliable**, **maintainable**, and **secure** systems at scale.

We also believe that Foreign functions should first class citizens. N Lang should be easy enough to be productive in a day, and still let you reach for the best tools for the job when you need them.

Just as HTML introduced a straightforward way to structure content, we wanted to create a common thread for some of computing's most difficult problems — one that any developer could pick up quickly. 

Finally, Under the hood, N Lang follows a robust **language → parser → interpreter → gateway** approach, time-tested by global adoption in other paradigms, but supercharged for today’s data-driven demands.


---

## Is N Lang hard to learn?

No. In fact, you likely already know more N Lang then you think. You should be able to pick it up in an afternoon, and spend years understanding and mastering its depths.

It's designed around the concept that small simple systems make complex systems work and ideal small systems are highly reusable. Which means you can learn it progressively. At scale, it does require a certain *mindset* around Nodes and ledgers.  

Also, N Lang's syntax is intentionally *human-readable* and somewhat familiar (technically a superset of JSON). You can scale your knowledge gradually, creating small blocks that compose into large systems.

---

## Why would I use N Lang?

Bluntly, there are things that only N Lang can do, but also N Lang speeds up development and reduces maintenance for distributed, event-driven, and data-centric applications. Even complex operations and data types like CRDT based conflict resolution are built-in. You’ll spend less time wiring and more time building real value. AND when there isn't something in N Lang's toolbox, you can simply extend the language with first class foreign functions from your favorite languages and applications.

Even if you are an absolute expert in distributed computing and large scale systems, it would take you months to write even a fraction of the code that N Lang can write securely in minutes. When we apply our collective knowledge to a common language, we can build systems that are more reliable, more maintainable, and more secure.

But it's more than just productivity and speed. N Lang enables you to create, connect, and recombine data in ways that can be shared globally across hundreds of different professions. It enables Software-as-a-Utility — for all.

---

## What would I use N Lang for?

N Lang is ideal for:

- **Cloud & Agentic Software**  
  Use N Lang to make the ultimate agentic software fast. Networked software is N Lang’s sweet spot.

- **Service Creation and Integration**  
  Make fast, maintainable APIs or connect existing services at scale.

- **Auditability**  
    Create systems that are auditable and verifiable at every step.

- **Orchestration / Configuration**  
  Similar to Infrastructure as Code, but extended into service creation, integration, or recombination.

- **Complex Operations**  
  Perfect for data pipelines, CQRS, or any environment where data modeling and reliable state transitions are paramount.

- **Information Modeling**  
  Replace or enhance a traditional CMS, unify shifting schemas, or structure data for content platforms, data warehouses, or operational stores.

- **Data Transformation**  
  Convert unstructured data into structured data, or manage schema evolutions and data transformations.


### Orchestration / Configuration Model
If you already use Infrastructure as Code, N Lang extends that mindset to services themselves—provision, connect, and recombine them with version-controlled declarations.

### Operational Model
In an Internal Development Platform or multi-service environment, N Lang orchestrates and unifies microservices, speeding up integration and reducing complexity.

### Information Model
For CMS or content-driven systems, N Lang shapes your data and automates how it evolves. It can also serve as a bridging layer between unstructured data and well-defined schemas.

---

## What is an N-gineer?

An **N-gineer** is someone who writes and maintains N Lang programs (Snapps). The name reflects the mix of disciplines involved in node-based, data-driven development.

---

## What is an N Lang program?

An **N Lang program**, also called a **Snapp**, is a *Sub-dividable, N-Lang, Application*, or chunk of logic, configuration, or data transformations expressed in N Lang syntax. Snapps can be composed into larger systems or split into smaller modules by grouping nodes and sub-dividing them.

---

## How do I learn to write a Snapp?

Check out the [N Lang Tutorial Series](https://github.com/squillo/n_tutorials) or the [N Lang Specification](https://github.com/squillo/n). Start small with a simple Snapp, then build up as you learn more advanced concepts.

---

## Is N Lang extendable?

Absolutely. N Lang supports **foreign functions** natively, letting you call into Rust, C, Java, Python, JavaScript or other languages for advanced features.  It's important to note, N Lang follows a "let it crash" philosophy, so if foreign functions fail, it won't stop the rest of the program from running.

---

## Can I develop my own N Lang blocks?

Yes. You can create new block types, parse, compile, and interpret them in the native syntax. This makes your Snapps more modular and reusable.

---

## How do I develop my Snapp?

1. **Install N Lang CLI** to manage, build, and run Snapps. [TODO, link]
2. **Use any UTF-8 editor or an IDE** with syntax highlighting.
3. **Write `.n` files** for your N documents. You can also parse `.n.md`, `.yaml`, or `.toml` into N.

---

## How do I interpret my parsed Snapp?

- Use the **N Lang CLI** [TODO, link] to start your N program.
- Or integrate it with a specialized interpreter.

---

## How do I deploy my Snapp as an application?

- **`nlang start`** deploys an N Lang app if you’re using its built-in ledger graph.
- Other interpreters exist for specialized use cases:
  - **Nimble**: Integrates with SvelteKit for web apps.
  - **Strataform**: Handles web infrastructure orchestration.
  - **Raconteur**: Builds scalable APIs, automations, and integrations.

---

## How do Snapps communicate?

Snapps can exchange messages through **N Lang Gateways** using the **N Lang Message Wire Protocol (MWP)**. They can also interoperate across different expression models. The [Kong Gateway plugin](https://github.com/squillo/rcp-gateway-kong) converts standard HTTP requests into the N Lang MWP, offering a bridge for external services.

---

## How do I message my N Lang application?

Depending on your chosen runtime/interpreter, you’ll typically send messages via an **N Gateway** or using the **MWP** directly. More gateway options will appear over time—watch the ecosystem grow!

---

## Where are Snapps stored?

Snapps can be published to a **Snapp registry** (upcoming feature). For now, you can store them in Git or any version control system and share them with your team or community.

---

## How is N Lang Licensed?

N Lang follows a “crawl, walk, run” philosophy. Currently:

- **Research License** (non-commercial use, free for annual revenue under \ $10,000)
- **Commercial License** (exclusively through Squillo for commercial use. Essentially, if you make money off the software, then part of it needs to go back to the community. Don't worry, the Snapp store will make this easy and help you too!)

As the project matures, the licensing model will evolve towards a more open model, so check back for updates.

---

*Happy N-gineering!* Feel free to contribute, ask questions, or share your Snapps. We’re excited to see how you’ll use N Lang to reshape data programming for the cloud and beyond.
