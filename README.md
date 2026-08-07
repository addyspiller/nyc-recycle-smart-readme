# NYC Recycle Smart

A photo-based tool for getting an immediate, NYC-specific answer about how to dispose of an item.

## The problem

NYC recycling rules can be surprisingly difficult to apply in the moment.

Knowing that something is recyclable isn't always enough. The answer can depend on the material, type of packaging, and local disposal rules, which often means stopping to search through guidance just to figure out what to do with the item in your hand.

I wanted to test a simple product hypothesis:

**Could computer vision remove that lookup step entirely?**

## Product approach

I designed the interaction around reducing the decision to one action:

**Take a photo. Get a clear answer.**

That meant keeping the experience intentionally narrow:

- no browsing through recycling categories
- no lookup tables
- no need to identify the material yourself
- instructions specific to New York City rather than generic recycling guidance

The goal wasn't to build a comprehensive waste-management platform. It was to see whether one confusing moment could become significantly easier.

## What I built

A user can photograph an item such as a container, bottle, or piece of packaging and receive plain-language guidance about how to dispose of it under NYC rules.

I built the first version in four days as a rapid product experiment to test whether the interaction was useful and whether vision models were capable enough to support it.

## What I learned

The experiment showed that computer vision could make a rules-heavy civic process feel much more direct.

It also reinforced something I use in client work: when the uncertainty is about whether an interaction will actually solve the problem, a small working product can answer that faster than a detailed specification.

## Status

Prototype complete. The application isn't currently open to public traffic.

## Built with

JavaScript · Gemini Vision API · Netlify
