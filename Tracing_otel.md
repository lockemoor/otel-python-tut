
# Tracing and Opentelemetry basics



## Introduction

With increased complexity of architecture and with web development's (meaning agile's) fast paced development cycles, the need for proper observability has never been greater.
One such way is to track requests through your services using distributed tracing, and one of the more popular tools for that is opentelemetry, both of which we'll cover in this series of articles.
Disclaimer: Some of the concepts will be explained in a more generalized way and some will be for python specific enviroments.

## Distributed tracing

I believe that two of the most important concepts for understanding how distributed tracing works are context propagation and spans. If these two click properly understanding how everything else works is just a matter of going through the documentation.

### Context Propagation

