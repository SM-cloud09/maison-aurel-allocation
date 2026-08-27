# Maison Aurel — Allocation Intelligence

An interactive supply allocation decision-support prototype designed to make scarce-product allocation more transparent, consistent, and explainable.

## Business Problem

Limited product releases can create more customer demand than available supply. Allocation decisions made through manual judgment or first-come, first-served approaches may overlook customer value, loyalty, and regional demand.

Maison Aurel explores a structured approach to this problem using weighted scoring and explainable decision logic.

## Scenario

The prototype models a limited-edition release with:

- 12 units available
- 40 verified client requests
- 10 units allocated through the primary weighted ranking
- 2 units reserved for promising new clients through a Rising Reserve mechanism

All client information in the prototype is sample data.

## Decision Factors

Each request is evaluated using adjustable weights for:

- Lifetime Spend
- Loyalty Tier
- Purchase Frequency
- Return History
- Regional Demand

Users can change these weights and recalculate the ranking to explore how different business priorities affect allocation decisions.

## Key Features

- Weighted multi-factor scoring model
- Dynamic ranking of 40 client requests
- Adjustable allocation priorities
- Automatic allocation and waitlist classification
- Rising Reserve mechanism for promising new clients
- Client-level score breakdown
- Human-readable explanation for each recommendation
- Automatically generated executive allocation summary
- Interactive KPI view

## Technologies

- HTML
- CSS
- JavaScript
- Explainable AI (XAI) design principles
- Prompt engineering and AI-assisted solution development

## How It Works

The application normalizes customer attributes, applies user-adjustable weights, calculates a composite score, and ranks requests from highest to lowest.

The primary allocation assigns 10 units to the highest-ranked customers. Two additional units are reserved for selected new customers who lack extensive purchase history but demonstrate early engagement potential.

The interface also generates plain-language explanations describing the factors behind each recommendation.

## Purpose

The prototype demonstrates how a subjective scarcity decision can be transformed into a more structured, transparent, and auditable decision-support process.

It is intended as a demonstration of supply chain allocation, analytics, and explainable decision design rather than a production allocation system.

## Project Context

Individual final project developed for TOM 6500 — AI Studio & Business Implementations during the MS in Digital Supply Chain Management program at Cal Poly Pomona.

## Disclaimer

Maison Aurel is a fictional brand created for this academic prototype. All customer names and data used in the application are synthetic/sample data.
