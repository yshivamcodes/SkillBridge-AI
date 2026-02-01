# SkillBridge-AI
AI-Powered Career & Skill Guidance Platform for First-Generation Learners

## Overview

SkillBridge AI is a Social Good–focused AI platform designed to help first-generation learners make informed career decisions.
It acts as a digital career mentor, providing personalized career recommendations, skill gap analysis, and step-by-step learning roadmaps using accessible, cloud-native AI.

The project is being built as part of the AWS AI for Bharat / 10,000 AIdeaS Hackathon, with a strong emphasis on responsible AI, scalability, and accessibility.

## Problem Statement

* First-generation learners from Tier-2 and Tier-3 regions often lack:

* Access to career mentors and counsellors

* Awareness of career paths and required skills

* Structured guidance to bridge education-to-employment gaps

* This results in career confusion, skill mismatch, and underemployment despite formal education.

## Solution

SkillBridge AI provides:

* AI-driven career recommendations based on user background and interests

* Skill gap analysis aligned with industry roles

* Personalized learning roadmaps using free, trusted resources

* Multilingual support to improve accessibility

* The platform is cloud-native, privacy-first, and designed for large-scale adoption.

## Target Users

* First-generation college students

* Rural and semi-urban youth

* Underserved learners seeking career clarity

## Core Features (MVP)

* Career recommendation engine

* Skill gap identification

* Personalized skill roadmap generation

* Curated free learning resources

* English + Hindi language support

* Mobile-first web experience

## Architecture & Design

The system follows a serverless, AWS-native architecture, using AI services for personalization and orchestration.

Key services include:

* Amazon SageMaker – ML-based career recommendation

* Amazon Bedrock – Natural language explanations and roadmap generation

* Amazon Bedrock AgentCore – Multi-step AI reasoning orchestration

* AWS Lambda & API Gateway – Backend logic and APIs

* DynamoDB & S3 – Data and content storage

* Amazon Translate – Multilingual support

## Detailed specifications and design decisions are available in:

requirements.md

design.md

## Responsible AI & Privacy

* No collection of sensitive personal data

* Explainable, non-deterministic recommendations

* Multiple career options provided (no single-path forcing)

* Bias-aware and inclusive design principles

## Project Status

✅ Idea & scope finalized

✅ Requirements and design artifacts created using Kiro Spec → Design flow

## MVP development in progress

This repository is currently used for hackathon submission and design documentation.
A production-grade implementation may be developed in a future phase.

## Hackathon Context

This project is submitted as part of:
AWS AI for Bharat / 10,000 AIdeaS Hackathon

Submission includes:

* requirements.md

* design.md

* Presentation deck (PDF)

* No GitHub deployment is required at this stage.

## Team

Team Name: SkillBridge AI
Team Lead: Shivam Yadav

## Future Scope

* Job market trend integration

* Mentor matching system

* WhatsApp / SMS-based guidance

* Government and academic institution partnerships
