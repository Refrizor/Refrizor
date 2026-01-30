* 🛠 Full-Stack Developer | Predominantly Java → Now I'm into JS/TypeScript, and Python for data science
  * I love backend development and data modeling!
* Building with Express and RESTful APIs, React, and Next.js
* Currently enrolled in an IBM program to obtain a professional full-stack software developer certificate
* Working on Inferris (one of my largest projects yet!)
* Advocate for [AFSP](https://afsp.org) <sub><a href="https://afsp.org"><img src="https://www.datocms-assets.com/12810/1587726862-afsplifesaverblue.png?ar64=MTox&crop=faces&fit=crop&fm=webp&w=200" alt="AFSP" width="25" height="25"></a></sub>

![Stats](https://github-readme-stats.vercel.app/api?username=Refrizor&show_icons=true&theme=transparent&hide_border=true)

## Projects
* [Server Tracker](https://github.com/Refrizor/server-tracker_v1) (v1) is a registry tracker for server instance uptime tracking and transient player-session tracking. Contains a TypeScript REST API and a Spigot plugin for Mojang server instances.
* [Inferris Rewrite v2](https://github.com/Refrizor/inferris-rewrite-v2) is a Java plugin that consumes a REST API using Retrofit, Jackson, Guice (DI), and Caffeine (TTL caching).
* [timetools-gui](https://github.com/Refrizor/timetools-gui) is a lightweight Java Swing GUI for generating and parsing Unix epoch timestamps for sysadmin workflows.
* [oaqjp-final-project-emb-ai](https://github.com/Refrizor/oaqjp-final-project-emb-ai) is a course capstone that parses ML model API responses to classify emotion predictions and confidence scores.

## Goals (2026)

* Continue leveling up in modern JS/TS and React-based app development
  * Strengthen Redux implementations
* Finish & open-source the network monitoring repository catering to the Minecraft server admin/dev and networking ecosystem (in progress)
* Continue advances in Python with a focus on data science, automation, AI, and beyond
* Keep pushing creative boundaries in programming, psychology, writing, and photography

<!--
## Inferris
Inferris is a large technical and communal project of an upcoming mature, age-gated (17+) community built on conversation with substance, connection, and shared experiences with a social and gaming ecosystem and a culture that rewards itself for preserving its own guardrails.

The social community will be hosted on Discord along with some of the activities, while one of the major gaming extensions lie the upcoming Minecraft network with custom software.

The values and undertones I wish to promote are discussions with substance—including mature and serious conversations—good vibes, toxicity as a rarity, inclusive energy, and stewards that *help*—not present fear or grandiosity; stewards that protect and preserve the culture, core values, and therein its integrity with Trust & Safety/Moderation mentorship training, retailiation protections, and other guardrails for a long-term, substainable presence that fosters safety, compassion, and a fun darn time.

The actual software project ranges from TypeScript and Express RESTful API development, Java and Java-based API consumers, to databases like PostgreSQL and Redis. **Learn more below!**

<details>
  <summary>Click to expand (technicals)</summary>
  
  ### REST API
  The main platform project encompasses a TypeScript Express RESTful API which intersects with the Minecraft/Discord project and uses PostgreSQL and Redis.

  Before the rewrite, the API included:
  * **Authentication** (Argus) and **authorization**, **RBAC** (Argus), **API keys** and **permission scopes**
  * **Minecraft player representations** and their retrospective core data, ranks, profile, profile badges, featured badge, social links, and its logic
    * Basic implementation of nicknaming as a 'facade player' (identity facades) and a nickname -> real name resolver
    * Vanishing allowed staff to disappear from the network entirely and be reducted from player counts.
    * The `/msg` system used the player resolver and respected vanish/nick privacy—blocking messages to vanished players and to nicked players’ real names unless the sender had the bypass permission.
  * * **Server network monitoring** allowed servers to constantly update the API on its uptime and current status and states with proper downtime checking
    * In addition, it tracked current **player lists** and **global player counts** with "visible" vs "actual" counts which were propogated to lobby server Scoreboard sidebars depending on player rank
  * **Chat messaging via various permission-gated channels**, like global, staff, and testing channels (Redis Pub/Sub)
  * **Chat moderation and safety pipeline**
    * Stage A ("local rules") of the pipeline handled the local chat rules. Is it content giberrish? Too many messages per allowed window? Self-promotion/advertisement (outside the whitelisted domains)? Flagged or hard-blacklisted words? Allow or deny the message.
    * Stage B ("Analysis") of the pipeline was a handoff: it handed the message to the REST API which then used Google Perspective for moderation analysis and cross-referenced the response's categories' values against pre-defined category thresholds, and returned an action response type: allow, allow but inform of potential misuse/abuse, or block. (Of note, messages on Perspective's end were never saved or used for training to abide by privacy policies.)
  * **Chat log storage and filtering endpoint**
    * Minecraft chat messages were sent to the API and immediately entered two keys: a global scope key, and a server-specific scope key, along with a sorted set for efficient reverse-lookup
    * A **cron job** periodically pushed the chat messages from Redis to the MySQL database for long-term storage
    * `/messages?` query filtering (such as by specific server, all servers, sent by user, at a certain time, etc.) programmatically accounted for messages in both Redis and MySQL and maintained a chronological log
  * Dynamic **player permissions** (`GET /permissions`) with eligibility criteria designed in flexible "AND" or "OR" guards
    * Plugin logic *never* handled nodes locally via files. They required an authoritative source of truth by design
  * A moderation **punishment/infraction system** with various infraction types (warn, kick, mute, ban), temporary duration support, silented invocations to deter public notification, per-player infraction record, cron jobs for removing expired punishments, and more
  * **Friends system** (add, remove, pending requests, list, resolvers and integration with vanish/nick system)
  * **Argus's internals** (the internal staff panel) for handling auth/RBAC/account states                                                                                                                                                                                                                                                                                                                                                                                                                                            
</details>
-->
