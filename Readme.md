# Domain Driven Design

## What is DDD (Domain Driven Design)?
DDD is a way of organize and structure a Software so that the classes, methods match with business domain.

## Software complexity
- Should be used in big and complex software
- Should be used in software with much departments and contexts differents
- The biggers complexities of software doesn't comes from tecnology, but of business domain rules
- People

## How DDD can help?
- Deep understanding the domain and subdomains
- Have a Universal Language (avoid Ubiquitous Language)
- Create design using Bounded Contexts

# Domain and Subdomains

## Domain (core domain)
- Main business acitivity, the heart of business
- Competitive differential

## Subdomains
- Support Subdomain
    - Support the core domain
    - Helps the core domain does your operations
- Generic Subdomain
    - Support the core domain too, but don't have competitive differential
 
# Problem vs Solution

## Problem
- Overview of domain and your complexities
- Separate the domain in subdomains

## Solution
- Analyze and to model the domain -> subdomain delimiteds

# Bounded Contexts
> Bounded Contexts is an explicit boundary within which a domain model exists. Inside the boundary all terms and phrases of the Ubiquitous Language have specific meaning, and the model reflects the Language with exactness.

## Transversal Elements
![](context.png "Context Example")

Above, the "Cliente" is a Transversal Element because he is associated with two context. However, he is deal with different things depending of context
