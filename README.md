![N-gineer](assets/Ngineer%20-%20Green.png)
# N-gineers Start Here
Getting up and running with N Lang.

Welcome! This is the place to get up and running with writing and deploying N Lang programs.

## FAQ & Quick Reference
- [What is N Lang?](#What%20is%20N%20Lang)
- [Why create a new language?](#Why%20create%20a%20new%20language)
- [Is N Lang hard to learn?](#Is%20N%20Lang%20hard%20to%20learn)
- [Why would I use N Lang?](#Why%20would%20I%20use%20N%20Lang)
- [What would I use N Lang for?](#What%20would%20I%20use%20N%20Lang%20for)
- [What is an N-gineer?](#What%20is%20an%20N-gineer)
- [What is an N Lang program?](#What%20is%20an%20N%20Lang%20program)
- [How do I learn to write an N Lang program?](#How%20do%20I%20learn%20to%20write%20an%20N%20Lang%20program)
- [Is N Lang extendable?](#Is%20N%20Lang%20extendable)
- [Can I develop my own N Lang blocks?](#Can%20I%20develop%20my%20own%20N%20Lang%20blocks)
- [How do I develop my N Lang program?](#How%20do%20I%20develop%20my%20N%20Lang%20program)
- [How do I parse N for an Interpreter?](#How%20do%20I%20parse%20N%20for%20an%20Interpreter)
- [How do I interpret my parsed N Lang program?](#How%20do%20I%20interpret%20my%20parsed%20N%20Lang%20program)
- [How do I deploy my N Lang program as an application?](#How%20do%20I%20deploy%20my%20N%20Lang%20program%20as%20an%20application)
- [How do I message my N Lang application?](#How%20do%20I%20message%20my%20N%20Lang%20application)
- [Can I write my own N Lang parser?](#Can%20I%20write%20my%20own%20N%20Lang%20parser)
- [Can I write my own N Lang interpreter?](#Can%20I%20write%20my%20own%20N%20Lang%20interpreter)
- [Can I write my own N Lang gateway?](#Can%20I%20write%20my%20own%20N%20Lang%20gateway)
- [Can I write my own N Lang blocks?](#Can%20I%20write%20my%20own%20N%20Lang%20blocks)


### What is N Lang?
[N Lang](https://github.com/squillo/n) is the world's first "Node Language" for structuring data — a blend of orchestration, configuration, and programming. N Lang provides a construct for writing simple sub-dividable programs that build complex programs that are highly distributable.

### Why create a new language?
Hyper-text transformed the way humans connect with each other. N Lang's goal is to transform the way systems connect. 

First, we wanted to maximize speed, reliability, and maintainability for networked data. Next, we needed to create a way to directly express the relationship between networked data and data producers & consumers and how we could program that directly through interface that was as easy learning something like HTML.

Finally, we needed a language -> parser -> interpreter -> gateway design pattern that has a proven track record of growth and adoption.

### Is N Lang hard to learn?
Subjectively no. It's a new mindset to learn, but it is specifically human-readable and is often familiar. It's designed around the concept that small simple systems make complex systems work. To do this, the language uses blocks and attributes to compose large systems from small systems.

### Why would I use N Lang?
There are several reasons to use N Lang, particularly any time you have structured data.
- If you are already using a process like Infrastructure as Code, then you already know the advantages of configuration & orchestration repeatability coupled with version control for infrastructure. N Lang is the missing utility that extends those capabilities into service creation, integration, and recombination. Additionally, it's HCL compatible, so you can use it just like you would Terraform. 
- If you have an Internal Development Platform, N Lang is a perfect way to integrate and unify millions of services.
- If you are using a Content Management System (CMS), then structuring your data using N Lang can create powerful CMS replacements.
- If you have several types of data or APIs that changes data shape frequently, then N Lang will be your new best friend.

### What would I use N Lang for?
N Lang is specifically designed for highly productive data-structuring, service creation, integration, and recombination that scales. It's specifically well suited to create, connect, and transform data while handling change and the faulty nature of networks.

### What is an N-gineer?
An N-gineer is someone that writes N Lang programs. We use a special name for them because N Lang programming is a combination of so many disciplines.  

### What is an N Lang program?
N Lang programs are interpreted programs written in N Lang that create, connect, and recombine services.

### How do I learn to write an N Lang program?
The best way to learn is by starting with the [N Lang Tutorial Series](https://github.com/squillo/n_tutorials). You could also learn all the ins and outs of N Lang by referring to the [N Lang Specification](https://github.com/squillo/n). 

### Is N Lang extendable? 
N Lang is also extendable, which means that certain N Lang parsers and interpreters may have pre-written N Lang blocks that add common functionality. For example, Squillo's [Raconteur](https://github.com/squillo/raconteur) is equipped with definitions for advanced Network Operations, CQRS, Cron Jobs, Event busing, Webhooks, and more.  

### Can I develop my own N Lang blocks?
Yes, since N Lang is a construct for sub-dividable programs, block definitions can be created and then supported by an N Lang interpreter.

### How do I develop my N Lang program?
The best way to develop an N Lang program is using the [Squillo NDE](https://github.com/squillo/squillo-nde) and then parse your program for an N Lang interpreter. Any UTF-8 encoding editor is suitable. We denote N documents with a `.n` file extension. You can even parse markdown documents into N.

### How do I parse N for an Interpreter?
Eventually, there will be several options for parsing N Lang programs. In the meantime, Squillo developed an open source parser and the [Raconteur Parser](https://github.com/squillo/raconteur) for N Lang programs. You can use the [Raconteur-cli](https://github.com/squillo/raconteur-cli) or Squillo NDE to parse your N Lang program for an N Lang interpreter.

### How do I interpret my parsed N Lang program?
There are several options to interpret parsed N Lang programs, including writing your own easily. For example, Squillo developed an open source network interpreter as well as the Raconteur Object Interpreters (ROIs) for the Raconteur N Lang parser for high-throughput network operations. Currently, there is the [ROI: Elixir](https://github.com/squillo/ex_raconteur_umbrella) written in Elixir. 

### How do I deploy my N Lang program as an application?
Once you've parsed your N Lang program and selected your interpreter. You can deploy your N Lang application. Your interpreter could be a web framework like Svelte or React, or even a Network interpreter typically using a Docker Image of your Interpreter with your program as a volume.

### How do Network N Lang applications communicate?
All Network N Lang applications use the N Lang Message Wire Protocol (MWP) to send and receive messages. Messages tell the Network N Lang application what part of a program to run and with what data. By default, a message request and response is a synchronous operation.

### How do I message my Network N Lang application?
Depending on your Network N Lang Interpreter, you can send messages over an N Gateway. Eventually, there will be several N Gateway options, in the meantime, Squillo developed a [Kong Gateway plugin](https://github.com/squillo/rcp-gateway-kong) that converts HTTP requests to and from the N Lang Message Wire Protocol. This N Gateway is designed to work as a standalone plugin with Kong but also works with the Raconteur Control Plane (RCP) "TODO LINK NEEDED" developed by Squillo.  

### Can I write my own N Lang parser?
Yes, as long as it follows the N Lang specification and is registered as an N Lang parser.
Check the [N Lang parser registry](https://github.com/squillo/n/blob/main/N%20Language%20Spec/N_LANGUAGE_PARSER_REGISTRY.md) to get started.

### Can I write my own N Lang interpreter?
Yes, as long as it follows the N Lang specification and is registered as an N Lang interpreter. Check the [N Lang interpreter registry](https://github.com/squillo/n/blob/main/N%20Language%20Spec/N_LANGUAGE_INTERPRETERS_REGISTRY.md) to get started.

### Can I write my own N Lang gateway
Yes, as long as it follows the N Lang specification and is registered as an N Lang gateway. Check the [N Lang gateway registry](https://github.com/squillo/n/blob/main/N%20Language%20Spec/N_LANGUAGE_GATEWAYS_REGISTRY.md) to get started.

### Can I write my own N Lang blocks?
Yes, however, the N Lang parser and interpreter you select will need to support your custom block type.
Check the [N Lang block specification]() to get started.