# Qobdisha AI Specification

## Overview
Qobdisha AI is a digital memory and gifting platform built with Java 17 and Spring Boot. It allows users to store, retrieve, search, and manage personalized digital capsule entries (memories, cards, and video greetings).

## Core Features
1. **Status Check**: Endpoint `/api/qobdisha/status` returns backend health status.
2. **List Entries**: Endpoint `/api/qobdisha/items` returns all saved capsule entries.
3. **Add Entry**: Endpoint `/api/qobdisha/add` accepts JSON to save memories, cards, and video links.
4. **Search Entries**: Filter entries by title or content keywords.
5. **Delete Entry**: Remove an entry by its unique ID.
