# Architecture Diagram

## Overview

This diagram shows the high-level architecture of the system.

## Mermaid Diagram

```mermaid
flowchart LR

User[User Browser]

Web[Web Application]

API[Backend API]

DB[(Database)]

Auth[Authentication Service]

User --> Web

Web --> API

API --> DB

API --> Auth
```
