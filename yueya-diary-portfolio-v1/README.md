# 悦芽日记 (Yueya Diary)

A WeChat Mini Program designed for Chinese families to track daily childcare activities and improve communication between parents and hired childcare workers.

> The product itself is intentionally Chinese-only because it was designed specifically for users in the WeChat ecosystem and for a childcare scenario that is common in China.

[中文说明](README.zh-CN.md)

## Overview

Yueya Diary started from a real family problem.

When both parents need to work, it can be difficult to know what is happening with the baby throughout the day. At the same time, managing a hired childcare worker (育儿嫂) can feel awkward: parents want more visibility, but they do not want every interaction to become a direct check or confrontation.

In China, a “育儿嫂” is a professional childcare worker hired by families to assist with infant care.

The idea behind Yueya Diary is simple:

- make daily childcare activity visible;
- reduce the anxiety caused by not being physically present;
- create a consistent record of the baby’s routine;
- make handover easier when childcare workers change;
- build a long-term childcare data history for the family.

## The Problem

Traditional childcare communication often depends on fragmented messages, verbal updates, handwritten notes, or memory.

This creates several problems:

- Parents cannot easily review the whole day at a glance.
- Important details can be forgotten or recorded inconsistently.
- It is difficult to compare routines across different days or caregivers.
- Parents may feel anxious because they do not know what is happening while they are at work.
- When a childcare worker changes, there is often no structured historical record.

## Product Concept

Yueya Diary turns daily childcare into a lightweight, structured check-in workflow inside WeChat.

The caregiver records activities during the day, and parents can review them later in one place.

The product is designed to feel like a practical family tool rather than an employee monitoring system.

## Core Features

The first version includes structured tracking for:

- milk feeding time and volume;
- solid food type and allergy confirmation;
- sleep time;
- soothing / sleep methods;
- gross motor activity;
- bathing;
- music / listening activities;
- reading time, book title and pages;
- mood;
- body temperature;
- bowel movement colour and form;
- outdoor walks;
- notes;
- date-based history review;
- support for one or more childcare workers;
- data export.

## Product Philosophy

The key product insight is that this is not only a data-recording tool.

It is also an emotional product.

For working parents, especially mothers returning to work after parental leave, the problem is often not simply “I need more data.” The deeper problem is:

> “I cannot be there, so I do not know what is happening.”

Yueya Diary tries to reduce that uncertainty without creating constant interruptions between parents and caregivers.

## Why WeChat Mini Program

The target users are Chinese families, so the WeChat Mini Program ecosystem is the most natural distribution channel.

Advantages include:

- no separate app installation;
- familiar interaction model;
- easy access through WeChat;
- low friction for family members and caregivers;
- suitable for private beta testing through experience users.

## Current Status

The project has reached a working prototype / internal testing stage.

Completed milestones include:

- initial product requirements;
- WeChat Mini Program development environment setup;
- cloud environment configuration;
- working preview in WeChat Developer Tools;
- product rename from “小芽日记” to “悦芽日记”;
- early external interest from a potential test user.

## Screenshots

Real product screenshots will be added here.

Suggested screenshots:

1. Home / daily record page
2. Feeding and sleep tracking
3. Daily history / review
4. Data export or summary
5. WeChat Mini Program preview

## Product Flow

```mermaid
flowchart LR
    A[Caregiver records daily activity] --> B[Structured childcare data]
    B --> C[Parent reviews the day]
    C --> D[Lower uncertainty]
    D --> E[Long-term childcare history]
```

## What This Project Demonstrates

This project is a product case study as much as a software project.

It demonstrates:

- identifying a real user problem;
- converting an emotional pain point into a product requirement;
- feature prioritisation;
- product workflow design;
- WeChat Mini Program development;
- cloud setup and testing;
- bilingual product communication;
- iteration based on real-world feedback.

## Language Strategy

The application interface is intentionally Chinese-only.

This repository uses English as the default documentation language so that international recruiters and collaborators can understand the product, while the actual interface remains in Chinese because that is the correct design choice for the target market.

A full Chinese project description is also available in [README.zh-CN.md](README.zh-CN.md).

## Next Steps

Planned improvements include:

- improve the daily recording experience;
- refine historical data review;
- test with additional families;
- collect caregiver and parent feedback;
- improve export and comparison features;
- explore simple trend summaries for sleep, feeding and mood;
- improve onboarding for new caregivers.

## Repository Structure

```text
yueya-diary/
├── README.md
├── README.zh-CN.md
├── docs/
│   └── product-design.md
├── assets/
│   └── README.md
└── .gitignore
```

## Note on Source Code

This repository is currently used as a product portfolio / case study. The full production Mini Program source code is not published here at this stage.

---

Built as a practical product experiment around childcare visibility, family communication and lightweight digital record keeping.
