# Kelvis Guerrero

Software developer in Santo Domingo, Dominican Republic. I'm studying Software Development at ITLA and taking the Full-Stack + AI program at Alterna Academy. I did a backend internship writing REST APIs and Worker Services in C#/.NET, and the rest of what's here I built on my own.

I'm looking for a full-time developer role, on-site in Santo Domingo or remote. You can reach me at kelvisguerrero03@gmail.com.

## Where to start

The [portfolio](https://kelvis-guerrero.vercel.app) has a case study per project, with the tradeoffs I made and what is still missing. These three are the ones I'd look at first:

- [AgendaBot](https://github.com/Kelvis123456/agendabot) is a .NET backend where an AI agent books barbershop appointments over WhatsApp. The test that matters fires 8 identical bookings at a real SQL Server and checks that exactly one wins.
- [ReservaYa](https://github.com/Kelvis123456/reservaya) is a sports court booking platform with PostgreSQL for bookings and MongoDB for the flexible data. It has 76 backend tests, most of them on the failure paths.
- **RentEdge** is a pricing SaaS for rent-a-car companies (NestJS, Next.js, TimescaleDB, two Python services). The repo is private. The portfolio has the architecture diagram and a 50-second walkthrough, and I'm happy to go through the code on a call.

## Libraries and tools

Small projects where I tried to back each claim in the README with a test, then had each one audited by a separate AI reviewer. The audits found real bugs in the first three, and the fixes are in each repo's decisions log.

- [outbox-kit](https://github.com/Kelvis123456/outbox-kit) ([site](https://kelvis-outbox-kit.vercel.app)) is a .NET library for the transactional outbox on EF Core and PostgreSQL. The test that matters kills a real process between publishing and committing, then checks that no message is lost and every effect is applied once.
- [mcp-probe](https://github.com/Kelvis123456/mcp-probe) ([site](https://kelvis-mcp-probe.vercel.app)) runs scripted checks against an MCP server from a YAML file and fails the CI job when something breaks.
- [evalgate](https://github.com/Kelvis123456/evalgate) ([docs](https://kelvis-evalgate.vercel.app)) is a CI gate for RAG and LLM apps: a versioned eval set, a committed baseline, and a non-zero exit when quality drops.
- [Hornilla](https://github.com/Kelvis123456/cafe-concept) ([site](https://kelvis-hornilla.vercel.app)) is a concept website, in Spanish, for a fictional coffee roaster. No photos: everything is drawn in SVG.

## Built around Dominican rules and data

[dgii-helper](https://github.com/Kelvis123456/dgii-helper) issues invoice numbers (NCF) without duplicates, [codigo-trabajo-rag](https://github.com/Kelvis123456/codigo-trabajo-rag) answers questions about the Labor Code and cites its articles, [dop-usd-backtest](https://github.com/Kelvis123456/dop-usd-backtest) tests exchange-rate forecasts against repeating the last value, and [dominican-tools-mcp](https://github.com/Kelvis123456/dominican-tools-mcp) exposes the tax and labor tools through MCP.

## Other work

- [automatizaciones](https://github.com/Kelvis123456/automatizaciones): n8n workflows, one that stores a daily USD to DOP rate in Postgres and one that classifies messages with Gemini.
- [Connect5](https://github.com/Kelvis123456/connect5): a board game in Unity with a local AI and online multiplayer.
- [Detective Game](https://github.com/Kelvis123456/detective-game): a narrative detective game with a case, evidence and interrogation engine, in React.
- WillForge: a fitness app with an RPG progression system, in Flutter and Supabase. Private.
- [PHASE](https://github.com/Kelvis123456/phase-game-design) and [SKIM](https://github.com/Kelvis123456/skim-game-design): design work for two original mobile games.

## Stack

TypeScript, C#/.NET, Python, NestJS, Next.js, React, Flutter, PostgreSQL, SQL Server, Docker, n8n, Unity.
