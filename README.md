# Migrant

A completely dabatase independent migration tool. Migrant gives you a
framework for using migrations in any context.

## Installation

```bash
npm install -g migrant
```

## Usage

Initialize migrant. This will create: `.migrantrc`, `config/migrant.js`,
`db/version.js` and `db/migrations/`.

```bash
migrant init
```

To create your first migration just run:

```bash
migrant create "first migration"
```
