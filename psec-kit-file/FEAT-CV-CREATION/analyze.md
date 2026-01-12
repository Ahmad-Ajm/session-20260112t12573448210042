# Analyze

## Problem Context
Users need a simple, guided way to create and maintain a CV without prior formatting or writing skills. The system must collect structured data and persist it securely.

## Assumptions
- Each user owns exactly one primary CV.
- CV data is stored in a relational database.
- Image upload is optional and limited to 2MB.

## Risks
- Incomplete data entry by users.
- Image upload security (file type validation).

## Dependencies
- User Authentication feature.
- Database storage layer.
