# Celestial Bodies Database

## Project Overview

A relational database developed as part of the Relational Database Certification from freeCodeCamp.

The project consists of designing and implementing a database representing a fictional universe, connecting galaxies, stars, planets, planet types and moons through relational structures.

## Technologies

- PostgreSQL
- SQL
- Git
- GitHub

## Database Structure

The database contains five main tables:

| Table | Description |
|---|---|
| `galaxy` | Stores information about galaxies. |
| `star` | Stores stars belonging to galaxies. |
| `planet` | Stores planets orbiting stars. |
| `planet_type` | Defines the different types of planets. |
| `moon` | Stores moons associated with planets. |

## Database Relationships

- Each galaxy can contain multiple stars.
- Each star belongs to a galaxy.
- Each star can have multiple planets.
- Each planet has a defined planet type.
- Each planet can have multiple moons.

## Concepts Applied

- Relational database modeling
- Primary keys and foreign keys
- SQL data definition and manipulation
- One-to-many relationships
- Data types and constraints
- Referential integrity

## Project Files

| File | Description |
|---|---|
| `universe.sql` | Complete PostgreSQL database dump. |

## Execution

To restore the database using PostgreSQL:

```bash
psql -U postgres -f universe.sql
```

Make sure PostgreSQL is installed and running before executing the command.

## Certification

**Platform:** freeCodeCamp  
**Certification:** Relational Database  
**Project:** Celestial Bodies Database  
**Status:** Completed

---

<div align="center">

**Part of my freeCodeCamp learning journey.**

</div>
